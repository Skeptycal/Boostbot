# Boostbot
A bot for [Boostnote](https://github.com/BoostIO/Boostnote).

## Launching
You have to obtain a webhook secret key from [here](https://github.com/BoostIO/Boostnote/settings/hooks) and the access token of the bot account beforehand.

```
$ (WEBHOOK_SECRET=<the_key> GITHUB_ACCESS_TOKEN=<the_token> node server.js >> logfile.log) &
```
