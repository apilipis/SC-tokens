To use this:

For now, we are running this on a dev chain because we are cheap students. To run this on your own machine:
1. Install ethereum. See ethereum.org/cli
2. geth --datadir "./data" --dev --unlock 0 --mine --minerthreads 1
3. In another terminal, geth --datadir "./data" --dev attach ipc:data/geth.ipc

For later, we can set this up: https://github.com/ethereum/go-ethereum/wiki/Setting-up-private-network-or-local-cluster

The script is in tokens.js

Source: https://ethereum.stackexchange.com/questions/2751/deploying-the-greeter-contract-via-the-geth-cli-is-not-registering-in-my-private
