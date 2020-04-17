Role Name
=========

An ansible role to setup VIM environment to weshouman's best practice

Requirements
------------

Ack & Git may be used and each gets installed if required and not present.

Role Variables
--------------

```install_prosession```:      (TRUE/false) to install vim-prosession  
```install_ack```:             (TRUE/false) to install vim-ack  
```install_secure_modelines``: (TRUE/false) to install vim-secure-modelines  
```custom_scripts``:           [] to copy the mentioned scripts  

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: weshouman.vim_env, install_ack: false }

License
-------

MIT

Author Information
------------------

Walid Shouman
