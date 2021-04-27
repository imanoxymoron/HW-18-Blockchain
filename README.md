# HW-18-Blockchain

Welcome to zbank proof of authority blockchain. 

In order to start the network you must: 

1.) Start puppeth via geth:

./puppeth

2.) Start the initial mining node:

./geth --datadir node1 --mine --miner.threads 1

3.) Start node 2 via: 

./geth --datadir node2 --port 30304 --rpc --bootnodes "enode://61b87e94e6f33577a0b06d1e40e47e819217a27a85697b840d2a046c195f8270f707d1b3a0a68a84215ef42527f0a7206dd5afa63315316af80fcea539e4fd6e@127.0.0.1:30303" --ipcdisable

Note - geth flags required to get both nodes to mine:

self=enode://61b87e94e6f33577a0b06d1e40e47e819217a27a85697b840d2a046c195f8270f707d1b3a0a68a84215ef42527f0a7206dd5afa63315316af80fcea539e4fd6e@127.0.0.1:30303

./geth --datadir node2 --port 30304 --rpc --bootnodes "enode://61b87e94e6f33577a0b06d1e40e47e819217a27a85697b840d2a046c195f8270f707d1b3a0a68a84215ef42527f0a7206dd5afa63315316af80fcea539e4fd6e@127.0.0.1:30303" --ipcdisable

Now you can go to my crypto and transact:  

Open up my crypto to using your private keys.  Change your network at the bottom left hand corner to zbank. 

![image](https://user-images.githubusercontent.com/72050478/116294381-e75b7c00-a765-11eb-8dd6-543d191c8a61.png)

Next, after changing the network, you are ready to test the blockchain.  

Using your own wallet to access the network and address on the network. You can navigate to:

![image](https://user-images.githubusercontent.com/72050478/116297041-e24bfc00-a768-11eb-9268-2eb5a1f65375.png)

This allows you to test transactions in our custom blockchain.  
