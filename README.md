# Install-Foundry

1-Installation Using Foundryup:

Open your terminal and install Foundryup by running the following command:
```bash
curl -L https://foundry.paradigm.xyz | bash
```
After the installation is complete, make the foundryup command available by following the on-screen instructions.
2-Installing Foundry VTT with Foundryup:

Install the latest (nightly) compiled binaries using the Foundryup command:
```bash
foundryup
```
3-Clone
```bash
git clone https://github.com/foundry-rs/foundry.git
cd foundry
```
## Install-[Foundry](https://book.getfoundry.sh/getting-started/installation)
After cloning the repository, run the following command to install the dependencies
```bash
# Update forge packages
foundryup

# Install or update dependencies
forge install
```
## or
Build from Source Code:

First, use rustup.rs to install the Rust compiler and Cargo package manager. Then, compile Foundry VTT from source code using the commands below:
```bash
# Clone
git clone https://github.com/foundry-rs/foundry.git
cd foundry
# Install Forge
cargo install --path ./crates/forge --profile local --force --locked
# Install Cast
cargo install --path ./crates/cast --profile local --force --locked
# Install Anvil
cargo install --path ./crates/anvil --profile local --force --locked
# Install Chisel
cargo install --path ./crates/chisel --profile local --force --locked
```


