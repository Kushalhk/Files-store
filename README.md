# ʜᴋ ғɪʟᴇ ꜱᴛᴏʀᴇ ʙᴏᴛ

<p align="center">
  <img src="https://envs.sh/o3u.jpg" alt="ʜᴋ ғɪʟᴇ ꜱᴛᴏʀᴇ ʙᴏᴛ Logo">
</p>


ᴛᴇʟᴇɢʀᴀᴍ ʙᴏᴛ ᴛᴏ ꜱᴛᴏʀᴇ ᴘᴏꜱᴛꜱ ᴀɴᴅ ᴅᴏᴄᴜᴍᴇɴᴛꜱ ᴀɴᴅ ɪᴛ ᴄᴀɴ ᴀᴄᴄᴇꜱꜱ ʙʏ ꜱᴘᴇᴄɪᴀʟ ʟɪɴᴋꜱ.
I ɢᴜᴇꜱꜱ ᴛʜɪꜱ ᴡɪʟʟ Bᴇ ᴜꜱᴇғᴜʟ ғᴏʀ ᴍᴀɴʏ Pᴇᴏᴘʟᴇ.....

##

**If you need any more modes in repo or If you find out any bugs, mention in [@Harikushal](https://www.telegram.dog/harikusha)**

**Make sure to see [contributing.md](https://github.com/Kushalhk/Files-store) for instructions on contributing to the project!**



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


#### Deploy on Koyeb

The fastest way to deploy the application is to click the **Deploy to Koyeb** button below.


[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/Kushalhk/Files-Store&branch=koyeb&name=hkfilesharingbot)



### Admin Commands

```
/start - start the bot or get posts

/batch - create link for more than one posts

/genlink - create link for one post

/users - view bot statistics

/broadcast - broadcast any messages to bot users

/stats - checking your bot uptime
```

### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `APP_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `DATABASE_URL` Your mongo db url
* `DATABASE_NAME` Your mongo db session name
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `START_MESSAGE` Optional: start message of bot,
* `FORCE_SUB_MESSAGE`Optional:Force sub message of bot, use HTML and Fillings
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub
* `PROTECT_CONTENT` Optional: True if you need to prevent files from forwarding


### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption

#### CUSTOM_STATS

* `{uptime}` - Bot Uptime

### Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
- Our Support Group Members

### Licence
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

[FILE-SHARING-BOT](https://github.com/Kushalhk/Files-Store/) is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. 

##

   **Star this Repo if you Liked it ⭐⭐⭐**
