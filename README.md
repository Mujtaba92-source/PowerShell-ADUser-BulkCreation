AD Bulk User Creation Script
This PowerShell script automates the creation of multiple Active Directory user accounts with randomly generated names.

Usage
Edit Variables: Modify the following variables at the top of the script to suit your needs:

$PASSWORD_FOR_USERS: Set a default password for all users (e.g., "Password1").
$NUMBER_OF_ACCOUNTS_TO_CREATE: Specify how many accounts to create (e.g., 10000).
Run the Script: Execute the script in a PowerShell environment with the necessary permissions to create users in Active Directory.

Functionality
Generates random first and last names using consonants and vowels.
Creates user accounts in Active Directory with:
Username format: firstName.lastName
Password set to never expire.
Requirements
PowerShell with Active Directory module installed.
Appropriate permissions to run the script and create user accounts in Active Directory.
