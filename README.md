# lazygit-ephemeral
Ephemeral Theme for lazygit

## How to use
- paste the contents `ephemeral.yml` into the `config.yml` file, and set this in your ~/.config/nvim/init.lua `vim.g.lazygit_config = false` this will allow it to be used in lazyvim as well!<br/>
  <center>OR<center/>
- specify the config file as follow, (you can add several config files, separated by commas). this will only work on the terminal instance of lazygit <br/>
  ```
  lazygit --use-config-file="$HOME/.config/lazygit/themes/ephemeral.yml"
  ```
### NOTE: 
The background color depends on your terminal, to have the ephemeral background color as the one used in the doom emacs theme set  your terminal background to `#28323E`

# TODO:Including this in the neovim theme directly
- need to add the theme in the following file `lua/ephemeral/init.lua`
