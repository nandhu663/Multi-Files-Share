# File-sharing-Bot

<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg" width ="250">
  </a>
  <a href="https://t.me/tvseriezzz_update">
    <img src="https://github.com/nandhu663/PyrogramGenStr/blob/main/resources/madebymotech-badge.svg" width="250">
  </a><br>
  <a href="https://t.me/tvseriezzz">
    &nbsp;<img src="https://img.shields.io/badge/tvseriezzz_channel?style=flat-square&logo=telegram" width="130" height="18">&nbsp;
  </a>
  <a href="https://t.me/tvseriezzz">
    &nbsp;<img src="https://img.shields.io/badge/tvseriezzz_group?style=flat-square&logo=telegram" width="130" height="18">&nbsp;
  </a>
  <br>
  <a href="https://github.com/nandhu663/Multi-Files-Share/stargazers">
    <img src="https://img.shields.io/github/stars/https://github.com/nandhu663/Multi-Files-Share?style=social">
  </a>
  <a href="https://github.com/nandhu663/Multi-Files-Share/fork">
    <img src="https://img.shields.io/github.com/nandhu663/Multi-Files-Share?label=Fork&style=social">
  </a>  
</p>


<b><i>Telegram Bot To Store Posts And Documents And it Can Access By Special Links./nI Guess This Will Be Usefull For Many People...</i></b> 

##

**If You Need Any More Modes in Repo or If You Find Out Any Bugs, Mention in [codexbotzsupport](https://www.telegram.dog/codexbotzsupport)**

### Features
- Fully customisable.
- Customisable welcome messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.

### Setup

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub 

##
### Installation
#### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/nandhu663/Multi-Files-Share)

#### Deploy in your VPS
````bash
git clone https://github.com/nandhu663/Multi-Files-Share
cd File-Sharing-Bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
````

### Admin Commands

```
/start - start the bot or get posts

/batch - create link for more than one posts

/genlink - create link for one post

```

### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `API_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `START_MESSAGE` Optional: start message of bot, use HTML and <a href='https://github.com/nandhu663/Multi-Files-Share/blob/main/README.md#start_message'>fillings</a>
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub

### Extra Variables

* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption, you can use HTML and <a href='https://github.com/shahsad-klr/File-Sharing-Bot/blob/main/README.md#custom_caption'>fillings</a> for formatting (only for documents)
* `DISABLE_CHANNEL_BUTTON` Put True to Disable Channel Share Button, Default if False

### Fillings
#### START_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption


## Support   
Join Our [Telegram Group](https://www.telegram.dog/tvseriezzz) For Support/Assistance And Our [Channel](https://www.telegram.dog/tvseriezzz_update) For Updates.   
   
Report Bugs, Give Feature Requests There..   

### Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
- Thanks For [All In One](https://www.telegram.dog/tvseriezzz_update) & [Our Group](https://t.me/tvseriezzz) Members.

### Licence
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

[Files-Share-Bot](https://github.com/nandhu663/Multi-Files-Share) is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. 

##

   **Star this Repo if you Liked it ⭐⭐⭐**
