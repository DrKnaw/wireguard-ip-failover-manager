# WireGuard installer

![Lint](https://github.com/angristan/wireguard-install/workflows/Lint/badge.svg)
![visitors](https://visitor-badge.glitch.me/badge?page_id=drknaw.wireguard-ip-failover-manager)

**Based on [wireguard-install](https://github.com/angristan/wireguard-install)**

## Requirements

Supported distributions:

- Ubuntu >= 16.04
- Debian 10

## Usage

Download and execute the script. Answer the questions asked by the script and it will take care of the rest.

```bash
curl -O https://raw.githubusercontent.com/DrKnaw/wireguard-ip-failover-manager/master/manager-failover.sh
chmod +x manager-failover.sh
./manager-failover.sh
```

It will install WireGuard (kernel module and tools) on the server, configure it, create a systemd service and a client configuration file.

Run the script again to add or remove ip!
