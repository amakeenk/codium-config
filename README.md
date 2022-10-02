```
$ git clone git@github.com:amakeenk/codium-config.git
$ conf="${HOME}/.config/VSCodium/User/settings.json"; rm -fv ${conf}; ln -sv "$(pwd)/codium-config/settings.json" ${conf}
```
