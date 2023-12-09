## BIN Checker Bot
## Env

- `API_TOKEN` Bot token.
- `START_MSG` Custom start message.

## Deploy

### Heroku
[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/EscaliBud/BinChecker)

### Railway
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2EscaliBud%2FBinChecker&envs=API_TOKEN%2CSTART_MSG&API_TOKENDesc=Your+bot+token.&START_MSGDesc=Your+custom+start+message.&referralCode=AsunaRobot)

### 000webhost
[![Deploy on 000webhost](https://github.com/CyberID-Ltd/zYxDevs-Profile-Requirements/blob/main/000webhost-logo.svg)](https://www.000webhost.com)

##
```
✔ Tested on Heroku
✔ Tested on 000webhost
⚠ Warn: Still not Tested on Railway!
```

**Setup Webhook**<br>
Copy this, replace `<Bot Token>` and `<your app name>` with your own value then open on your browser.

If Heroku:
`https://api.telegram.org/bot<Bot Token>/setWebhook?url=https://<your app name>.herokuapp.com/bot.php`

Other:
`https://api.telegram.org/bot<Bot Token>/setWebhook?url=https://<your hosted url>/bot.php`

## Command

`!bin <Your-xxxxxx-Bin>`

