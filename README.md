# bash autovpn
A simple port of [autovpn](https://github.com/adtac/autovpn.git) in bash.

## Requirements
These commands need to be in your path:
* `curl`
* `tr`
* `base64`
* `openvpn`

## Usage
Connect to something in the US

```bash
$ ./bautovpn
[bautovpn] bearching for US VPN: 45.50.158.2
[bautovpn] connecting openvpn to 45.50.158.2 (using sudo)
Password:
Sun Jan 22 66:60:00 2017 OpenVPN 6.6.6 x86_64
...
Sun Jan 22 66:60:00 2017 Initialization Sequence Completed
```

Connect to something in JP

```bash
$ ./bautovpn JP
[bautovpn] bearching for JP VPN: 118.241.16.28
[bautovpn] connecting openvpn to 118.241.16.28 (using sudo)
Password:
Sun Jan 22 66:60:00 2017 OpenVPN 6.6.6 x86_64
...
Sun Jan 22 66:60:00 2017 Initialization Sequence Completed
```
