#[Zuru OS](https://zuru.ml)
Opensource Server-side API with unlimited Cloud Storage. WebDav included!

> **Note:**  this software in public beta. If you see any problems or bugs - [create new issue](https://github.com/ZuruTeam/Zuru/issues/new).

##License <a name="license"></a>
All source code realised under [GNU GPL v.2](https://github.com/ZuruTeam/Zuru/blob/master/LICENSE).

##Installation <a name="installation"></a>
1. Read our [License](#license).
2. Copy [git](https://github.com/ZuruTeam/Zuru/archive/master.zip) from the [master branch](https://github.com/ZuruTeam/Zuru/tree/master) to your server. Don't forget to unzip :package:
3. Open your browser, go to [installer.zuru.ml](https://installer.zuru.ml) and proceed simple user registration. Thats everything you need to do!

:wrench: If you don't want to show us your private server, then follow this steps: // Бородатые админы, это для Вас

1. Create new user folder in /zuru/users/
2. Create new "configurations" folder in the new user directory
3. Put new ini-file "users" to configurations folder from previous step
4. Update created ini-file to the specific content:
```javascript
{
	"login":"YOUR LOGIN (ONLY ENGLISH)",
	"email":"YOUR EMAIL",
	"password":"MD5 HASH YOUR PASSWORD",
	"name":"YOUR NAME (ANY SYMBOLS)",
	"surname":"YOUR SURNAME (ANY SYMBOLS)",
	"gender":"male OR female",
	"birdth":{
		"day":BIRTH DAY,
		"month":BIRTH MONTH,
		"year":BIRTH YEAR
	},
	"phones":{
		"mobile":"YOUR MOBILE PHONE"
	},
	"profile_activation":CURRENT TIMESTAMP
}
```
Open your browser, go to your server and enjoy!

> **Tip:** If you want to hide your private server, you can use [Hamachi](https://secure.logmein.com/RU/products/hamachi/download.aspx). It's really useful in such cases.

## Manual update
1. Read our [License](#license).
2. Create backup!
3. Have you created backup? Create backup! Seriously. :triumph:
4. Go to /zuru/ and delete "mods" directory.
5. Go to /zuru/users/common/configs/ and delete "mimetypes.ini"
6. Clear errors.log
7. Move with the replacement all [latest stable git files](https://github.com/ZuruTeam/Zuru/archive/master.zip) from the [master branch](https://github.com/ZuruTeam/Zuru/tree/master).

The end :smile:

##API & Documentation
All documentation you can find at [dev.zuru.ml](http://dev.zuru.ml). Only Russian :ru:

##Requirements
###Minimal
- :elephant: PHP 5.2
- 0777 root-privileges (read/write/delete/move/copy)
- 64MB on the server drive
- FTP
- mod_rewrite.c
- json_decode/json_encode
- call_user_func
- CURL
- GET, POST, PUT requests

###Recommended
- :elephant: PHP 5.3-5.4
- From 2GB on the server drive and higher
- HTTPS support
- mod_setenvif.c
- mod_deflate.c
- mod_gzip.c
- mod_charset.c
- php_value & php_flag modification
- CURL without any limits
- Unlimited hosting traffic
- All WebDav requests + INSTALL

##Languages
All API decriptions only in English.

:exclamation: От автора: Я ищу свободных переводчиков. Если у Вас есть время и Вы готовы бесплатно мне помочь в переводе GUI с русского на другие языки, [напишите мне](#ileonidze).

##Donation
You can support us! Tweet or post about our project, thats all we need.

In the future you will be able to buy a premium donuts :doughnut:

##Links
[Website](https://zuru.ml), [VK](https://vk.com/zuru_official), [Facebook](https://www.facebook.com/zuru.ml), [Twitter](https://twitter.com/ZuruTeam)

##Project Map
[zuru.ml](https://zuru.ml) - main project website

[home.zuru.ml](https://home.zuru.ml) - GUI

[dev.zuru.ml](https://dev.zuru.ml) - dev documentation

[installer.zuru.ml](https://installer.zuru.ml) - simple server registration

[julia.zuru.ml](https://julia.zuru.ml) - voice assistance website

##Staff

**@author: Леонид Федотов** / iLeonidze - <me@ileonidze.tk> - [Website](https://ileonidze.tk) - [VK](https://vk.com/ileonidze) - [Facebook](https://www.facebook.com/ileonidze) <a name="ileonidze"></a>

**@pr: Анастасия Воробьёва** / NSTDanci - [VK](https://vk.com/nstdanci) <a name="nstdanci"></a>

####Special thanks to:
[Иван Балашов](https://vk.com/ivanparadox), [Никита Бурдин](https://vk.com/burdinn), [Роман Штыров](https://vk.com/id64479862), [Nc_Soft](mailto:intaspace@gmail.com), [DevMan](https://toster.ru/user/DevMan), [Сергей Наломенко](http://nalomenko.com/)

and any other people from Toster and StackOverflow who helped and supported me and this project.

## Changelog
- First init, currently nothing here
