# Dotfiles

> This repository contains machine-specific configuration to accompany my dotfiles.

After cloning this repo, run `curate -v` to automatically set up the dotfiles development
environment.

__Please Note:__ Dotfiles uses [config_curator](https://rubygems.org/gems/config_curator) gem for installation.

# Install

```bash
git clone git@github.com:shivapoudel/dotfiles.git ~/.dotfiles
cd ~/.dotfiles

# Submodule
git submodule init
git submodule update

# Dotfiles
curate -v
./vim-plugins

# Installer
mkdir -p /usr/local/bin
./bin/{apigen|phpcs|phploy|phpunit|wp-cli}-install
```

For Windows add `{git_executable_path}/usr/local/bin/` directory to PATH using [Path Editor](https://patheditor2.codeplex.com/) tool.

# License

Copyright (c) 2015 Shiva Poudel  
Licensed under the MIT license:  
<http://shivapoudel.mit-license.org/>
