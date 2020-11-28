# [بوت الرفع لليوتيوب](https://t.me/meaallh100)


**Environment Variables**

* `BOT_TOKEN`(Required) - Get your bot token from [Bot Father](https://tx.me/BotFather "Bot Father").
* `SESSION_NAME`(optional) - Your bot's username.
* `API_ID`(Required) - Your telegram api id, get from [Manage Apps](https://my.telegram.org).
* `API_HASH`(Required) - Your telegram api hash, get from [Manage Apps](https://my.telegram.org).
* `CLIENT_ID`(Required) - Your google client id.
* `CLIENT_SECRET`(Required) - Your google client secret.
* `BOT_OWNER`(Required) - Telegram id of bot owner.
* `AUTH_USERS`(optional) - Telegram id's of authorised users, separated by `,`.
* `VIDEO_DESCRIPTION`(optional) - Any default description to be aded to the video.
* `VIDEO_CATEGORY`(optional) - YouTube's video category id. If not specified or specified id is invalid, category id will be selected randomly.
* `VIDEO_TITLE_PREFIX`(optional) - Any prefix to be added to the video's title.
* `VIDEO_TITLE_SUFFIX`(optional) - Any suffix to be added to the video's title.
* `UPLOAD_MODE`(optional) - The video's privacy status. Valid values for this property are: `private`, `public`, `unlisted`.
* `DEBUG` (optional) - Whether to set logging level to DEBUG. If set logging will be set to DEBUG level, else INFO level.

**Getting your `CLIENT_ID` and `CLIENT_SECRET`**

* Head to [Google console](https://console.developers.google.com "Google console"), create a new project named `Youtube Uploader` and enable `API'S AND SERVISES`. Search for `YOUTUBE DATA API v3` and enable the API. Go to [Credentials](https://console.developers.google.com/apis/credentials "Credentials") page, select your project `Youtube Uploader` create a new credential with `desktop` as type. Copy the `CLIENT_ID` and `CLIENT_SECRET`. 
* You have to verify your application with google, only then you can make the uploaded videos public. YouTube changed its developer policy, and videos uploaded using unverfied applications will be kept private.

**Install requirements**

Run :
```bash
$ pip3 install -r requirements.txt
```

**Run bot**

Lets run our bot for the first time!
```bash
$ python3 -m bot
```
If you did everything correctly, the bot should be running. Go do `/start` to see if the bot is live or not. Follow the instructions provided by bot to setup authorisation and to start uploading.


**Or the easy way of directly deploying to heroku**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)



