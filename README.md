# README #

Date: 08/07/2017


### What is this repository for? ###

* Telegram Bot
* Version: 1.0.0
* name: [Bot]Ti
* Code based from {S}bot version 0.54.0

### How do I get set up? ###

* Mysql + Php + JQuery + Html with Linux or Windows

### Virtual disk with VmWare Player ###

* Use the vmware player and the virtual disk. Downalod from: www.botti.guion78.com the virtual machine for run [Bot]Ti in 5 minutes

### Contribution guidelines ###

* Writing tests: Community

### Browsers certificate ###

* Browser: Internet Explorer 8+ , Firefox, WaterFox, Chrome, Safari

### Who do I talk to? ###

* www.botti.guion78.com
* Assistance: botti@guion78.com
* 
* Code and conceive:
* Guion Matteo (www.guion78.com)


### How to install? ###

* Linux install:
* Create one Bot, use this guide: https://core.telegram.org/bots#botfather and generate the Token:
* The token is a string along the lines of 110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALD saw that will be required to authorize the bot and send requests to the Bot API
* Use the server Linux with Lamp (Php version 5.5 or higher with support for curl and mcrypt (apt-get install php5-mcrypt, apt-get install php5-curl and /etc/init.d/apache2 restart), mysql 5.5 or higher and apache)
* Insert in config.sample.php the Token, user and pwd user mysql and define the path of INFO_PHOTO e SEND_PHOTO
* If this is your first install rename config.sample.php to config.php
* For ability mcrypt at php launch in the bash: "php5enmod mcrypt" and restart Apache or Server. This is very important for login in Sbot management.
* Use telegram_base.sql in folder sql and install in your server Mysql (launch in DB telegram the instruction sql).
* In /etc/rc.local your server Linux insert (in two row):
* "php /var/www/_PATH_OF_FOLDER_BOT/demone.php > /var/www/_PATH_OF_FOLDER_BOT/botAdmin/log/bot.log & 
* exit 0"
* Delete the " " before inserting the file
* "EXIT 0" -> for force the exit
* If you want the send images to work directory upload_img must be writable (set to 777)
* reboot Server linux.
* Ok, the bot is run and you to be working. User login: admin Password login: password

* Windows install:
* For install with Windows use the guide for Linux Server, but not configure rc.local. Configure Scheduled Tasks in Windows panel.


### Changelog ###

### 09/07/2017###
* Version 1.0.0 initial based from {S}Bot 0.54.0