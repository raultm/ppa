# ppa
Repo of custom debian packages


# Install apt repo

```
curl -s --compressed "https://raultm.github.io/ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/raultm_ppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/raultm.list "https://raultm.github.io/ppa/my_list_file.list"
apt update
```
