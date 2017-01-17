# POCoin

Scrypt coin made for educational purposes.
 
===========================================

Adres prefix: p  
Coins: 					1337 POC / Block  
Block target time: 		1 min  
Difficulty retarget: 	1 min  
Block halving: 			Om de 262.800 blokken (Ongeveer elk half jaar)  


RPC Port:				56883  
Testnet Port:			38865  
P2P Port:				56884  

===========================================

### Compile Instructies: 
Dependencies:  
`apt-get install ntp git build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev libqrencode-dev`

Clone:  
`git clone https://github.com/dexter130/POCoin.git`

Compile POCoin Daemon (Ubuntu 14.04 LTS 64 bit):  
`cd pocoin`  
`make -f makefile.unix USE_UPNP=-`