
<!-- README.md is generated from README.Rmd. Please edit that file -->
SSPA
====

This repo provides information on the module Sustainable and Spatial Planing and Analysis (SSPA). The 2019 module catalogue can be found [here](http://webprod3.leeds.ac.uk/catalogue/dynmodules.asp?Y=201819&M=TRAN-5115M), the timetable [here](http://timetable.leeds.ac.uk/teaching/201819/reporting/Individual?objectclass=module&idtype=name&identifier=TRAN5115M01&&template=SWSCUST+module+Individual&days=1-7&weeks=1-52&periods=1-21).

The main program used for the practicals is QGIS.

If you are confident with computing and want to write code, you can also use R.

References
----------

For a list of references related to the course see here: <https://www.zotero.org/groups/418217/energy-and-transport/items/collectionKey/S97S2EAX>

If you want those references on your computer, you can run the following commands in R (assuming you have the right packages installed):

``` r
refs = RefManageR::ReadZotero(group = "418217", .params = list(collection = "S97S2EAX", limit = 100))
#> Ignoring entry 'iacono_access_2008'  (line2) because:
#>  A bibentry of bibtype 'TechReport' has to specify the field: institution
RefManageR::WriteBib(refs, "references.bib")
#> Writing 9 Bibtex entries ...
#> OK
#> Results written to file 'references.bib'
```

Info on using R
---------------

If you want to use R for the course, the links below may be useful.

It assumes you have a basic understanding of R and spatial data, that can be obtained by following an online tutorial such as that provided by DataCamp or by following [Chapter 2](https://geocompr.robinlovelace.net/spatial-class.html) of the online book [Geocomputation with R](https://geocompr.robinlovelace.net/).

The main tutorial is [accessability](https://github.com/ITSLeeds/SSPA/blob/master/accessability.Rmd), which is best followed as a print-out from the `accessibility.pdf` file provided as a download in the project's [releases](https://github.com/ITSLeeds/SSPA/releases).

<!-- Before starting you sould download the project repo (which contains the necessary data) from: [github.com/ITSLeeds/SSPA/archive/master.zip](https://github.com/ITSLeeds/SSPA/archive/master.zip). -->
