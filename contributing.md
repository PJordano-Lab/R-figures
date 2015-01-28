
## How to use this repository

You can just browse the figures available [here](https://github.com/PJordano-Lab/R-figures). If you click on any figure, it will take you to the source code used to produce it (actually an HTML report with the R code and the resulting graphic). The original Rmarkdown document is also available in the same repository.

You can also use http://htmlpreview.github.io to view the source code and the resulting graphic in a single html file (e.g. http://htmlpreview.github.io/?https://raw.github.com/PJordano-Lab/R-figures/blob/master/Spatial/topomap.html)


### To contribute:

1. **Pull** the latest version of this repository from GitHub.

2. Place a copy of the Rmarkdown document and the resulting HTML file (after knitting) in the appropriate folder (e.g. Spatial, Networks...). If needed, include also a minimal dataset to make the example reproducible (e.g. `topomap_data.rda` to accompany `topomap.Rmd` and `topomap.html`).
**Important**: always include a final chunk in the Rmarkdown file to provide session info, like this: `sessionInfo()`.

3. Put a small-size copy of your resulting figure (e.g. `topomap.png`) in the `figures` folder of the main repository.

4. Open `README.Rmd` and include your figure in the appropriate section: just write a short caption and include the final figure with a link to the source code, like this:

`#### Topographic map with contour lines`

`[![](figures/your_figure_name.png)](http://github.com/PJordano-Lab/R-figures/blob/master/your_theme/your_figure_name.Rmd)`
    
5. Knit `README.Rmd` to markdown (`README.md`).
    
6. **Commit** everything (the `Rmd`, `html` and `png` file of your figure, plus `README.Rmd` and `README.md`) and **push**  to the GitHub repository.

Thanks!

