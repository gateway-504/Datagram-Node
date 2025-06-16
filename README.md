# Datagram-Node

# Project Intro
Datagram is the DePIN baselayer — an AI-driven, Hyper-Fabric Network enabling fast, scalable connectivity and DePIN interoperability.

Fund: https://cryptorank.io/drophunting/datagram-activity843 (NA)

X: https://x.com/dgramnetwork?mx=2

TG: https://t.me/datagramnetwork

DC: https://discord.gg/datagramnetwork 

# Tutorial

### Minimum Hardware	Requirement

*CPU	4 Core
*RAM	4 GB
### Preparation Before Install Node
*Create acoount
https://dashboard.datagram.network?ref=979051572
*Save your node key from httpa://dashboard.datagram.network/wallet?tab=licenses

<h1 align="center">INstalling NOde</h1>
## 1.Update packages
``` 
apt update 
```


## 2.Install wget & tmux(skip if you have installed)
``` 
apt install wget tmux -y
 ```


## 3.Download file node
```
wget https://github.com/Datagram-Group/datagram-cli-release/releases/latest/download/datagram-cli-x86_64-linux
```

```
chmod +x datagram-cli-x86_64-linux
```


## 4.Create tmux session
```
tmux new -s datagram
```


## 5.Run Node
```
./datagram-cli-x86_64-linux run -- -key your_key
```
* change your-key with your actual node key from dashboard.datagram.network/wallet?tab=licenses

## 6.Detach session (make sure node is running)
ctrl b + d


## 7.Attach session to chcek the logs
```
tmux attach -t datagram
```


### Check your node in  Dashboard
https://dashboard.datagram.network/overview

DONE
