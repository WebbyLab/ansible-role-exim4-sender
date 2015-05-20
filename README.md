exim4-sender
=========

Installs and configures exim4 in send only mode

Role Variables
--------------

    exim4_sender_hostname: 'ubuntu-server'
    exim4_sender_root_address: 'root@ubuntu-server'

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: webbylab.exim4-sender, exim4_sender_hostname: 'myserver', exim4_sender_hostname: 'mail@example.com' }

License
-------

MIT

Author Information
------------------
WebbyLab (http://webbylab.com)