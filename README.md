** This project is a flask App for sending and also for keeping a list of messages that is send by the user. **

# Example Application - Complimentr (Made this app by learning from the below course )

https://github.com/craigsdennis/intro-to-apis-course

## Use this on Glitch

choose **Tools** >> **Extras** >> **Git Import and Export** >> **Import from GitHub** when prompted enter the git repo

## This project is Live on GLITCH

[devanshu-twilioapi.glitch.me](https://devanshu-twilioapi.glitch.me)

## Local Installation

Copy `.env.example` to `.env` and **UPDATE IT WITH YOUR [Twilio](https://twilio.com) credentials **.

### Running the application(Windows)

- `python -m venv .venv`
- then cd to `.venv/Script/` dir and activate it by using this `& ./activate`
- `pip install -r requirements.txt`
- `flask run`

### Running the application(linux or mac)

- `python -m venv .venv`
- `source ./.venv/bin/activate`
- `pip install -r requirements.txt`
- `FLASK_ENV=development flask run`

#### In Development mode

- Run [ngrok](https://ngrok.com/) on port 5000
- Visit your ngrok url!
