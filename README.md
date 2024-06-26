# You can make an R package too!

Talk given for

-   [Research Coding Club](https://researchcodingclub.github.io/), at
    the University of York, UK

Slides: [You can make an R package too!](https://bit.ly/3mma-pkg)

Based on

-   [R Packages (2e)](https://r-pkgs.org/) by Hadley Wickham and Jennifer Bryan

-   [Data Science for Modern and Open Research: You can make an R package
    too!](https://3mmarand.github.io/DDA/slides/you-can-make-an-r-package.html#1) Talk at the Danish Diabetes Academy Winter School for Postdocs 2021

-   [Forwards Package development
    modules](https://github.com/forwards/workshops) by Emma Rand and Mine Cetinkaya-Rundel.
    

Licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative
Commons Attribution-NonCommercial-ShareAlike 4.0 International
License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" alt="Creative Commons License" style="border-width:0"/></a><br />

## Summary

In this talk I'll be covering *why* you might make an R package and
*how* you can make one (spoilers: there are more reasons than you
probably think; it's easier than you probably think). The talk should be
accessible to people with minimal R experience and immediately useful to
those who have been using R for a while. I will discuss where packages
come, where they live on your computer and the different states a
package can be in. I will then live-code making a minimal package using
the **`devtools`** approach. We will add functions, documentation,
dependencies and a license. I will also show you how to check the
package and how to use it interactively.

## Learning Objectives

by the end of this session you will able to:

-   explain the rationale for writing packages
-   describe the different states a package can be in
-   create a minimal package and explain its key components
-   add functions with `usethis:use_r()`
-   use the package interactively with `devtools::load_all()`
-   use `devtools::check()` to execute `R CMD` check
-   add a license with `usethis::use_mit_license()`
-   add documentation using **`roxygen2`** and `devtools::document()`
-   add package dependencies with `usethis::use_package()`

## Prerequisites for coding along

If you want to code along with the live coding you will need:

-   [R and RStudio](prerequisite-guides/install-r-rstudio.md)
-   [R build toolchain](prerequisite-guides/install-pkg-dev-tools.md): Rtools(windows) or XCode (mac) or r-base-dev
-   the following packages: `devtools` and `assertthat`

You can verify your system is set up by running:

`devtools::has_devel()`

in the console
