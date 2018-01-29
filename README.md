# Nebula Explorer V2 based off https://github.com/carsenk/explorer

##License

The code in this branch is licensed under GPLv3 (see LICENSE file)

##Installation

`git clone`

`npm install`

`bower install`

`npm start`

Make sure to install geth as well for the NBAI explorer to be able to function. Then run:

`geth --rpc --rpcaddr localhost --rpcport 8545 --rpcapi "web3,eth" --rpccorsdomain "http://localhost:8000"`

Then visit http://localhost:8000 in your browser of choice after you npm start the explorer


