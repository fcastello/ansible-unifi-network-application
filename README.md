# ansible-unifi-network-application

Ansible role to install Unifi Network Aplication



Example Playbook
----------------
```yaml
- hosts: all
 - name: Install unifi
    import_role:
      name: fcastello.unifi_network_application
```

Limitations
-----------
- Tested only in ubuntu 24.04. Might work with other versions


License
-------

MIT

# To Do
- Install mongodb with the right ubuntu distro, at the time of writing this role mongodb didn't have prebuilt packages for ubuntu noble. But Jammy work on noble.