# Datagram-Node

# Project Intro
Datagram is the DePIN baselayer — an AI-driven, Hyper-Fabric Network enabling fast, scalable connectivity and DePIN interoperability.

Funding    : https://cryptorank.io/drophunting/datagram-activity843 (NA)

X          : https://x.com/dgramnetwork?mx=2

Telegram   : https://t.me/datagramnetwork

Discord    : https://discord.gg/datagramnetwork 

# Tutorial

### Minimum Hardware	Requirement

* 4 Cores CPU	

* 4 gb RAM

* 10 gb storages

### Preparation Before Install Node

* Create acoount at https://dashboard.datagram.network?ref=979051572

* Open https://dashboard.datagram.network/wallet?tab=licenses and save the Keys


<h1 align="center">Installing NOde</h1>


## 1.Update packages

``` 
apt update 
```


## 2.Install wget & tmux(skip if you have installed)
``` 
apt install wget tmux -y
 ```


## 3.Download file node and give permission
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
