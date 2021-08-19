# Blockchain-Homework









                                                    


### CORGINET TEST RUN ###




### Hello! I understand that you are ready to get the Corgi testnet up and running. Below you will find the instructions to do just so!



### To begin with, you will need two files from the Geth & Tools 1.9.7 build - https://geth.ethereum.org/downloads/


### Place those into a directory, preferably named after said net, and open a terminal.

### From the terminal, please enter these two commands to initialize the nodes:
    ./geth --datadir node1 init networkname.json
    ./geth --datadir node2 init networkname.json
 
### Then, to begin the mining on the two nodes, please enter these commands:

    ./geth --datadir node1 --unlock "0xEC80189509063CfbdD2e7753c2C60C4B8B5E7c76" --mine --rpc --allow-insecure-unlock
    ./geth --datadir node2 --unlock "0xA9bFe6BF062A87F73750487162546A4C747DDB5a" --mine --port 30304 --bootnodes "enode://04ff194a5afe7908b42994d19a2faf1c735d5b58eb38c30e6c88c202d7c8832eff6820424a73ca60ee9103b8bcffea5d29a836dcf668fcba0cc9bf6d56b03103@127.0.0.1:30303" --ipcdisable --allow-insecure           -unlock 

### From there, the network should be up and running and showing results!



https://gw.bootcampcontent.com/GW-Coding-Boot-Camp/gwu-virt-fin-pt-04-2021-u-c/-/raw/master/02-Homework/18-Blockchain/Instructions/Resources/Images/change-network.png
### To connect to MyCrypto, please add a new server from the bottom leftside, and input the information as follows:
    Node Name - Corginet
    Network - Custom
    Network Name - corginet
    Currency - ETH
    ChainID - 65327
    URL - http://126.0.0.1:8545
    
### From there, navigate to the bottom buttons on the View & Send tab, and click 'Keystore File'


### Navigate to the folder containing the node1 keystore file, which should be located in:
    /corginet/node1/keystore
    
### Grats! Now you have access to the glorious amount of money held within!...



### To send any amount, where its labeled "To Address", simply add the desired address in, and send away!








In regards to the more technical side of corginet:


- It is a clique build using PoA
- The blockchain ID is 63527
- The account password is PopRiddle21 (Of course its named after the corgis!)
- Nodes1 and Node2 are running on port 30303 and 30304 respectively.
