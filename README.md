
BONES CryptoCoin
 
BONES CryptoCoin is unique adaptive reward coin that add difficulty bonus to standard reward system
Example 1:  block reward  7 bones + difficulty bonus (current difficulty is 2.88402)  =  7 +  2 =  9 bones total.
Example 2:  block reward 10 bones + difficulty bonus (current difficulty is 35.84302) = 10 + 35 =  45 bones total.
Total amount of Bones coins is variable from 3,800,000 (difficulty 2.7) to 200,000,000 (difficulty 100).
Price for 2 BONES coin can be unpredictable high.
BONES CryptoCoin adapts fast to high hash-rates but payouts for every k/hash spent. 
 
SPECIFICATIONS
NAME: BONES CryptoCoin 
SYMBOL: BONES
CRYPTOGRAPHY: Scrypt POW (Proof of Work)
MAXIMUM COINS: 3,800,000 (on difficulty 3)
PREMINE: 2% (bounty, giveaways, exchanges, faucets and pools)
BLOCK REWARDS: 7-10 + difficulty bonus rewards
BLOCK TIME: 1 Minute
DIFFICULTY RETARGET: 6 Hours
 
BLOCKS / REWARDS:
           1 - 200,000:  7 - 10  + difficulty bonus
200,001 - 300,000:  5 - 8    + difficulty bonus
300,001 - 400,000:  4 - 6    + difficulty bonus
400,001 - 500,000:  3 - 5    + difficulty bonus
500,001 - 600,000:  2 - 4    + difficulty bonus
600,001 - 700,000:  2 - 3    + difficulty bonus
700,001 - 800,000:  1 - 2    + difficulty bonus
800,001 - ***,***:       1         + difficulty bonus
 
1,000,000 blocks total.
 
Max coins (average difficulty 10)
19,200,000
 
Max coins (average difficulty 100)
192,000,000
 
Max coins (average difficulty 1000)
1,920,000,000
 
DOWNLOADS:
 
WINDOWS WALLET
coming soon!
 
LINUX GUI/DAEMON WALLET
coming soon!
 
MAC WALLET
coming soon!
 
ANDROID WALLET
coming soon!
 
WEBSITE / BLOCK EXPLORER / FAUCET / GAMES
ALL on one website - coming soon!
 
POOLS
coming soon!
 
EXCHANGES
coming soon!
 
COMMUNITY:
GOOGLE+
https://plus.google.com/u/0/101275248105817661352
 
FACEBOOK
https://www.facebook.com/BonesCoin
 
TWITTER
https://twitter.com/BonesCryptoCoin
 
REDDIT
http://www.reddit.com/r/BonesCoin/
 
PORTS
RPC 55255
P2P 55355
 
CONFIG:
bones.conf
rpcuser=hard-name-user
rpcpassword=hard-guess-password
server=1
daemon=1
 
Point your miner to 127.0.0.1:55255
and don't forget specify user and password as well.
 

sudo apt-get update
sudo apt-get install -y git-core build-essential libssl-dev libboost-all-dev libboost1.48-all-dev libdb5.1-dev libdb5.1++-dev libgtk2.0-dev 
git clone https://github.com/BonesCoin/Bones.git 
chmod 755 Bones/src/leveldb/build_detect_platform
cd Bones/src
make -f makefile.unix clean; make -f makefile.unix USE_UPNP= bonescoind
 
LINUX COMPILE GUIDE
 
sudo apt-get install build-essential libboost-all-dev libcurl4-openssl-dev libdb5.1-dev libdb5.1++-dev
sudo apt-get install libboost1.48-all-dev
make -f makefile.unix USE_UPNP=-
