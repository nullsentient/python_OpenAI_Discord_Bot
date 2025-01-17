

**python_OpenAI_Discord_Bot v 1.1**

**By esper2142 on 2/13/23**



A general purpose Discord bot for use with an OpenAI API token and a Discord bot token written completely from scratch in Python. Edit commands and events as you see fit.


**1)** Create a Discord bot and add it to your server with the appropriate permissions. More information here: https://discordpy.readthedocs.io/en/stable/discord.html

**2)** Create an OpenAI account and create an API key: https://platform.openai.com/account/api-keys . Please note this is NOT free.

**3)** Rename `.env.example` to `.env` and paste your created tokens into the appropriate variables.

**4)** Run `pip install -r requirements.txt` to install the script's dependencies.

**5)** Find the channel ID you'd like to post messages in your discord server, and place it in DISCORD_BOT_TOKEN in the .env file . More information on how to find your channel ID here: https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-

**6)** Upload your images for the script into a folder and put the full path in DISCORD_IMAGE_PATH in the .env file

**7)** Host your script somewhere and run it. Suggestions are: your own PC/NAS/Raspberry Pi, or a cloud online service like pythonanywhere or Amazon EC2.
