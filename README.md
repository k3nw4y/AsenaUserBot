<div align = "center">
  <img src = "https://i.imgyukle.com/2020/05/29/yBpJsP.jpg" width = "200" height = "200">
  <h1> Asena UserBot </h1>
</div>
<p align = "center">
    Asena UserBot is a bot that makes it easy to use Telegram. It is completely open source and free.
    <br>
        <a href="https://github.com/quiec/AsenaUserBot/blob/master/README.md#installation"> Installation </a> |
        <a href="https://github.com/Quiec/AsenaUserBot/wiki/G%C3%BCncelleme"> Update </a> |
        <a href="https://t.me/AsenaUserBot"> Telegram Channel </a>
    <br>
</p>

----
![Docker Pulls](https://img.shields.io/docker/pulls/fusuf/asenauserbot?style=flat-square)! [Docker Image Size (latest by date)](https: //img.shields. io / docker / image-size / fusuf / asenauserbot? style = flat-square)
## Setup
### Very Simple Method
[Youtube Videos](https://www.youtube.com/watch?v=mUUQ53TYqI0) ![YouTube Video Views](https://img.shields.io/youtube/views/mUUQ53TYqI0?style=flat-square)

** Android: ** Open Termuxu and paste this code: `bash <(curl -L https://kutt.it/88I5KA) '

** iOS: ** Open iSH and paste this code: `apk update && apk add bash && apk add curl && curl -L -o asena_installer.sh https://t.ly/vATX && chmod + x asena_installer.sh && bash asena_installer.sh`

**Windows 10:** [Python](https://www.microsoft.com/en-us/p/python-38/9mssztt1n39l#activetab=pivot:overviewtab) then PowerShell paste this code: `Invoke-Expression (New-Object System.Net.WebClient) .DownloadString ('https://kutt.it/aYTzCx') '

### Simple Method
If you have no idea how to install the bot, read here: [Installation Guide](https://github.com/Quiec/AsenaUserBot/wiki/Setup/)

[![Deploy] (https://www.herokucdn.com/deploy/button.svg)] (https://heroku.com/deploy?template=https://github.com/Quiec/AsenaUserBot)
### Hard Method
``` python
git clone https://github.com/Quiec/AsenaUserBot.git
cd AsenaUserBot
pip install -r requirements.txt
# Create and edit config.env. #
python3 main.py
```

## Sample Plugin
```python
from userbot.events import register
from userbot.cmdhelp import CmdHelp # <- Add this.

@register (outgoing = True, pattern = "^. test")
async def trial (event):
    await event.edit ('Really don't try!')

Help = CmdHelp ('test') # We say we will add information.
Help.add_command ('try', # Command
    Type None, # if there is a command parameter type, otherwise type None
    'He's really testing!', # Command description
    'trial' # Example usage.
    )
Help.add_info ('Made by @ Fusuf.') # You can add information.
# Or warning -> Help.add_warning ('DO NOT USE!')
Help.add () # And Let's Add.
```

## Information
If you have any requests & complaints & suggestions, you can reach the [support group](https://t.me/AsenaSupport).

```
    Due to Userbot; Your Telegram account may be banned.
    This is an open source project, you are responsible for everything you do. Absolutely, Asena executives do not accept responsibility.
    By establishing the Asena, you are deemed to have accepted these responsibilities.
```

## Credit
Thanks for;

[Seden UserBot](https://github.com/TeamDerUntergang/Telegram-UserBot)

[Userge](https://github.com/UsergeTeam/Userge)

[Spechide](https://github.com/Spechide)
