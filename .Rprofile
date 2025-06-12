# Activate renv (loads correct library paths)
if (requireNamespace("renv", quietly = TRUE)) {
  renv::activate()
}

# Optionally auto-load commonly used packages (but NOT auto-install)
required_packages <- c("dplyr", "readxl", "rvest")
invisible(lapply(required_packages, function(pkg) {
  if (requireNamespace(pkg, quietly = TRUE)) {
    library(pkg, character.only = TRUE)
  }
}))

source("renv/activate.R")

