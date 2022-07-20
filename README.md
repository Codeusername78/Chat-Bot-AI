# Chat-Bot-AI-Own-
Welcome to this guide and follow the instructions to prepare a working Smart AI Discord bot!

First Step-:

1) Go to https://discord.com/developers/applications and create a new application (button is on top right).
<img width="500" alt="image" src="https://user-images.githubusercontent.com/76993080/171371472-1d37b4fa-3891-4a9b-8146-79095ac9db7c.png">
2) Enter the name of the bot and click Create.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/76993080/171372230-12237221-1b8a-48d3-8234-6329befab00d.png">
3) Go to the Bot Section and click add a bot.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/76993080/171372601-6e2d5210-bf8f-4764-b978-ace8e5a5f446.png">
4) Scroll Down and enable all privileged gateway intents.
<img width="500" alt="image" src="https://user-images.githubusercontent.com/76993080/171373262-188510a2-30c3-4af6-89b9-0422fb1b6c7d.png">
5) Now go to OAuth2 < URL Generator, In Scopes select bot

6) After selecting bot, you should be able to add in in your server.

***Running bot on VS Code***

Copy the code provided, and paste it in your file.
install discord.py using ``` pip install discord.py ``` on command prompt.

*Copy your bot's token in the bot sectiong of the developer portal.*

In line 32, replace "Your Bot Token" with the copied token.

We would be requiring two api keys ,
One for Random Stuff Api developed by Mr. PGamerX
and One for Rapid Api.

Go to https://api-info.pgamerx.com/
<img width="500" alt="Screenshot 2022-07-20 200425" src="https://user-images.githubusercontent.com/76993080/180009173-74b82dc8-23a1-49cd-a4e1-fef883bb89b9.png">

Create an account and go to Manage Key.

Generate a new api key.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/76993080/180009692-687a280c-95df-44d6-a3cc-0ffef332b53d.png">

*At line 8, replace  API_KEY with your copied API Key*

***RAPID API KEY***

Visit this site https://rapidapi.com/pgamerxdev/api/random-stuff-api/ 

Register an account at Rapid Api.

You will be able to find your key here.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/76993080/180011218-c737fc72-4638-4510-93b6-f8e5bdeca1aa.png">

At line 8, replace "Your Rapid Api Key" with your RAPID API Key.

After applying these changes,

*Run the bot and the bot should be running!*


<img width="500" alt="image" src="https://user-images.githubusercontent.com/76993080/180012327-e14092b6-50ac-4ca4-b364-92fadae44ed0.png">










