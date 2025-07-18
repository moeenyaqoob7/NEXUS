## Nexus Testnet 3

# Install dependencies
```
sudo apt update && sudo apt upgrade -y
sudo apt install -y build-essential pkg-config libssl-dev git protobuf-compiler
```
## For VPS
```
sudo apt update
sudo apt install screen -y
```

## Install Rust
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source ~/.cargo/env
```

# Install cli
```
curl https://cli.nexus.xyz/ | sh
source ~/.bashrc
