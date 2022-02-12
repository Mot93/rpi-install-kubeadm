Role Name
=========

Role design to install kubeadm, kubelet and kubectl on a raspberry pi

Requirements
------------

You need root privileges to run this script.
    become: yes

Example Playbook
----------------

Out of the box:

    ---
    - hosts: localhost
      remote_user: pi
      become: yes
      roles:
        - rpi-install-kubeadm


License
-------

MIT

Author Information
------------------

If you like my work and whant to know more, visit my website:
[www.mattiarubini.com](https://www.mattiarubini.com)
