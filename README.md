# File-sharing-Bot


Telegram Bot to store Posts and Documents and it can Access by Special Links.
I Guess This Will Be Usefull For Many People.....😇. 

##

**If you need any more modes in repo or If you find out any bugs, mention in [@XurseXFriends ](https://www.telegram.dog/XurseXFriends)**

### Features
- Fully customisable.
- Customisable welcome & Forcesub messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.

### Setup

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub 

##
### Installation
#### Deploy on Heroku
**BEFORE YOU DEPLOY ON HEROKU, YOU SHOULD FORK THE REPO AND CHANGE ITS NAME TO ANYTHING ELSE**<br>
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)</br>
<a href="https://youtu.be/LCrkRTMkmzE">
  <img src="https://img.shields.io/badge/How%20to-Deploy-red?logo=youtube" width="147">
</a><br>
**Check This Tutorial Video on YouTube for any Help**<br>


#### Deploy in your VPS
````bash
git clone https://github.com/Akeonowl/Private
cd Private
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
````

### Admin Commands

```
/start - start the bot or get posts

/batch - create link for more than one posts

/genlink - create link for one post

/users - view bot statistics

/broadcast - broadcast any messages to bot users
```

### Variables

* `API_HASH` buat API HASH di my.telegram.org
* `API_ID` buat API ID di my.telegram.org
* `TG_BOT_TOKEN` Token Bot dari @BotFather
* `OWNER_ID` Owners ID pembuat Bot
* `CHANNEL_ID` Channel Database dapatkan id di @TGIdsBot eg:- -100xxxxxxxx
* `ADMINS` List ID admin bot, pisahkan dengan spasi jika lebih dari 1 admin
* `START_MESSAGE` Masukkan start message atau biarkan default
* `FORCE_SUB_MESSAGE`Pesan Force Subs channel, ubah sesuai kemauan
* `FORCE_SUB_CHANNEL` ID Channel yang mau di Force Subs

### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - Nama depan User
* `{last}` - Nama belakang User
* `{id}` - User ID
* `{mention}` - Mention user
* `{username}` - Username



