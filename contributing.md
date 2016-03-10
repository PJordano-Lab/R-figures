
## How to use this repository

You can just browse the figures available [here](https://github.com/PJordano-Lab/R-figures). If you click on any figure, it will take you to the source code used to produce it (actually an HTML report with the R code and the resulting graphic). The original Rmarkdown document is also available in the same repository.


### To contribute:

1. **Clone** or **Pull** the latest version of this repository from GitHub.

2. Open and fill in `Rmd_template.Rmd`. Save it in the appropriate folder (e.g. Spatial, Networks...) with an informative name (e.g. `bipartite_network.Rmd`). 

3. Knit your Rmd. This will generate an HTML output file and one (or more) figures in the `figures` folder.

4. Open `README.Rmd` to include your figure in the appropriate section (e.g. Spatial, Networks, etc). Just insert a chunk wherever you want the figure to appear, like in this example:

```{r}     
insert("My figure", "Networks/bipartite_network.Rmd")     
```

where "My figure" is the title, and the second argument is the path to your Rmd source document. 
    
5. Knit `README.Rmd`. This will generate `README.md`.
    
6. **Commit** everything (the `Rmd`, `html` and `png` files, plus `README.Rmd` and `README.md`) and **push**  to the GitHub repository.

Thanks!

