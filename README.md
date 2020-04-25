# Non-immigrants' Statistics

The project "Non-immigrants' Statistics" collects data from different sources in order to determine the non-immigrants' trends in US states.
The data would give the ability to analyze the trends around non-immigrants while showing the influx and efflux of induviduals within the American states.

airport-codes_csv.csv - Airport Code Table
I94_SAS_Labels_Descriptions.SAS - I94 Immigration Data (Labels Descriptions)
us-cities-demographics.csv - U.S. City Demographic Data
immigration_data_sample.csv - I94 Immigration Data (Data Sample with 1000 records)
sas_data - I94 Immigration Data (In Parquet files) (Over 3 million records)

## Creation of an S3 bucket

Create an AWS S3 bucket at (https://s3.console.aws.amazon.com/)

## Usage

Edit dl.cfg and add the AWS credentials details.
[AWS]
ACCESS_KEY_ID=<!--ENTER AWS KEY ID HERE-->
SECRET_ACCESS_KEY=<!--ENTER AWS SECRET KEY HERE-->


```jupyter notebook
open on Jupyter "Capstone Project Template.ipynb"
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT]