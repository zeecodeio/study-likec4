# Study LikeC4

## Local environment Setup

### Install asdf on Ubuntu

```bash
sudo apt install -y curl
curl -fsSL https://asdf-vm.com/install.sh | bash
```

### Install node using asdf

```bash
asdf plugin-add nodejs
asdf install nodejs latest
asdf global nodejs latest
```

### Install likec4

```bash
npm install --global likec4
```

## Run

```bash
likec4 serve
```
