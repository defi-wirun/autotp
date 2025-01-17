# AutoTP

AutoTP aims to be an automated trading platform that supports multiple exchanges. Inspired by MetaTrader and [MQL4](https://docs.mql4.com/).

## Usage

1. Craft your trading robot inside `robot/`
2. Compile it with `go build -o autotp robot/binance/spot/grid/main.go`
3. Copy `config.yml.example` to `config.yml`, configure your preferred parameters
4. Run `./autotp -c config.yml`, or `./monit` for infinite running until the world ends

### (Work-in-Progress) Supported Exchanges

- [Binance](https://github.com/binance/binance-spot-api-docs)
- [FTX](https://docs.ftx.us/)
- [Bitkub](https://github.com/bitkub/bitkub-official-api-docs)
- [Satang Pro](https://docs.satangcorp.com/)

Read-only exchange,

- [SET: The Stock Exchange of Thailand](https://marketdata.set.or.th/mkt/marketsummary.do?language=en&country=US)
