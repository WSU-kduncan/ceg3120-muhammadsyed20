Setup
	Open the Discord Developer Portal, Select your desired application, on the right hand side select the 
	Bot option, Once done you can either just copy the token from there or click 'Click to Reveal Token',
	Which will reveal to you your token.
	
	Once you have copied your token, open your local repo and make a .env file and make a variable named
	discord token and paste your token their. Once you have done that go back and download the dotenv with 
	pip. Then in your bot.py file make sure to add the from dotenv import load_dotenv command that will see 
	all the variables inside your .env folder.

	To make the bot work y=ou will need to download discord.py, and python-dotenv. 


Usage
	So when the bot is up and running and online, if you type  in 'towel!' it will provide a quote from 
	brooklyn99 or a hitchhiker quote, If you type in 'thank you' then the bot will give you a quote from the 
	office.
