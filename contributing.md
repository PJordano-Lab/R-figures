
## How to use this repository

You can just browse the figures available [here](https://github.com/PJordano-Lab/R-figures). If you click on any figure, it will take you to the source code used to produce it (actually an HTML report with the R code and the resulting graphic). The original Rmarkdown document is also available in the same repository.


### To contribute:

1. **Clone** or **Pull** the latest version of this repository from GitHub.

2. Place a copy of the Rmarkdown document and the resulting HTML file (after knitting) in the appropriate folder (e.g. Spatial, Networks...). If needed, include also a minimal dataset to make the example reproducible (e.g. `topomap_data.rda` to accompany `topomap.Rmd` and `topomap.html`).
**Important**: always include a final chunk in the Rmarkdown file to provide session info, like this: `sessionInfo()`.

3. Put a small-size copy of your resulting figure (e.g. `topomap.png`) in the `figures` folder of the main repository. **Important**: the figure file (.png) must have the same name as the Rmarkdown and HTML file associated to it.

4. Open `README.Rmd` and include your figure in the appropriate section: just write a short caption (4 hash symbols (####) followed by the figure title) and then include a knitr chunk like in this example:

`#### Topographic map with contour lines`  
`{r}`   
`fig_insert("Spatial", "topomap")`  

where "Spatial" is the general theme of your figure (e.g. Spatial, Networks, etc), and "topomap" is the name of your figure.
    
5. Knit `README.Rmd` to markdown (`README.md`).
    
6. **Commit** everything (the `Rmd`, `html` and `png` file of your figure, plus `README.Rmd` and `README.md`) and **push**  to the GitHub repository.

Thanks!

