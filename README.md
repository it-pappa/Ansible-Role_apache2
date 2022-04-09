Provision Apache2 on Linux hosts
=========

This role will determind the linux distro and install apache2. 

Requirements
------------
- Sudo access to remote host. 



Dependencies
------------
- ansible.posix

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: webserver
      become: yes
      gather_facts: true

      roles:
      - provision_apache2

License
-------

BSD

Author Information
------------------

Dan Eckholm - IT-Pappa
