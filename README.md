<h1 align="center">⚡ gclonebot ⚡<br></h1> 

<p align="center">gclonebot is a telegram bot that allows you to copy folder/team drive to team drives. One of the main advantage of this bot is that you can host it to Heroku for free.<p/>

#### ✅ Advantages
- Use server side copy
- Bypass the 750Gb a day limit thanks to Service accounts
- Duplicate team drive
- Copy public folders & files to team drives

#### ❌ Drawbacks
- Does not support files upload (only copy)
- You cannot copy the data to My Drive

1. Download this repo
2. Open the config.ini file (inside the telegram_gcloner folder) and fill the following values :
> path_to_gclone =./gclone  `(add .exe if you use Windows)`<br>
> telegram_token = `go to @BotFather and send /newbot to get one`<br>
> user_ids = -1 = `Your user id (go to @MissRose_bot and type /id to get your id) - If you want to authorize multiple users, add a comma between each ID (ex: 150654065,5897065)`<br>
> group_ids = `your telegram group ID (leave it blank if you don't want to add one). To get your group id, go to @MissRose_bot and type /id`<br>
> gclone_para_override = `leave this empty if you don't know how to use it`<br>
3. Install [python](https://www.python.org/downloads/)
4. cd to the folder containing the bot
5. run `sudo pip install -r requirements.txt`
6. cd to the telegram_gcloner folder and run : `py telegram_gcloner.py`
7. Start your bot and you can copy your data!
