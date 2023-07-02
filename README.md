# SAEON-datadownload

This app is created as an interface to download data from SAEON Observation Database (https://observations.saeon.ac.za/)

The R shiny app is hosted on shinyapps.io at http://googlie.shinyapps.io/SAEON_data_download and the source code provide in this repo.

## Pre-reqursites to using the app

One needs to log into there SAEON Observation Database account at https://observations.saeon.ac.za/, if not signed up they will need to sign up. 

Once logged in, the user can go to https://observations.saeon.ac.za/account/token to obtain the token required to entire the app to download data from the SAEON data platform. 

## Lauching the app from your local pc in RStudio

In a new R script one can use the following code to launch the app providing that the package shiny is installed.

    library(shiny)
    runGitHub(repo = "SAEON-datadownload", username = "Brishan200", ref = "main")



