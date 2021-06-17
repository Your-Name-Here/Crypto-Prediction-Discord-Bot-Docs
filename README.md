# Crypto Prediction Discord Bot Docs
## _You'd better be right..._
 A Discord bot that allows users to place predictions on crypto assets. Currently supported assets are any assets on the Binance futures exchange. Assets that look like ``BTCUSDT``

- BTC
- ETH
- LINK
- XRP
- ...more

## Commands
The commands take advantage of the new discord slash commands instead of the traditional  

- ``/prediction`` is how place a prediction. Example: ``/prediction symbol:BTCUSDT direction:Up``
    - ``Symbol`` The symbol to place the prediction on. 
    - ``Direction`` If you think the asset will gain or loss value in the next 24 hours. Up/Down
    - ``Timeframe`` This is the timeframe that you want the bot to check if you were correct. Values are in hours and are 1, 6, 12 and 24
- ``/mystats`` Tells you how well you're doing.

You start a command just like you are starting any message to a channel. Type a ``/`` then the name of the command. It will likely auto-complete for you.

## Inviting to your discord.

For now, until features are more complete, will only be available on the Cryptonauts discord server
