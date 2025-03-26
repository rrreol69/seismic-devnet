# Setup Guide

## 1. Install Rust
```bash
curl https://sh.rustup.rs -sSf | sh
. "$HOME/.cargo/env"
```

## 2. Install sfoundryup
```bash
curl -L -H "Accept: application/vnd.github.v3.raw" "https://api.github.com/repos/SeismicSystems/seismic-foundry/contents/sfoundryup/install?ref=seismic" | bash
source ~/.bashrc
```

## 3. Run sfoundryup
```bash
sfoundryup
```

## 4. Clone repository
```bash
git clone --recurse-submodules https://github.com/SeismicSystems/try-devnet.git && cd try-devnet/packages/contract/
```

## 5. Deploy Smart Contract
```bash
bash script/deploy.sh
```

# Interact With Encrypted Contract

## 1. Install Bun
```bash
curl -fsSL https://bun.sh/install | bash
```

## 2. Install Dependencies
```bash
cd try-devnet/packages/cli/ && bun install
```

## 3. Send Transaction
```bash
bash script/transact.sh
```

# Final Step
If you have done all these steps, send a screenshot in the Seismic Discord on the #devnet channel.

### Quick Links

📱 **Discord Community**: [discord.gg/seismic](https://discord.gg/seismic)

🐦 **Twitter/X**: [@SeismicSys](https://x.com/SeismicSys)
