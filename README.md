# Telegram Music Downloader
A Simple Music Downloader Bot For Telegram with Youtube Music, Spotify & Deezer Support.


## Demo

[You Need Music?](https://t.me/JuniTubeBot)


## Deployment

To deploy this project run

### Easy Way (Local)
```bash
  cp sample_config.env config.env
  pip3 install -r requirements.txt
  python3 -m mbot
```

### Docker
```bash
  cp sample_config.env config.env
  docker build . -t musicbot
  docker run musicbot
```
### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/junioralive/JuniTube)

## Environment Variables

To run this project, you will need to add the following environment variables to your config.env file

`API_ID`
`API_HASH`
`BOT_TOKEN`
`SPOTIPY_CLIENT_ID`
`SPOTIPY_CLIENT_SECRET`
`UPDATES_CHANNEL`
`LOG_GROUP`
`DATABASE_URL`
`AUTH_CHATS`




