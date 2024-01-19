setHook("rstudio.sessionInit", function(newSession) {
  if (newSession)
    message("Welcome to your Lab! To get started, you can access your starter files and dataset in your 'Files' tab within RStudio. Sample data this week is stored under Module8.")
    rmarkdown::render("/home/rstudio/Instructions.Rmd", params = "ask")
    viewer <- getOption("viewer")
    viewer('/home/rstudio/Instructions.pdf')
}, action = "append")
