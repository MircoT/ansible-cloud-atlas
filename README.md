# ansible-galaxy-cloud-atlas

An Ansible role with useful tools for cloud systems.

A brief description of the role goes here.

How to
------

```bash
git clone https://github.com/MircoT/ansible-cloud-atlas
ln -s $HOME/ansible-cloud-atlas $HOME/.ansible/roles/ansible_cloud_atlas
cd ansible-cloud-atlas
ansible-playbook tests/test.yml
```

If you want to install a specific target:

```bash
ansible-playbook tests/test.yml --extra-vars "target_task=pm2"
```


Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

[Apache 2.0 License](LICENSE)

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
