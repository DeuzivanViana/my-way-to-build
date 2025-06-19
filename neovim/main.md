Source: https://github.com/neovim/neovim

# Setup
`sudo apt install ninja-build gettext cmake curl build-essential`

# Compile
`make CMAKE_BUILD_TYPE=Release CMAKE_INSTALL_PREFIX=$HOME/container/neovim -j12`

When its done, use `stripe -s`on nvim executable.