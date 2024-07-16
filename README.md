# ⤥ pumpcheck

## Get Crypto Announcements on Your Discord Server

**pumpcheck** sends a Discord webhook of the price any coin from the [CoinGecko](https://www.coingecko.com/en/api) API.

## Running

### View the Help Menu
- `./pumpcheck -h`

### Typical Command
- `./pumpcheck -w <discord-webhook-url> -a <avatar-png-url> -t <ticker>`

### Connect to Webhook and Show Bitcoin's Price
- `./pumpcheck -w <discord-webhook-url> -a <avatar-png-url> -t bitcoin`

### Connect to Webhook and Show Ethereum's Price
- `./pumpcheck -w <discord-webhook-url> -a <avatar-png-url> -t ethereum`

*all coins that are listed on coingecko are able to be viewed, be sure to use the coin's ticker.*

