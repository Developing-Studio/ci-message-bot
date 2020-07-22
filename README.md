[toc]

# Custom Helper Bot

## General Info

This is a general custom made bot.

Features are:

1. Sending messages in channels and being able to edit them with commands. (pending)
2. Sending announcements. (pending)



## Installation 

1. Clone this repo
2. Make sure you have the latest version of python
3. Creating a discord application and a bot user at the [discord dev website](https://discord.com/developers/applications)
4. [Setting up config](#config)
5. Running `main.py` 
6. Inviting the bot to your server, there will be an invite link in the python shell after you run it. 



## Config

1. Create a python environment

2. Install the required packages with `pip -r requirments.txt`

3. This bot uses [dotenv](https://pypi.org/project/python-dotenv/) for environment variables. 
4. Rename `.example_env` to `.env`
5. At `DISCORD_TOKEN=bot_token` replace bot_token with the bot's token. 