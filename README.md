# DSCI 310 Group 13
# Project Title: Predicting Youtube View Count in 2007/2008

## Contributors: Chris Cai, Maggie Dong, Billy Jia

## Summary:
Youtube is one of the most popular websites in the world. Many people at some point in their lives may have thought whether or not they wanted to become a Youtuber as a future job. Data research and analysis would help any person looking to become a Youtuber to figure out how certain categories of data impact the number of views on a video. This analysis will try to predict the future view counts of Youtube videos based on previous view counts. The dataset used tracks categories like video ID, uploader, **age**, category, **length**, **views**, **rate**, **rating**, **comment count** and related IDs, but only the data in bold will be explored in the analysis as the other features are not important towards the prediction.

## Procedure of generating the report
To **setup**, please use the command: `docker pull chrisckh/dsci-310-project-group-13:0.0.0` to download the docker image and use the command: `docker run --rm -p 8787:8787 -e PASSWORD="asdf" chrisckh/dsci-310-project-group-13:0.0.0` to run the Rstudio container. Then type `http://localhost:8787/` in a web browser to open the container and login with Username: `rstudio` , and Password: `asdf` .  

To **generate the report** , please go to the analysis folder, open analysis.Rmd, and click the **Knit** button. 

## Dependencies:
R version 4.2.2, R packages, analysis.Rmd, and raw data used can be found in the Dockerfile

## License
The predict-youtube-future-views project is made available under the **Attribution 4.0 International** ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/))
