# open-eo
Source universe for: open-eo
if (!require(devtools)) {
  install.packages("devtools",dependencies=TRUE)
  library(devtools)
}
install_github(repo="Open-EO/openeo-r-client",dependencies=TRUE)
library(openeo)
