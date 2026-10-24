# brainy-uptime

An outside check of https://brainy.cz/api/ready every ten minutes (`.github/workflows/ready.yml`).
A failed run is the alert: GitHub e-mails the account that last changed the schedule.
`keepalive.yml` keeps the schedule from being switched off after 60 quiet days.
