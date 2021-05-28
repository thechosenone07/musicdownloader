# Music downloader bot

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

Still under development Please Report issues to improve this repo.I will try to fix bugs in next update

Music downloader bot is a telegram bot that can send you high-quality audio 🎧🎧🎧

## Features

- All jio saavn Song,Album and Playlist links are supported
- Meta data such as Album Art, artist details are present
- Lyrics are also embeded into the meta data (if available)

## Deployment

### Please read all the deployment instructions before deploying the bot

This project entirely depends on [Sumanjay's](https://github.com/cyberboysumanjay)
[Unofficial jiosaavn api](https://github.com/cyberboysumanjay/JioSaavnAPI).

So if You need to deply this preoject you first have to deply your own JioSaavnAPI

You Can Deploy your API on heroku or your VPS

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/anishgowda21/JioSaavnAPI/tree/master)

- After deploying the api note the API URL

- Go to [BotFather](https://telegram.dog/BotFather)

- Create a bot and get your API token

- Deploy the bot here

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/anishgowda21/Music-downloader-bot)

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`Telegram bot API token`

`Url of your JioSaavn API`

`The name of the heroku app where you are deploying your bot`

## Roadmap

- Add song search by name

- Add spotify and deezer support

### You can find the working example [here](https://telegram.dog/jiomusic_dlbot)

## Special Thanks to

- [cyberboysumanjay](https://github.com/cyberboysumanjay) for his awesome API