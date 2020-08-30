# bounty-targets-alert

It's an watcher for new scopes added to **[bounty-targets-data](https://github.com/arkadiyt/bounty-targets-data)** and send you alert to Slack.

![bounty-targets-alert](https://user-images.githubusercontent.com/25837540/91665191-098cf380-eb1e-11ea-916e-53675edb3987.png)

## Dependencies

### Pre-requisites

- curl _([libcurl](https://curl.haxx.se/libcurl/))_
- [go1.13+](https://golang.org/dl/)

### Requirements

- [jq](https://stedolan.github.io/jq/download/)
- [anew](https://github.com/tomnomnom/anew)
- [slackcat](https://github.com/dwisiswant0/slackcat)


## Usage

Based on [this](https://github.com/arkadiyt/bounty-targets-data#status), I recommend you to run this every hour in a cronjob.

```bash
▶ crontab -e
0 * * * * /path/to/bounty-targets-alert/main https://hooks.slack.com/services/xxx/xxx/xxx
```

## Contact

[![Twitter Follow](https://img.shields.io/twitter/follow/dwisiswant0.svg?style=social)](https://twitter.com/dwisiswant0)

Follow me at Twitter, DMs are always open.