ansible-openwrt-examples
========================

Requirements
------------

* Router with OpenWRT 15.05 installed
* Router root password set
* Client with ansible installed

Dependencies
------------

| Role | Description |
|-----------|----------|
| [flandiGT/openwrt-uci](https://github.com/flandiGT/openwrt-uci) | ansible library for setting of uci config values on openwrt systems |
| [flandiGT/openwrt-system](https://github.com/flandiGT/openwrt-system) | ansible role for configuring general aspects of your openwrt system |
| [flandiGT/openwrt-network](https://github.com/flandiGT/openwrt-network) | ansible role for configuring network aspects of your openwrt system |
| [flandiGT/openwrt-wireless](https://github.com/flandiGT/openwrt-wireless) | ansible role for configuring WiFi aspects of your openwrt system |
| [flandiGT/openwrt-firewall](https://github.com/flandiGT/openwrt-firewall) | ansible role for configuring firewall aspects of your openwrt system |
| [flandiGT/openwrt-dhcp](https://github.com/flandiGT/openwrt-dhcp) | ansible role for configuring DHCP aspects of your openwrt system |
| [flandiGT/openwrt-ddns](https://github.com/flandiGT/openwrt-ddns) | ansible role for configuring dynamic-DNS aspects of your openwrt system |
| [flandiGT/openwrt-sqm](https://github.com/flandiGT/openwrt-sqm) | ansible role for configuring SQM aspects of your openwrt system |
| [flandiGT/openwrt-openvpn](https://github.com/flandiGT/openwrt-openvpn) | ansible role for configuring OpenVPN aspects of your openwrt system |
| [flandiGT/openwrt-ssh](https://github.com/flandiGT/openwrt-ssh) | ansible role for configuring SSH aspects of your openwrt system |

Run a playbook
--------------

Install playbook requirements:
```
ansible-galaxy install -r requirements.yml -p ./roles --force
```

Run a playbook:
```
ansible-playbook <selected playbook yml> -i inventory.ini --ask-pass
```
