
# stable-releases

​

Ubuntu AMD64 Binary Release: https://github.com/ndagnetwork/stable-releases/blob/master/ndag.tar.gz

Windows X64 Binary Release: https://github.com/ndagnetwork/stable-releases/blob/master/ndagwallet.zip
​


Windows X64 V0.1.2(up to 96 threads): https://github.com/ndagnetwork/stable-releases/blob/master/ndagwallet-windows-x64-0.1.2.zip
​


Exwallet will be cancelled and a full-node wallet will be adopted to support more RPC functions of the exchange. For example, GetNewAddress, SendCoinTo, and Listtransactions, 

​

# GetNewAddress

GetNewAddress - Generate A New wallet address

​

# SendCoinTo

SendCoinTo - Send coin to another address

​

# Listtransactions

Listtransactions - List all transactions that have occurred for an address or entire Wallet

​

​

Instead of using proactive notification, RPC uses passive queries instead, which makes it easier to get the wallet's transactions based on scheduled tasks.(for example: crontab -e )

​
