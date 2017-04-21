# massExploitConsole
a collection of tools with a cli ui

## what does it do?

- an easy-to-use user interface (cli)
- execute any adapted exploit with process-level concurrency
- crawler for baidu and zoomeye
- a simple webshell manager
- some built-in exploits (automated)
- more to come...

## requirements

- GNU/Linux or MacOS, fully tested under [Kali Linux (Rolling, 2017)](https://www.kali.org), Ubuntu Linux (16.04 LTS) and Fedora 25 (it will work on other distros too as long as you have dealt with all deps)
- `proxychains4` (in `$PATH`), used by exploiter, requires a working socks5 proxy (you can modify its config in `mec.py`)
- python packages:
    - `requests`
    - `bs4`
    - `pip install` on the go, sometimes `pip2` is needed

## screenshot

![](/screenshot/main.png)

## disclaimer

- please use this tool only on **authorized systems**, im not responsible for any damage caused by users who ignore my warning
- exploits are adapted from other sources, please refer to their author info
