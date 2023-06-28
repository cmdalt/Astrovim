# Astrovim

git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim

Run the nvim package manager to install plugins

nvim +PackerSync

Install Rust analyzer using LspInstall

nvim . // open nvim

You should now have a blank .nvim file open in front of you.

// Pres <Esc> to enter normal mode, then type the following

:LspInstall rust

:TSInstall rust
