# Create your environment
Below code creates venv and names if .venv  
`python -m venv .venv`

# Activate venv
`.venv/scripts/activate`

# Deativate venv
`deativate`

# Requirements.txt
- List of all libraries needed  

## Install requirements
`pip install -r requirements.txt`

## Show all libraries
`PIP list`

## Get all current packages and versions into Txt File
`PIP freeze > filename.txt`

## Get python version
`python -V`

## Upgrade all current libraries to their highest available versions
1. `pip install -r requirements.txt`
2. Replace all '==' with '>='
3. `pip install -r requirements.txt --upgrade`  

## Azure KeyVault Identity
`pip install azure.indentity`  
`pip install azure.keyvault`  
