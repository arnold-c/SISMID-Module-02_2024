source("renv/activate.R")

if (interactive()) {
  httpgd::hgd(port = 51000, token = "BoVAZhHWyF")
}

# if (interactive() && Sys.getenv("RSTUDIO") == "") {
#   Sys.setenv(TERM_PROGRAM = "vscode")
#   if ("httpgd" %in% .packages(all.available = TRUE)) {
#     options(vsc.plot = FALSE)
#     options(device = function(...) {
#       httpgd::hgd(silent = TRUE)
#       .vsc.browser(httpgd::hgd_url(history = FALSE), viewer = "2")
#     })
#   }
#   source(file.path(Sys.getenv(if (.Platform$OS.type == "windows") "USERPROFILE" else "HOME"), ".vscode-R", "init.R"))
# }

options(vsc.rstudioapi = TRUE)
