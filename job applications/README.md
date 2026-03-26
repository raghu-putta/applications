# Job Application Bot

An AI-powered LinkedIn Easy Apply assistant that helps you auto-fill forms, answer questions, and submit applications.

## How it works
1. Reads your configuration from `config/personals.py` (your name, phone, location, and question preferences).
2. Uses `config/secrets.py` for LinkedIn login (keep this file private).
3. Runs the automation from `runAiBot.py`.

## Setup
1. Install Python 3.10+.
2. In this folder, install dependencies:
   - `pip install -r requirements.txt`
3. Update:
   - `config/personals.py` with your details.
   - `config/settings.py` with bot preferences.
   - `config/secrets.py` with your LinkedIn login username/password.

## Run
From `job applications/`:
`python runAiBot.py`

## Contact
Raghu Putta <raghuputta46@gmail.com>

