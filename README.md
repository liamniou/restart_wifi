# RESTART_WIFI README

## About

Enable/disable Wi-Fi endpoint on F@st 3890 Com Hem Wi-Fi Hub C2 router.

Slightly adjusted version of [this script](https://github.com/xenago/nix-scripts/blob/8646aef4942050d5ed95bf4a1811b2b40b081a52/network/bell_hh_wifi_disable.py).

## How to use

```bash

export ROUTER_HOST=...
export ROUTER_USERNAME=...
export ROUTER_PASSWORD=...

python main.py --gh off
...
python main.py --gh on
```
