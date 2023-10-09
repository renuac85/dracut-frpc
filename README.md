# dracut-frpc

> Currently does not work. Still trying to figure out why.

Run an [FRP](https://github.com/fatedier/frp) client during system boot using [Dracut](https://en.wikipedia.org/wiki/Dracut_(software)).

Meant for use with [dracut-crypt-ssh](https://github.com/dracut-crypt-ssh/dracut-crypt-ssh) to remotely decrypt a Fedora server that is behind [NAT](https://en.wikipedia.org/wiki/Network_address_translation).

## Usage

Run `setup.sh` to:

1. Download the latest version of FRPC.
2. Grab a user-defined FRPC config file.
3. Install the Dracut module.
