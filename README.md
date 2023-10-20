## README

The [R-Universe](https://r-universe.dev/search/) platform provides a github-hosted 
indexer as an alternative to submitting R-packages to CRAN. This repository 
contains a JSON file that is regularly indexed for the listed publicly available 
R-packages developed by IIASA staff. 

Any R-package listed in the json will be built and made available on [https://iiasa.r-universe.dev/](https://iiasa.r-universe.dev/builds). 

The listed R-packages can then be installed by providing an additional repository
to `install.packages()`.

**Example:**
```
# Install the ibis R-package
install.packages('ibis.iSDM', repos = "https://iiasa.r-universe.dev")
```

To add a new R-package to the indexer, simply edit the JSON in this repository.

For more information, 
see the [blog post](https://ropensci.org/blog/2021/06/22/setup-runiverse/) on r-universe.
