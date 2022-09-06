# Vanilla OS PPA

## Setup
```bash
curl -s --compressed "https://vanilla-os.github.io/ppa/KEY.gpg" | gpg --dearmor | sudo tee /usr/share/keyrings/vanilla-archive-keyring.gpg
sudo curl -s --compressed -o /etc/apt/sources.list.d/vanilla-os.list "https://vanilla-os.github.io/ppa/vanilla-os.list"
sudo apt update
```
