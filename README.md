# ai_documenter_for_fabric
A set of notebooks that enable AI to create markdown documentation of your Fabric environment

Be sure to update the config sections of the notebooks
# =========================
# CONFIG
# =========================
ORG = <ENTER YOUR ORG>                 # e.g. "myorg"
PROJECT = <ENTER YOUR PROJECT NAME>
TARGET_REPO_NAME = <YOUR REPOS NAME>
BRANCH = "refs/heads/main"             # updated branch if needed
API_VERSION = "7.1"

## Azure Devops Personal Access Token
# PAT (recommended: store in Key Vault / Fabric secret; paste here for first run)
AZDO_PAT = mssparkutils.credentials.getSecret(<YOUR KEY VAULT URL>, <YOUR AZDO PAT>)

# Where to write in Lakehouse Files
RAW_ROOT = <PATH YOU WANT TO WRITE FILES TO>  # relative path in Spark notebook points to Lakehouse Files 
