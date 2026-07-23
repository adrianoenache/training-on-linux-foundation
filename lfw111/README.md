# Introduction to NodeJS LFW111

## Setup on Linux or MacOS

- Repository of Node Version Manager (NVM) [https://github.com/nvm-sh/nvm](https://github.com/nvm-sh/nvm)
- Release 0.40.6 - Jul 23, 2026 [https://github.com/nvm-sh/nvm/releases](https://github.com/nvm-sh/nvm/releases)

### Install NVM

This command fetch and execute the instalation.

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.6/install.sh | bash
```

This command restart de `.bashrc`

```bash
source ~/.bashrc
```

This command verify it the `PATH` is configured.

```bash
command -v nvm
```

This command show the current version of NVM.

```bash
nvm --version
```

This command list NodeJS instaled avaliable.

```bash
nvm ls
```

This command list NodeJS avaliable on-line to be instaled.

```bash
nvm ls-remote
```

### Re-install NVM

This command remove NVM from bash session.

```bash
nvm unload
```

This command remove NVM instalation.

```bash
rm -rf ~/.nvm
```

Remove from file `.bashrc` the `PATH` configuration.

```bash
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
```

Follow the install NVM instructions abobe.

### Install NodeJS

This command install the NodeJS from the on-line.

```bash
nvm install 24.18.0
```

This command set the NodeJS default version.

```bash
nvm alias default 24.18.0
```

### For Windows

Node Version Switcher (NVS) is a similar NodeJS manager

- Repository [https://github.com/jasongin/nvs](https://github.com/jasongin/nvs).
- Release 1.7.1 - Aug 16, 2023 [https://github.com/jasongin/nvs/releases](https://github.com/jasongin/nvs/releases)