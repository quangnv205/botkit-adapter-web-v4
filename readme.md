# Support this project
- Star GitHub repository :star:
- Create pull requests, submit bugs or suggest new features
- [Github](https://github.com/quangnv205)

![](https://github.com/quangnv205/botkit-adapter-web-v4)


# Botkit Starter Kit

This is a Botkit starter kit for web, created with the [Yeoman generator](https://github.com/howdyai/botkit/tree/master/packages/generator-botkit#readme).

To complete the configuration of this bot, make sure to update the included `.env` file with your platform tokens and credentials.

[Botkit Docs](https://botkit.ai/docs/v4)

This bot is powered by [a folder full of modules](https://botkit.ai/docs/v4/core.html#organize-your-bot-code). 
Edit the samples, and add your own in the [features/](features/) folder.

# WebAdapter
Connect Botkit or BotBuilder to the Web. It offers both websocket and webhook capabilities. To use this adapter, you will need a compatible chat client - generate one using the Botkit yeoman generator, or use the one included in the project repo here.

To use this class in your application, first install the package:
```
npm install --save botbuilder-adapter-web
```
Then import this and other classes into your code:
```
const { WebAdapter } = require('botbuilder-adapter-web')
```
This class includes the following methods:
```
continueConversation()
createSocketServer()
getConnection()
init()
isConnected()
processActivity()
sendActivities()
```

## Run Server
```
$ npm install
$ npm start
```
# Contribution
Contributions are greatly appreciated. You can contribute by adding `i18n` support with your language, the testing section or any other feature.

# Contributors
[<img alt="Quang Nguyen" src="https://assets.gitlab-static.net/uploads/-/system/user/avatar/1702767/avatar.png?width=160" width="160">](https://gitlab.com/quangnv205)

Quang Nguyen
## License

MIT

