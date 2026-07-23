# Introduction to NodeJS LFW111

## Setup on Linux or MacOS

- Node Version Manager (NVM) repository [https://github.com/nvm-sh/nvm](https://github.com/nvm-sh/nvm)
- Release 0.40.6 - Jul 23, 2026 [https://github.com/nvm-sh/nvm/releases](https://github.com/nvm-sh/nvm/releases)

### Install NVM

This command fetchs and execute the instalation.

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.6/install.sh | bash
```

This command restarts `.bashrc`

```bash
source ~/.bashrc
```

This command checks if the `PATH` is set.

```bash
command -v nvm
```

This command show the current NVM version.

```bash
nvm --version
```

This command lists the available installed NodeJS.

```bash
nvm ls
```

This command lists NodeJS available online to be installed.

```bash
nvm ls-remote
```

### Reinstall NVM

This command removes NVM from the bash session.

```bash
nvm unload
```

This command removes the NVM installation.

```bash
rm -rf ~/.nvm
```

Remove the `PATH` setting from the `.bashrc` file.

```bash
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
```

Follow the NVM installation instructions above.

### Install NodeJS

This command installs NodeJS from online options.

```bash
nvm install 24.18.0
```

This command sets the default version of NodeJS on NVM.

```bash
nvm alias default 24.18.0
```

### For Windows

Node Version Switcher (NVS) is a similar to NVM NodeJS manager.

- Repository [https://github.com/jasongin/nvs](https://github.com/jasongin/nvs).
- Release 1.7.1 - Aug 16, 2023 [https://github.com/jasongin/nvs/releases](https://github.com/jasongin/nvs/releases)