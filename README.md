---
editor_options:
  markdown:
    wrap: 72
    canonical: true
---

## Advanced Reproducible Research in R

# AdvancedR3:

This is the most advanced R course, where everyone is having trouble
installing RStudio and other packages.

# Brief description of folder and file contents

The following folders contain:

-   `data/`: Processed lipidomic data
-   `doc/`: Documents
-   `R/`: I dont know, nice R scripts i'd recon
-   `renv/`: enviroment stuff

# Installing project R package dependencies

Dependencies have been managed by using
`usethis::use_package("packagename")` through the `DESCRIPTION` file,
installing dependencies is as easy as opening the `AdvancedR3.Rproj`
file and running this command in the console:

```         
# install.packages("remotes")
remotes::install_deps()
```

You'll need to have remotes installed for this to work.

# Resource

For more information on this folder and file workflow and setup, check
out the [prodigenr](https://rostools.github.io/prodigenr) online
documentation.
