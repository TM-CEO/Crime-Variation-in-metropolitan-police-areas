# Crime-Variation-in-metropolitan-police-areas

This project is to develop a comprehensive dashboard utilising UK MPS (Metropolitan Police Service)
Monthly Crime Datasets, illustrating key metrics and insights into the crime statistics within the Metropolitan Police area.

MPS Crime data contains Crimes in London metropolitan police areas. Metropolitan Police District
consists of the 32 London boroughs but does not include the City of London proper – the central financial district – which is policed by a separate force, the City of London Police. All data is broken down by financial year for each crime type and can be filtered by Basic Command Unit (BCU) and Borough.
You can find more details about the Metropolitan Police on this web page.

website link - https://www.met.police.uk/

If you need to download dataset according to this project, please follow bellow link. And it's a collection of datasets.

Dataset - https://data.london.gov.uk/dataset/mps-monthly-crime-dahboard-data

## Steps of this SQL project

1. Create a new database in MS SQL server called "LondonCrimeDB"

2. Import the downloaded dataset into new database and clean dataset.

3. Then identify the primary keys and the foreign keys of this datasets and connect them into one dataset using SQL joins. In this, I created a "view" using the "union" join. View is a virtual table that we created to store data in different tables easily. Same columns in each table is mandatory when joining.

4. Connect the SQL server to powerBI and make the dashboard.

## Thank you!
