
# stable-releases
2
​
3
Ubuntu AMD64 Binary Release: https://github.com/ndagnetwork/stable-releases/blob/master/ndag.tar.gz
4
​
5
The Windows X64 version is being prepared and will be uploaded when the work is completed. Exwallet will be cancelled and a full-node wallet will be adopted to support more RPC functions of the exchange. For example, GetNewAddress, SendCoinTo, and Listtransactions, 
6
​
7
# GetNewAddress
8
GetNewAddress - Generate A New wallet address
9
​
10
# SendCoinTo
11
SendCoinTo - Send coin to another address
12
​
13
# Listtransactions
14
Listtransactions - List all transactions that have occurred for an address or entire Wallet
15
​
16
​
17
Instead of using proactive notification, RPC uses passive queries instead, which makes it easier to get the wallet's transactions based on scheduled tasks.(for example: crontab -e )
18
​
