1. Install Rust
```curl https://sh.rustup.rs -sSf | sh```
. "$HOME/.cargo/env"```

2. Install sfoundryup
```curl -L \
     -H "Accept: application/vnd.github.v3.raw" \
     "https://api.github.com/repos/SeismicSystems/seismic-foundry/contents/sfoundryup/install?ref=seismic" | bash
source ~/.bashrc```

3. Install sfoundryup
```sfoundryup```

4. Clone repository

```git clone --recurse-submodules https://github.com/SeismicSystems/try-devnet.git && cd try-devnet/packages/contract/```

5. Deploy Smartcontract

```bash script/deploy.sh```

Interact With encrypted contract

1. Install bun

```curl -fsSL https://bun.sh/install | bash```

2. Install dependencies
```cd try-devnet/packages/cli/ && bun install```

3. Send transaction
```bash script/transact.sh```

If you have done all this thing, send a screenshot in Seismic discord on #devnet channels
