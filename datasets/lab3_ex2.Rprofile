.First <- function() {
  message("Type go() and hit Enter to get started!\n")
  
  go <<- function() {
    source(".init.R")
    file.edit("lab3_ex2.Rmd")
  rmarkdown::render("lab3_ex2.Rmd")
  myViewer <- getOption("viewer")
  file.copy("lab3_ex2.html", file.path(tempdir(), "lab3_ex2.html"))
  myViewer(file.path(tempdir(), "lab3_ex2.html"))
  }
}
