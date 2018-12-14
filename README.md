# Dotfiles

> This repository contains machine-specific configuration to accompany my dotfiles.

# Install

For Windows add PHP and `{git_executable_path}/usr/local/bin/` directory to PATH using [Path Editor](https://patheditor2.codeplex.com/) tool.

__Please Note:__ Use as administrator privilage within VS Code terminal.

```bash
git clone --recursive git@github.com:sanzeeb3/dotfiles.git ~/.dotfiles
cd ~/.dotfiles

# Dotfiles
./install
```

# Update

```bash
git submodule update --init --recursive --remote
```

# License

Copyright (c) 2018 Sanjeev Aryal  
Licensed under the MIT license:  
<http://sanzeeb3.mit-license.org/>
