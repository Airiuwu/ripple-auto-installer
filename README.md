# Note
This Installer just install most things for a ripple server! If you want to use a custom modification, You need to edit it yourself. and please fork this project if you use it! (THIS IS NOT DESIGNED FOR WINDOWS!)

# What the heck is it?
It's my Ripple auto installer because I'm lazy to write very very looooooong command to setup it. So I decided to make my own installer!

# How to use it?
It's simple. Firstly, you need to download it by either downloading it from GitHub, or running this command to download: `wget https://raw.githubusercontent.com/Airiuwu/ripple-auto-installer/master/installer.sh`

After you do this, copy, paste and run the command: `chmod +x installer.sh && ./installer.sh`, and it will take you into the install process!

Make sure you set your DNS like this:

* YOUR-DOMAIN
* c.YOUR-DOMAIN
* a.YOUR-DOMAIN
* old.YOUR-DOMAIN
* osu.YOUR-DOMAIN

Make sure you have a MySQL user already created before hand

* `mysql`
* `CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';`
* `GRANT ALL PRIVILEGES ON * . * TO 'username'@'localhost';`
* `FLUSH PRIVILEGES;`

# I need help!
You ask for help via Github Issues.<br>
<br>

# Credits
* <a href=https://github.com/ppy>peppy</a> - Thank you for the wonderful game and I'm sorry for your bancho.
* <a href=https://github.com/osuripple>Ripple</a> - Maybe you're not too happy about this... I'm sorry.
* <a href=https://github.com/osufx>osu!fx</a> - Thanks for the secret module!
* <a href=https://github.com/osuthailand>osu!Ainu</a> - Thanks to Ainu for the support!! <3
* <a href=https://github.com/osukawata>osu!Kawata</a> - <a href=https://github.com/r33int>@r33int</a> You're the best! TYSM for helping out <3
* <a href=https://github.com/osuYozora>osu!Yozora</a> - wow man <a href=https://github.com/osuYozora>@osuYozora</a> Thanks for the past!
* <a href=https://github.com/EmilySunpy>Sunpy</a> - You know her! Thanks for most commands and dependencies!
* <a href=https://github.com/osuthailand>osu!Ainu</a> - Thanks Ainu and Aoba for this~

# License
This project is licensed under the GNU AGPL 3 License.
See the "LICENSE" file for more information.
