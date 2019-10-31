Getting started
===============

Use the following instructions to mine a block.

Open your wallet, and make sure your wallet is connected with a node.
Your wallet is connected when you see the icon [Wallet connections] in the lower corner of your wallet.

The message “Synchronizing with network...” will disappear once you mine your first block.

Close your wallet and create the file nexbit.conf in the folder “%APPDATA%\nexbit\”. *For windows wallet

Paste the following text into nexbit.conf and save the file.

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
addnode=nbc1.npay.life
addnode=nbc2.npay.life
addnode=nbc3.npay.life
addnode=nbc4.npay.life
addnode=nbc5.npay.life
addnode=nbc6.npay.life
addnode=nbc7.npay.life
addnode=nbc8.npay.life
addnode=68.183.253.3
addnode=68.183.247.125
addnode=68.183.254.141

more nodes will host soon. Pleaase in your /nexbit.conf/ file addnodes for faster sync.

```
NEXBIT.IO

