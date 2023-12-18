#Used Python to upload 2 CSV files from folder on desktop to Azure Cloud storage location and used Windows Task Scheduler to set up time to automatically run code
[CSV file upload.pdf](https://github.com/jtasker811/Data-Engineering/files/13708215/CSV.file.upload.pdf)

#Created cloud based pipeline on Keboola Connection to move my newly uploaded files from Azure to Keboola for a SQL transformation to be automatically performed as the 2nd stage of the data pipeline.

![SnowflakeSQL](https://github.com/jtasker811/Data-Engineering/assets/105367089/637d03f9-718f-4e4d-98a3-19f63e862678)
![Keboola Pipeline](https://github.com/jtasker811/Data-Engineering/assets/105367089/00391435-f60c-4ac0-96dd-7b9497708d32)

#SQL transformation joined the 2 CSV files on loyalty number and created new calculated/aggregated columns to provide better insights.

#Next stage of data pipeline was to then save a CSV version of the newly transformed file to the same Azure location to later connect to PowerBI.

![DRIVE SNAP](https://github.com/jtasker811/Data-Engineering/assets/105367089/000729fe-224c-42dc-a8b4-89a93d61506a)
![CSV SNAP](https://github.com/jtasker811/Data-Engineering/assets/105367089/5989087e-dc51-4b78-95c7-ea209a45ab4c)

#The Azure Cloud container was then connected to PowerBI to visualize the insights in a dashboard and a scheduled refresh was set-up to ensure entire ETL process was automated.

[airline_loyalty.pdf](https://github.com/jtasker811/Data-Engineering/files/13708283/airline_loyalty.pdf)
