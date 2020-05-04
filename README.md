# Covid-19-Assistant
Covid-19 Assistant is a chatbot which provide you real time information regarding the current situation in india. 
This chatbot is built using dialogflow and Python

# Usage
pip install -r requirements.txt

## create your intents, entities, parameters in Google Dialogflow
## connect your Dialogflow bot with python
@
* DIALOGFLOW_PROJECT_ID = 'your-project-ID' -- provide your project ID here
* os.environ["GOOGLE_APPLICATION_CREDENTIALS"] = 'google_key.json' -- download google key from service accounts (.json file)

## connect your Facebook messenger to python
@app.py
* VERIFY_TOKEN = ''  # <paste your verify token here>
* PAGE_ACCESS_TOKEN = ''  # paste your page access token here>"

Note: Dialogbot.py works individually to test the performance of the bot.
