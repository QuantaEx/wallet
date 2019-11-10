Getting started
===============

Use the following instructions to mine a block.

Open your wallet, and make sure your wallet is connected with a node.
Your wallet is connected when you see the icon [Wallet connections] in the lower corner of your wallet.

The message “Synchronizing with network...” will disappear once you mine your first block.

Close your wallet and create the file nexbit.conf in the folder “%APPDATA%\nexbit\”. *For windows wallet

Paste the following text into nexbit.conf and save the file.
Below CONF is for node
```bash
rpcuser=username
rpcpassword=rpcpass
rpcallowip=127.0.0.1
rpcport=13519
listen=1
server=1
addnode=node list below
```

Download the latest version of cpuminer  and extract the zip file.

More nodes added:

```bash
Below are the only official whitelisted nodes
*************************************
addnode=167.71.78.206
addnode=157.245.76.203
addnode=167.172.239.154
addnode=165.227.225.78
addnode=157.230.99.176
addnode=206.189.117.70
addnode=167.71.140.104
addnode=138.197.135.237
addnode=159.65.136.159
addnode=165.22.219.149

more nodes will host soon. Pleaase in your /nexbit.conf/ file addnodes for faster sync.

```
NEXBIT.IO

