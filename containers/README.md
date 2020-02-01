`docker build -t mdf .`

`docker run -p 3978:3978 --restart unless-stopped mdf`

https://github.com/Microsoft/BotFramework-Emulator/issues/356

To test bot in Docker container, you need to go into the App Settings and uncheck "Bypass ngrok for local addresses"

https://github.com/Microsoft/BotFramework-Emulator/wiki/Tunneling-(ngrok)
