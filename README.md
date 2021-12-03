

[![Stars](https://img.shields.io/github/stars/EvamariaTG/EvaMaria?style=flat-square&color=yellow)](https://github.com/EvamariaTG/EvaMaria/stargazers)
[![Forks](https://img.shields.io/github/forks/EvamariaTG/EvaMaria?style=flat-square&color=orange)](https://github.com/EvamariaTG/EvaMaria/fork)
[![Size](https://img.shields.io/github/repo-size/EvamariaTG/EvaMaria?style=flat-square&color=green)](https://github.com/EvamariaTG/EvaMaria/)   
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/EvamariaTG/EvaMaria)   
[![Contributors](https://img.shields.io/github/contributors/EvamariaTG/EvaMaria?style=flat-square&color=green)](https://github.com/EvamariaTG/EvaMaria/graphs/contributors)
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/EvamariaTG/EvaMaria/blob/main/LICENSE)
[![Sparkline](https://stars.medv.io/EvamariaTG/EvaMaria.svg)](https://stars.medv.io/EvamariaTG/EvaMaria)

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* Check [info.py](https://github.com/EvamariaTG/evamaria/blob/master/info.py) for more

#Deploy to Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FARJUN-PRADEEP-123%2FTESTING-ONLY-1&plugins=mongodb&envs=ADMINS%2CAPI_HASH%2CAPI_ID%2CAUTH_CHANNEL%2CAUTH_USERS%2CBOT_TOKEN%2CCACHE_TIME%2CCHANNELS%2CCOLLECTION_NAME%2CCUSTOM_FILE_CAPTION%2CDATABASE_NAME%2CDATABASE_URI%2CIMDB%2CLOG_CHANNEL%2CP_TTI_SHOW_OFF%2CPICS%2CSINGLE_BUTTON%2CSUPPORT_CHAT%2CUSE_CAPTION_FILTER&ADMINSDesc=Username+or+ID+of+Admin.+Separate+multiple+Admins+by+space.&API_HASHDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&API_IDDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&AUTH_CHANNELDesc=ID+of+channel.Make+sure+bot+is+admin+in+this+channel.+Without+subscribing+this+channel+users+cannot+use+bot.&AUTH_USERSDesc=Username+or+ID+of+users+to+give+access+of+inline+search.+Separate+multiple+users+by+space.+Leave+it+empty+if+you+don%27t+want+to+restrict+bot+usage.&BOT_TOKENDesc=Your+bot+token.&CACHE_TIMEDesc=The+maximum+amount+of+time+in+seconds+that+the+result+of+the+inline+query+may+be+cached+on+the+server&CHANNELSDesc=Username+or+ID+of+channel+or+group.+Separate+multiple+IDs+by+space.&COLLECTION_NAMEDesc=Name+of+the+collections.+Defaults+to+Telegram_files.+If+you+are+using+the+same+database%2C+then+use+different+collection+name+for+each+bot&CUSTOM_FILE_CAPTIONDesc=A+custom+file+caption+for+your+files.+formatable+with+%2C+file_name%2C+file_caption%2C+file_size%2C+Read+Readme.md+for+better+understanding.&DATABASE_NAMEDesc=Name+of+the+database+in+mongoDB.&DATABASE_URIDesc=mongoDB+URI&IMDBDesc=Imdb%2C+the+view+of+information+when+making+True%2FFalse&LOG_CHANNELDesc=Bot+Logs%2CGive+a+channel+id+with+-100xxxxxxx&P_TTI_SHOW_OFFDesc=Customize+Result+Buttons+to+Callback+or+Url+by+%28True+%3D+url+%2F+False+%3D+callback%29&PICSDesc=Add+some+telegraph+link+of+pictures+.&SINGLE_BUTTONDesc=choose+b%2Fw+single+or+double+buttons+https%3A%2F%2Fgithub.com%2FEvamariaTG%2FEvaMaria%2Fissues%2F22&SUPPORT_CHATDesc=Username+of+a+Support+Group+%2F+ADMIN.+%28+Should+be+username+without+%40+and+not+ID%29&USE_CAPTION_FILTERDesc=Whether+bot+should+use+captions+to+improve+search+results.+%28True+False%29&CACHE_TIMEDefault=300&referralCode=ENQaJY)

## Deploy

<details><summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/ARJUN-PRADEEP-123/TESTING-ONLY-1.git">
  <img src="https://telegra.ph/file/8005b3498755b538efa3c.jpg" alt="Deploy">
</a>
</p>
</details>

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/EvamariaTG/evamaria
# Install Packages
pip3 install -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>


