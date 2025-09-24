## Quick Use
choose executable_bin for your operation system

1. replace -api_key & -api_sec
2. choose -size, 200 indicates 200USDT
3. choose -side, trend is bullish use BUY, trend is bearish use SELL

random-trading-aster.exe -symbol BTCUSDT -side BUY -size 200 -step 0.0004 -seconds 30 -price_min 100000 -price_max 120000 -precision_base 3 -precision_quote 1 -api_key "to_replace" -api_sec "to_replace"

random-trading-aster.exe -symbol ASTERUSDT -side BUY -size 100 -step 0.0004 -seconds 30 -price_min 1 -price_max 10 -precision_base 2 -precision_quote 4 -api_key "to_replace" -api_sec "to_replace"

random-trading-aster.exe -symbol ETHUSDT -side BUY -size 100 -step 0.0004 -seconds 30 -price_min 3000 -price_max 5000 -precision_base 3 -precision_quote 1 -api_key "to_replace" -api_sec "to_replace"

## More paramters desc
symbol:  "trading symbol, e.g. ASTERUSDT"
side:    "first market side: BUY or SELL"
size:    "amount in quote asset per market order (e.g. 123.5)"
step:    "price step ratio for limit order (e.g. 0.002)"
seconds: "interval seconds between attempts (min 5)"
price_min:  "min open price"
price_max:  "max open price"
precision_base:  "asset precision (quantity decimals)"
precision_quote: "price precision (price decimals)"
api_key: "API key (or set env API_KEY)"
api_sec: "API secret (or set env API_SEC)"

## Social media:   

x.com/hyperswarmx

t.me/hyperswarm

https://discord.gg/EUqd4yvTYJ

GitHub - hyperswarms/hyperswarm-tools
