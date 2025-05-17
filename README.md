# Installation 

#1 - Download the latest release or source code.

#2 - Edit the **bot.py** file to match your token.
(I am running this on my local machine so I'm not using env but you can use your operating system's getenv if needed. Replit = os.getenv('TOKEN') Windows = Echoing the env, etc.)

#3 - Install **discord.py**
open windows run and type cmd or type it in startup. Once you have opened your command prompt paste the following:
``` bash
pip install discord.py
```
That will install the latest version of discord.py onto your machine.

#4 - Running the bot
while you are in command prompt, press Ctrl + c to return to command and then paste:
``` bash
python bot.py
```

# Congrats! You now have a fully working discord bot.
Make sure you have all intents enabled under bot and inviting your bot to your server.
You can find a tutorial on inviting your bot here:
https://www.youtube.com/watch?v=SRV_4C9aEqM

*I recommend enabling Administrator permissions but you may grant whatever permissions suit your server best*
