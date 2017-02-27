ansible-openwrt-examples
========================

Requirements
------------

* Router with OpenWRT 15.05 installed
* Router root password set
* Client with ansible installed

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
