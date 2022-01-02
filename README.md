
<h1 align="center">
<b> 『# GROUP-MANAGER』🇮🇳 </b>
</h1>

[![# GROUP MANAGER](https://telegra.ph/file2dd82644aa7f19518fe60jpg-01-02)](https://github.com/LEGENDS-OP/LEGENDUSERBOT)

<h6 align="center">
  <b>⚡ LegendBot Is One Of The Fastest & Smoothest Bot On Telegram Based on Telethon⚡</b>
</h6>

<p align="center">
<a href="https://github.com/LEGEND-OS/LEGENDBOT" alt="GitHub closed issues"> <img src="https://img.shields.io/github/issues-closed-raw/LEGEND-OS/LEGENDBOT?style=flat&logo=github&color=success" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDBOT/graphs/contributors" alt="GitHub contributors"> <img src="https://img.shields.io/github/contributors/LEGEND-OS/LEGENDBOT?style=flat&logo=github" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDBOT/network/members" alt="GitHub forks"> <img src="https://img.shields.io/github/forks/LEGEND-OS/LEGENDBOT?label=Forks&logo=github" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDBOT" alt="GitHub closed pull requests"> <img src="https://img.shields.io/github/issues-pr-closed-raw/LEGEND-OS/LEGENDBOT?color=success" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDBOT" alt="GitHub issues"> <img src="https://img.shields.io/github/issues-raw/LEGEND-OS/LEGENDBOT?style=flat&logo=github&color=yellow" /> </a>
</p>
<p align="center">
<a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-1f425f.svg?style=flat&logo=python&color=blue" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDBOT" alt="Docker!"> <img src="https://aleen42.github.io/badges/src/docker.svg" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDBOT" alt="GitHub repo size"> <img src="https://img.shields.io/github/repo-size/LEGEND-OS/LEGENDBOT" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDBOT/blob/master/LICENSE" alt="GPLv3 license"> <img src="https://img.shields.io/badge/License-GPLv3-blue.svg" /> </a>
</p>
<p align="center">
<a href="https://t.me/Legend_Userbot" alt="Telegram!"> <img src="https://aleen42.github.io/badges/src/telegram.svg" /> </a>
<a href="https://github.com/LEGEND-OS/LEGENDBOT/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" /> </a>
<a href="https://makeapullrequest.com" alt="PRs Welcome"> <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" /> </a>
</p>

------
## Status Of Bot 
<p align="left">
    <a href="https://github.com/LEGEND-OS/LEGENDBOT/network/members"><img src="https://img.shields.io/github/forks/LEGEND-OS/LEGENDBOT?label=Forks&logoColor=Black&style=social"></a><p align="left"><a href="https://github.com/LEGEND-OS/LEGENDBOT/stargazers"><img src="https://img.shields.io/github/stars/LEGEND-OS/LEGENDBOT?logoColor=Blue&style=social"></a><p align="left"><a href="https://github.com/LEGEND-OS/LEGENDBOT"></a><p align="left"><a href="https://github.com/LEGEND-OS/LEGENDBOT?"></a>

------
## Telegram 🏪
- [![Telegram Group](https://img.shields.io/badge/Telegram-Group-brightgreen)](https://t.me/Legend_Userbot)
- [![Telegram Channel](https://img.shields.io/badge/Telegram-Channel-brightgreen)](https://t.me/Official_LegendBot)
## Deploy
[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/kjeymax/MR-JOKER_BOT)

[![Deploy To Railway](https://railway.app/button.svg)](https://railway.app)

[![Deploy to Qovery](https://img.shields.io/badge/Deploy-Qovery-6EC0D9.svg)](https://qovery.com)



## Starting the bot

<h3 align = "justify">Once you've setup your database and your configuration (see below) is complete, simply run:</h3>

```

python3 -m mrjoker

```

## Configuration 

<h3 align = "justify">Create a new <u>config.py</u> or rename <u>sample_config.py</u> to <u>config.py</u> file in same dir and import, then extend this class.</h3>

- `TOKEN`                  : Your [bot Token](https://t.me/BotFather), As a string
- `API_ID & API_HASH`      : Get API_ID & API_HASH from my.telegram.org, used for telethon based modules.
- `SQLALCHEMY_DATABASE_URI`: Your database URL
-  `OWNER_ID`              : An integer of consisting of your [owner ID](https://t.memy_id_bot)
-   `OWNER_USERNAME`       : Your username (without the @)
-   `SUPPORT_CHAT`         : Your Telegram support group chat username
-   `EVENT_LOGS`           : Event logs channel to note down important bot level events, recommend to make this public. ex: `-100:123`
-   `JOIN_LOGGER`          : A channel where bot will print who added it to what group, useful during debugging or spam handling.
-   `CASH_API_KEY`         :Required for currency converter. [Get yours from](https://www.alphavantage.co/support/#api-key)
-   `TIME_API_KEY`         : Required for timezone information. [Get yours from](https://timezonedb.com/api)
-   `DEV_USERS`            : ID of users who are Devs of your bot (can use /py etc.). If you are a noob and would come and bother Mr.Joker support then keep the current ID's here at they are and add yours. 
-   `sw_api`               : Spamwatch API Token, Get one from [@SpamWatchBot](https://t.me/SpamWatchBot)
-   `STRICT_GBAN`          : Enforce gbans across new groups as well as old groups. When a gbanned user talks, he will be banned.
-   `DRAGONS`              : A space separated list of user IDs who you want to assign as sudo users
-   `DEMONS`               : A space separated list of user IDs who you wanna assign as support users(gban perms only)
-   `TIGERS`               : A space separated list of user IDs who you wanna assign as tiger users.
-   `WOLVES`               : A space separated list of user IDs who you want to assign as whitelisted - can't be banned with your bot.
-   `ENV`                  : Setting this to ANYTHING will enable environment variables. Leave it as it is
-   `WEBHOOK`              : Setting this to ANYTHING will enable webhooks. If you dont know how this works leave it as it is
-   `PORT`                 : Port to use for your webhooks. Better leave this as it is on heroku
-   `URL`                  : The Heroku App URL :-  `https://<appname>.herokuapp.com`
-   `No_LOAD`              : Dont load these modules cause they shit, space separation
-   `BL_CHATS`             : List of chats you want blacklisted.
-   `ALLOW_EXCL`           : Set this to True if you want ! to be a command prefix along with /. Recommended is True
-   `DEL_CMDS`             : Set this to True if you want to delete command messages from users who don't have the perms to run that command.
-   `AI_API_KEY`           : Make your bot talk using Intellivoid's chatbot API, [Get your key from](https://coffeehouse.intellivoid.net/)
-   `BAN_STICKER`          : ID of the sticker you want to use when banning people
-   `WALL_API`             : Required for wallpaper. [Get your's from](https://wall.alphacoders.com/)  
-   `ARQ_API_URL`          : https://thearq.tech/ 👈 Fill in this way
-   `ARQ_API_KEY`          : Start this boat https://t.me/ARQRobot. Get the key
-   `REM_BG_API_KEY`       : Go to this site https://www.remove.bg/api#remove-background. Get your api key
-    `GENIUS_API_TOKEN`    : Go to this site https://docs.genius.com/. Get your api token
 
 
## Python dependencies

<h3 align = "justify">Install the necessary python dependencies by moving to the project directory and running:</h3>

```
pip3 install -U -r requirements.txt

```


## Database

<h3 align = "justify">If you wish to use a database-dependent module (eg: locks, notes, userinfo, users, filters, welcomes), you'll need to have a database installed on your system. I use postgres, so I recommend using it for optimal compatibility.</br></br>

In the case of postgres, this is how you would set up a the database on a debian/ubuntu system. Other distributions may vary</h3>

- Install postgresql  

```
sudo apt-get update && sudo apt-get install postgresql 

```

- Change to the postgres user 
 
 ```
 sudo su - postgres
 
 ```
 
 - Create a new database user (change YOUR_USER appropriately)
 
 ```
 createuser -P -s -e YOUR_USER
 
 ```
 
This will be followed by you needing to input your password.

- create a new database table:

```

createdb -O YOUR_USER YOUR_DB_NAME

```

Change YOUR_USER and YOUR_DB_NAME appropriately.

- finally:

```

psql YOUR_DB_NAME -h YOUR_HOST YOUR_USER

```

<h3 align = "justify">This will allow you to connect to your database via your terminal. By default, YOUR_HOST should be 0.0.0.0:5432.</br></br>

You should now be able to build your database URI. This will be:</h3>

```
sqldbtype://username:pw@hostname:port/db_name

```

<h3 align = "justify">Replace sqldbtype with whichever db youre using (eg postgres, mysql, sqllite, etc) repeat for your username, password, hostname (localhost?), port (5000), and db name.</h3>

## Support
[![HITECH](https://img.shields.io/badge/LKHITECH-Channel-red?style=for-the-badge&logo=telegram)](https://telegram.dog/lkhitech)</br></br>
[![HITECH](https://img.shields.io/badge/LKHITECH-Group-red?style=for-the-badge&logo=telegram)](https://telegram.dog/hitechlkgroup)</br></br>
[![CONTACT ME](https://img.shields.io/badge/Telegram-Contact%20Me-informational)](https://t.me/kavinduaj)

## Discussions
<p align="left">
<a href="https://github.com/kjeymax/MR-JOKER_BOT/discussions" alt="Mr Joker"> <img src="https://img.shields.io/badge/%F0%9F%A4%A1-Mr%20Joker%20Discussions-9cf" /> </a>

<h3 align = "justify">Don't forget to star this repo if you liked it.</br></br>

enjoy your bot! 💝</h3> 

