# Read Parquet Files from an Azure Storage Account
This project utilizes keyvault to retrieve credentials and creates temporary SAS tokens for each individual blob. We read these parquet files with pandas and see the first top 5 rows.  

## Imports
- azure.identity
- azure.keyvault.secrets
- azure.storage.blob
- pandas