# Vaught
Vaught is Vault + Bot

# Getting Started
This is a python based discord bot. You should probably have python installed. I'm currently using 3.12, but as long as it's somewhat recent (has f-string support) it should be okay.

Next go to https://discord.com/developers/applications and create a new application under your own account.

From here, click Bot, then see "reset token". Press reset and save that string into a file named `keys.json` in the same directory as this code with the following format:
```json
{
	"token": "<PASTE TOKEN HERE>"
}
```
so if your token was `123ABC`:
```json
{
	"token": "123ABC"
}
```

Next, on the application dashboard, click the left hand side menu 'Installation' open the provided install link and follow the guide to install it in a server of your choosing.

Now to get python set up, run `pip install -r requirements.txt` to install any requirements added to the bot. Then run `python bot.py` to launch.

Happy coding!
