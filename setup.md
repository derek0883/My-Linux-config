
```bash
# nodejs
curl -sL install-node.now.sh/lts | bash

# spacevim
curl -sLf https://spacevim.org/install.sh | bash

npm install -g neovim
python -m pip install neovim
python3 -m pip install neovim

# rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
# add ~/.cargo/bin to PATH

rustup toolchain install stable
rustup toolchain install nightly
rustup default stable
rustup component add rust-src
rustup component add rls --toolchain nightly
cargo +nightly install racer

# Neovim 
https://github.com/neovim/neovim/releases
```
