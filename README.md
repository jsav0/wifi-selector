---
WiFi Selector
I created this little tool to allow easy switching between wireless networks. Usually i prefer dmenu to facilitate the interaction, but if i'm limited to a TTY, then peco works just great. 

### With peco:
[peco source](https://github.com/peco/peco)
![wifiselector with peco](http://n0a110w.xyz/img/uncompressed/wifiselector_peco-demo.gif)

### With dmenu
[dmenu source](https://git.suckless.org/dmenu/)
![wifiselector with dmenu](http://n0a110w.xyz/img/uncompressed/wifiselector_dmenu-demo.gif)

## Basic Usage
```
USAGE: ./wifi_selector.sh [OPTIONS]
  Quick wifi menu using iwd and your choice of dmenu or peco

OPTIONS:
  -d	dmenu, depends on X 
  -p	peco, works in a tty
```


