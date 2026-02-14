# Riot Accounts Checker

A small CLI utility to verify Riot Games account credentials against the official authentication endpoint.

It supports checking a single account directly from the command line or bulk-checking credentials from a file.

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/riot-accounts-checker.git
cd riot-accounts-checker
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Usage
Check a single account
```bash
python riot_accounts_checker.py -u myusername -p mypassword
```
Check multiple accounts from file

Create a text file with one account per line in the following format:
```bash
username1:password1
username2:password2
```
Then run:
```bash
python riot_accounts_checker.py -f accounts.txt
```
The script will print VALID or INVALID for each account.
Notes

    Credentials must be in username:password format.

    The tool uses Riot's authentication API and requires an active internet connection.
 
