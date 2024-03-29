# 1) Auto_install script
```python
sudo apt install curl -y && source <(curl -s https://github.com/nodekhanhnq/Aligned-Layer/blob/main/alignedlayer_auto)
```

Aligned Layer
Website: https://alignedlayer.com/

Twitter: https://twitter.com/alignedlayer

Explorer: https://explorer.nodesync.top/Alignedlayer-Testnet/staking

Faucet: https://faucet.alignedlayer.com/

# 2) Manual installation

### Preparing the server
```python
sudo apt update && sudo apt upgrade -y
apt install curl iptables build-essential git wget jq make gcc nano tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev -y
```

## GO 1.21.4
```python
ver="1.21.4"
wget "https://golang.org/dl/go$ver.linux-amd64.tar.gz"
sudo rm -rf /usr/local/go
sudo tar -C /usr/local -xzf "go$ver.linux-amd64.tar.gz"
rm "go$ver.linux-amd64.tar.gz"
echo "export PATH=$PATH:/usr/local/go/bin:$HOME/go/bin" >> $HOME/.bash_profile
source $HOME/.bash_profile
go version
```
