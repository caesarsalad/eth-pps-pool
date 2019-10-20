# eth-pps-pool
Ethereum mining pool that has PPS reward system and hash charts API
______________________________

## Used in production for one year.
### Only compatible with parity.

To change block reward for PPS reward util.go#71 (for ETH 2, ETC 4)

Use crontab syntax for time intervals of charts at api.json.

You can use screen or tmux to open api, minerproxy and payout modules separately. (at production I do not recommend to open all of them in one screen.)

example:
screen -mS api ./build/bin/open-ethereum-pool api.json

# You can open issue on github for bugs. If you need help send e-mail to huseyin-cakir-2013@yandex.com.
_________________________________

Based on [sammy007/open-ethereum-pool](https://github.com/sammy007/open-ethereum-pool) and PPS reward scheme using [CryptoManiac/open-ethereum-pool-pps](https://github.com/CryptoManiac/open-ethereum-pool-pps)
