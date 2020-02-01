## Echo Bot Container

Container image based on [Node.js Docker official image](https://hub.docker.com/_/node/) with Echo Bot from [Bot Framework SDK for JavaScript](https://docs.microsoft.com/es-es/azure/bot-service/javascript/bot-builder-javascript-quickstart?view=azure-bot-service-4.0).

#### How to use this image

`docker build -t mdf .`

`docker run -p 3978:3978 mdf`

To test bot in Docker container, you need to go into the App Settings and uncheck "Bypass ngrok for local addresses"

https://github.com/Microsoft/BotFramework-Emulator/issues/356

https://github.com/Microsoft/BotFramework-Emulator/wiki/Tunneling-(ngrok)
