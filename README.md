## Ubuntu packages

My apps are available as Ubuntu packages. Run these three commands once, then `sudo apt update && sudo apt upgrade` keeps everything current:

```
curl -fsSL https://gypsynature.github.io/apt/apt-archive-keyring.gpg | sudo tee /usr/share/keyrings/apt-archive-keyring.gpg >/dev/null
echo "deb [signed-by=/usr/share/keyrings/apt-archive-keyring.gpg] https://gypsynature.github.io/apt stable main" | sudo tee /etc/apt/sources.list.d/gypsynature.list
sudo apt update
```

Current apps: **srtdebug**, an SRT stream inspector. 
`sudo apt install srtdebug`

More are listed at [https://github.com/gypsynature/apt.](https://gypsynature.github.io/apt/)
