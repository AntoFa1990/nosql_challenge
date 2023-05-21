# nosql-challenge

This is a use case for Pymongo analyzing ratings data for retaurants.

## Tools Used

Python, Jupyter, pymongo, pprint, pandas, mondo

## Usage Instructions

Open the notebooks.
Import the json file using: mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
First run the setup notebook. 
Then run the analysis notebook.