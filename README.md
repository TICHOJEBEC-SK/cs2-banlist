<h1 align="center">
  CS2 Banlist
</h1>

<p align="center">
<i>Loved the tool? Please consider <a href="https://paypal.com/paypalme/mleaguecz">donating</a>  💸 to help it improve!</i>
</p>

<p align="center">
<a href="https://www.paypal.com/paypalme/mleaguecz"><img src="https://img.shields.io/badge/support-PayPal-blue?logo=PayPal&style=flat-square&label=Donate"/>
</a>

#### Banlist for your website

Simple banlist based on a similar principle as SourceBans.

## 🚀 Demo

Try the tool: [demo v1.0.0](http://mtgaming.eu/)

## 💡 Contact
**If you are interested, contact me on discord.**

Discord: TICHOJEBEC
## 💎 Features (PREMIUM)

Coming soon.

## 🧐 Features (FREE)

<a href="https://i.ibb.co/NKZ9nb7/image.png"><img src="https://i.ibb.co/NKZ9nb7/image.png" alt="image" border="0"></a>

**Banlist**
- List of bans based on nickname, SteamID, admin who issued the ban, reason for the ban, ban date, ban expiration, and the status indicating whether the ban is active.

**Mutelist**
- In progress...

**Adminlist**
- List of admins based on nickname, SteamID, date when they became an admin, the number of bans issued by the admin, and the status indicating whether the admin is active.

**Unban system**
- Option to submit an unban request. The request is automatically sent via Discord webhook as an embedded message. Requests are stored in the database based on the IP address. The option to submit an unban request is limited to once per hour.

**Report system**
- Player/bugs reporting feature. The request is automatically sent via Discord webhook as an embedded message. Reports are stored in the database based on the IP address. The option to submit a report is limited to once every 5 minutes.

**Admin system**
- Possibility to create and delete server admins.
- Possibility to create and delete server bans.

**Server admin commands**
```
css_admin - Opens the admin menu
css_slay "userid", !slay "userid" - allows you to kill a player
css_kick "userid", !kick "userid" - allows you to kick a player from the server
css_map "name_map", !map "name_map" - allows you to change the map on the server
css_ban "userid" "time_minutes or 0 - permanently" "reason",
!ban "userid" "time_minutes or 0 - permanently" "reason" - Bans a player
css_unban "steamid" "reason", !unban "steamid" "reason" - unbans the player
(example SteamId: STEAM_0:1:123456)
```


## 🛠️ Installation Steps

**Required for functionality MiniAdmin plugin by [Partiusfabaa](https://github.com/partiusfabaa)**
- [Metamod](https://www.metamodsource.net/downloads.php/?branch=master) 
- [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp) 

**Required for functionality Banlist website system**
- MySQL
- PHP 7.3+
- Modified version of MiniAdmin, which is located in this repository.

**Version Banlist v1.0.0 is functional only with the modified MiniAdmin plugin by [Partiusfabaa](https://github.com/partiusfabaa), which can be found in the repository. No other version is compatible with the Banlist system.**
- Upload Banlist to your website and install it. www.yourweb.com/install.php
- Upload the MiniAdmin plugin to your cs2 server and restart it.
- Now, a file named database.json has been created in the ../plugins/MiniAdmin/ directory.
- Edit the database.json file and enter the same MySQL connect details as during the website installation.
- Restart the server.
```
database.json
{
  "Connection": {
    "Host": 	"HOST",
    "Database": "NAME_DATABASE",
    "User": 	"NAME_USER",
    "Password": "PASSWORD"
  }
}

maps.txt
You just put the name of your maps here.
```

## 🙇 Special Thanks
- [Partiusfabaa](https://github.com/partiusfabaa) for amazing [cs2-miniadmin](https://github.com/partiusfabaa/cs2-MiniAdmin)
- [HTML Codex](https://htmlcodex.com) for [template](https://htmlcodex.com) 

## 🙇 Sponsors
- Be the first to support this project!

## 🙏 Support
<p align="left">
<a href="https://paypal.com/paypalme/mleaguecz"><img src="https://ionicabizau.github.io/badges/paypal.svg">
</a>
</p>

<hr>
<p align="center">
Developed with ❤️ in Slovakia
</p>
