# lightNovelWatcher
Discord bot that watches for new chapters on reddit

To use:

1. create discord app with https://discordapp.com/developers/applications/me
2. create bot account for app in app page
3 . authorize bot for the server with: https://discordapp.com/oauth2/authorize?client_id=XXXXXXXXXXXX&scope=bot
	- client_id is the app_id from step 1
4. export bot token from step 2 with

```bash
$export LN_BOT_TOKEN="<TOKEN GOES HERE>"
```

5. verify you have the bot token with:

```bash
$env | grep ".*TOKEN"
LN_BOT_TOKE=<TOKEN>
```

6. run the app

```bash
$./botProgram.py
```
