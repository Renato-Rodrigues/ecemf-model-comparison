# ECEMF model comparison

Data and visualizations created for analysing ecemf results on EU climate scenarios 

authors: Renato Rodrigues and Robert Pietzcker

Modellers and contributors: Robert Pietzcker, Muhammad Awais, Maro Baka, Francesco Dalla Longa, Harmen Sytze de Boer, Mark M. Dekker, Laurent Drouet, Jakob Dürrwächter, Johannes Emmerling, Amir Fattahi, Emir Fejzic, Theofano Fotiou, Panagiotis Fragkos,  Robin Hasse, , Johanna Hoppe, Daniel Huppmann, Maria Kannavou, Michal Lewarski,  Stefan Pfenninger-Lee, Sebastian Osorio, Renato Rodrigues, Francesco Sanvito, Joanna Sitarz, Igor Tatarewicz, Will Usher, Bob van der Zwaan, Behnam Zakeri, Gunnar Luderer

# License

- Results and visualizations are provided under a CC-BY-4.0 licence.
- The visualizations created by this code are available at: https://renato-rodrigues.github.io/ecemf-model-comparison/paperCharts.html

# Reproduction

- Use knit `rmarkdown::render("paperCharts.Rmd")` to create the charts.
- The script will try to install all required libraries. In case you need to install them manually, all packages can be installed via `install.packages`

```R
pkgs <- c("tidyr", "dplyr", "ggplot2", "grid", "gridExtra", "ggh4x", "ggrepel")
install.packages(pkgs)
```

- Raster image files, pngs, and vectorial image files, svgs, will be saved to the output folder.
- Additionally, an html report file will be created containing all charts.

