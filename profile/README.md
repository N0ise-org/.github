## N0ise, quick reference

- Production instance: https://n0ise.io
- Google Docs:
    - Notes: https://docs.google.com/document/d/1L0AjGOIToKE0yX-Q6njupFJXKs0_uYYOGI45ww9VomU


### Environment quick setup

#### Cloning repos

```bash
git clone git@github.com:N0ise-org/n0ise.git
git clone git@github.com:N0ise-org/webapp-remix.git
git clone git@github.com:N0ise-org/logo-pack.git
```

#### Development Setup

- **Installing Golang**:
    - Official Guide: https://go.dev/doc/install
    - Debian:
    ```
    sudo apt update -y && sudo apt install golang
    ```
    - Homebrew: 
    ```
    brew install golang
    ```
 
- **Installing Docker** https://docs.docker.com/engine/install/debian/

- **Installing Node with NVM**:
1. Download nvm
```bash
https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

2. Config .bashrc
```bash
eport NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}"  ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh"  ] && \. "$NVM_DIR/nvm.sh"
```

3. Installing the runtime
```
nvm install --lts
nvm alias default 20
```

- **Installing build essentials**:
    - Debian:
    ```
    sudo apt install build-essential
    ```
