# Lifebrain R-universe 

[![:name status badge](https://lifebrain.r-universe.dev/badges/:name)](https://lifebrain.r-universe.dev)
[![:registry status badge](https://lifebrain.r-universe.dev/badges/:registry)](https://lifebrain.r-universe.dev)
[![:total status badge](https://lifebrain.r-universe.dev/badges/:total)](https://lifebrain.r-universe.dev)

All packages developed, at least partly, as part of the Lifebrain EU consortium are added to this universe.
The only exepctions are the brain parcellations for different atlases for the ggseg and ggseg3d packages, which are numerous and collected in their own universe for easier access.

Accessing the packages in this universe through R, is a matter of adding the universe to the repositories the R installation function searches when installing a package.

```r
# Enable repository from lifebrain
options(repos = c(
  lifebrain = 'https://lifebrain.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'))
  
# Download and install metagam in R
install.packages('metagam')

# Browse the metagam manual pages
help(package = 'metagam')
```

## The ggseg R-universe

[![:name status badge](https://ggseg.r-universe.dev/badges/:name)](https://ggseg.r-universe.dev)
[![:registry status badge](https://ggseg.r-universe.dev/badges/:registry)](https://ggseg.r-universe.dev)
[![:total status badge](https://ggseg.r-universe.dev/badges/:total)](https://ggseg.r-universe.dev)

```r
# Enable repository from ggseg
options(repos = c(
  ggseg = 'https://ggseg.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'))
  
# Download and install metagam in R
install.packages('ggseg')

# Browse the metagam manual pages
help(package = 'ggseg')
```

# Enable both universes

```r
# Enable repository from ggseg
options(repos = c(
  ggseg = 'https://ggseg.r-universe.dev',
  lifebrain = 'https://lifebrain.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'
))
  
# Download and install metagam in R
install.packages('ggseg')

# Browse the metagam manual pages
help(package = 'ggseg')
```

# Funding

**EU Horizon 2020 Grant:** Healthy minds 0-100 years: Optimising the use of European brain imaging cohorts (Lifebrain).

**Grant agreement number:** 732592.

**Call:** Societal challenges: Health, demographic change and well-being
