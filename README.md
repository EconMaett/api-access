# Access economic data through APIs

<!-- badges: start -->
<!-- badges: end -->

Check out lecture number eight "R Databases and APIs" of Matthew DeHaven's course [Applied Economic Analysis](https://matthewdehaven.com/course-applied-economics-analysis-2024-Spring/).

Also have a look at chapter 1.2.2 "Reading from APIs" in J. Renato Leripio's book [R for Economic Research](https://book.rleripio.com/ds_tidyverse#readapi).

Note that the [`{httr2}`](https://httr2.r-lib.org/) R package has superseded `{httr}`.

Check out [`{RCurl}`](https://CRAN.R-project.org/package=RCurl ) and [`{jsonlite}`](https://github.com/jeroen/jsonlite).

To access SNB Data, see the guide [How to use the data.snb.ch API with R](https://data.snb.ch/api/cube/bakredsekbrm/script/R/en?dimSel=D1(T0,H),D3(T1,AA,A,B,DE,F,I,JLMN,P,Q,RS,U,SX1)&fromDate=2023-06&toDate=2024-06).

Take inspiration from Maximilian Mücke's [`{bbk}`](https://github.com/m-muecke/bbk/blob/main/R/snb.R) R package and from Enrico Schumann's [`{SNBdata}`](https://github.com/enricoschumann/SNBdata) package.

A nice starting point for a package is this script <https://github.com/econpulse/snbdata/blob/main/get_snb.R>.

To create your own R package, simply follow the instructions in the second edition of Hadley Wickham's book [R Packages](https://r-pkgs.org/).

User expresso has a great collection of homemade packages that access economic data at <https://github.com/expersso?tab=repositories>.

To see how Andrew Leach accesses the EIA API, check out <https://github.com/leachandrew/weekly_charts/blob/main/weekly_charts.Rmd>. Since the professor uses Abiel Reinhart's [`{pdfetch}`](https://github.com/abielr/pdfetch) R package, you might want to have a look at it.



