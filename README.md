PowerShell Script to Validate Azure Key Vault Secret Password Complexity

Purpose of this script:

Authenticates to Azure.
Prompts the user to enter an Azure Subscription ID.
Sets the active subscription.
Prompts for a Key Vault name and Secret name.
Retrieves the secret value from Azure Key Vault.
Validates the secret against the following password policy:

Minimum length of 17 characters
At least one uppercase letter
At least one lowercase letter
At least one numeric digit
At least one special character


Outputs an audit-friendly summary without exposing the secret value.
