# Aquachain Explorer

## Dont use npm for serving

copy all static files into a directory and serve that.

##Installation

`git clone https://github.com/carsenk/explorer`

`npm install`

`bower install`

`npm start`

Make sure to install geth as well for the ETH explorer to be able to function. Then run:

`geth --rpc --rpcaddr localhost --rpcport 8545 --rpcapi "" --rpccorsdomain "http://localhost:8000"`

Then visit http://localhost:8000 in your browser of choice after you npm start the explorer

##Updates since original etherpaty/explorer base:

-Regular Expressions completed for Addresses, Block #s, and Transacions IDs (aka Search works great)

-The theme is based off Bootstrap V3 for responsive design.

-You can easily change from a dark or light theme utilizing https://bootswatch.com

-There is a basic API implemented now as well as well as a Aquachain Blockchain Information page

-Realtime ETH/USD Price Ticker

-Realtime Aquachain Hashrate

-Address Pages are integrated with Shapeshift to easily send a payment to an address.

-Responsive design

-Fontawesome Icons

-Block Time Averages

-Gas Prices/Limits

-Total/Current Difficulty

-Realtime latest blocks and recent transactions

-Other random blockchain info stats were added
