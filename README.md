# collab-whoi
It'd be great to use this repo to have a script that uses tidyverse to make the "wide" Pescadero plankton (and/or benthic) sorting datasheets into "long" format for analyses

Bethany agrees, Stace wonders if we can call a Google sheet into R using something from the readr package? Decided not to use the googlesheets package but rather to pull in from excel:

> library(readxl)
> Bethany_data <- read_excel("Benthic_slurps_ISS5_Bethany_Fleming_20181017.xlsx")
> View(Bethany_data)
