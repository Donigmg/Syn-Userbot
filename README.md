

## ──「SYN USERBOT」──

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/xsyn1100/Syn-Userbot)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-green)](https://GitHub.com/xsyn1100/Syn-Userbot/graphs/commit-activity)
[![CodeFactor](https://www.codefactor.io/repository/github/mrismanaziz/Man-Userbot/badge)](https://www.codefactor.io/repository/github/xsyn1100/Syn-Userbot)
[![CodeQuality](https://img.shields.io/codacy/grade/a723cb464d5a4d25be3152b5d71de82d?color=blue&logo=codacy)](https://app.codacy.com/gh/xsyn1100/Syn-Userbot/dashboard)
[![Docker Pulls](https://img.shields.io/docker/pulls/mrismanaziz/man-userbot)](https://hub.docker.com/r/mrismanaziz/man-userbot/tags)
[![GitHub Forks](https://img.shields.io/github/forks/mrismanaziz/Man-Userbot?&logo=github)](https://github.com/xsyn1100/Syn-Userbot/fork)
[![GitHub Stars](https://img.shields.io/github/stars/mrismanaziz/Man-Userbot?&logo=github)](https://github.com/xsyn1100/Syn-Userbot/stargazers)

Syn-Userbot adalah userbot Telegram modular yang berjalan di Python3 dengan database sqlalchemy.

Berbasis [Paperplane](https://github.com/RaphielGang/Telegram-UserBot) dan [ProjectBish](https://github.com/adekmaulana/ProjectBish) userbot.
Saya membuat repository ini untuk memilih dan menambahkan beberapa modul yang saya butuhkan dengan banyak perubahan, fitur dan modul.

## Disclaimer

```
Saya tidak bertanggung jawab atas penyalahgunaan bot ini.
Bot ini dimaksudkan untuk bersenang-senang sekaligus membantu anda
mengelola grup secara efisien dan mengotomatiskan beberapa hal yang membosankan.
Gunakan bot ini dengan risiko Anda sendiri, dan gunakan userbot ini dengan bijak.
```



<details>
<summary><b>🔗 String Session</b></summary>
<br>
    
> Anda memerlukan API_ID & API_HASH untuk menghasilkan sesi telethon. ambil APP ID dan API Hash di my.telegram.org
<h4> Generate Session via Repl: </h4>    
<p><a href="https://repl.it/@mrismanaziz/stringenSession?lite=1&outputonly=1"><img src="https://img.shields.io/badge/Generate%20On%20Repl-blueviolet?style=for-the-badge&logo=appveyor" width="200""/></a></p>
<h4> Generate Session via Telegram StringGen Bot: </h4>    
<p><a href="https://t.me/StringManRobot"><img src="https://img.shields.io/badge/TG%20String%20Gen%20Bot-blueviolet?style=for-the-badge&logo=appveyor" width="200""/></a></p>
    
</details>

<details>
<summary><b>🔗 Deploy di VPS</b></summary>
<br>
    
### REQUIREMENTS PACKAGE !
-  Update & upgrade VPS anda `sudo apt update && upgrade -y`
-  Install Git `sudo apt install git -y`
-  Install Python3 `sudo apt install python3`
-  Install PIP / PIP3 `sudo apt install python3-pip`
-  Install NodeJs 16.X `curl -fsSL https://deb.nodesource.com/setup_16.x | sudo bash -` then do `sudo apt install -y nodejs vim`
-  Install FFMPEG `sudo apt install tree wget2 p7zip-full jq ffmpeg wget git -y`
-  Install Chrome `wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb` lalu ketik `sudo apt install ./google-chrome-stable_current_amd64.deb`

### Tutorial Deploy di VPS

-  `git clone https://github.com/xsyn1100/Syn-Userbot`
-  `cd Man-Userbot`
-  `pip3 install -r requirements.txt`
-  `mv sample_config.env config.env`
-  edit config.env Anda dan isi VARS menggunakan `nano config.env` `CTRL + S ` untuk menyimpan VARS Anda, gunakan `CTRL + X` untuk keluar dan kembali ke direktori Man-Userbot
-  Buka SCRREN di VPS Anda `screen -S Syn-Userbot`
-  Kemudian gunakan perintah ini untuk menyebarkan Man-Userbot `python3 -m userbot`

</details>

# Hosting 🖥

 **Deploying To Heroku / Railway** ⚙

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/xsyn1100/Syn-Userbot)

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2xsyn110p%2Syn-Useebot&envs=API_HASH%2CAPI_ID%2CBOT_TOKEN%2CLOG_GRP%2CMONGO_DB%2CSTRINGSESSION%2CTZ&optionalEnvs=BOT_TOKEN%2CCOMMAND_HANDLER%2CUPSTREAM_REPO&API_HASHDesc=Get+this+value+from+my.telegram.org%21+Please+do+not+steal&API_IDDesc=Get+this+value+from+my.telegram.org%21+Please+do+not+steal&BOT_TOKENDesc=Your+Bot+Token+Obtained+From+%40BotFather.+This+is+Not+Important&COMMAND_HANDLERDesc=Your+Command+Handler.&LOAD_UNOFFICIAL_PLUGINSDesc=Do+You+Wish+To+Load+X-Tra+Plugins%3F&LOG_GRPDesc=A+Group+ID+Where+You+Want+To+Log+Important+Logs.&MONGO_DBDesc=Create+A+Database+In+Mongodb+And+Get+URL.+Make+Sure+To+Enter+Correct+URL%21&STRINGSESSIONDesc=String+Session%2C+Run+string_gen.py+to+get+String+Session.&TZDesc=Your+Time+Zone&LOAD_UNOFFICIAL_PLUGINSDefault=True&TZDefault=Asia%2FKolkata)

## Support 🚑
<a href="https://t.me/synxupdate"><img src="https://img.shields.io/badge/Join-Telegram%20Channel-red.svg?logo=Telegram"></a>
<a href="https://t.me/synxsupport"><img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram"></a>

## Inspiration & Credits
* [TeamUltroid](https://github.com/github.com/Ultroid) : UltroidUserbot
* [Risman](https://github.com/mrismanaziz/Man-Userbot) :  Man-Userbot
* [Doni](https://github.com/xsyn1100/Syn-Userbot) : Syn-Userbot




## License
Licensed under [Raphielscape Public License](https://github.com/mrismanaziz/Man-Userbot/blob/Man-Userbot/LICENSE) - Version 1.d, February 2020
