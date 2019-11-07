freehck.sleep
=========

sleep for a while

Description
-----------

This role is useful when you need to wait a bit between tasks in role dependencies

Role Variables
--------------

`sleep_seconds`: time in seconds to sleep, default is `0`, i.e. don't sleep at all

Example
-------

    - role: freehck.sleep
      sleep_seconds: 60

Install
-------

This role can be installed from [Ansible Galaxy](https://galaxy.ansible.com/):

`ansible-galaxy install freehck.sleep`

License
-------

MIT

Author Information
------------------

Dmitrii Kashin, <freehck@freehck.ru>
