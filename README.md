# Sok-2013_data

#Hvordan laste inn dataen:

# Last ned nødvendig pakke
library(readr)

# Last inn data ved bruk av URL
url <- "https://raw.githubusercontent.com/Heppyo/Sok-2013_data/main/final_data.csv"

# Importer data inn i R
data <- read.csv(url)

# View the first few rows of the imported data
head(data)

# Datasettet er ikke nødvendigvis fullstendig før 11/09
