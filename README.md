![Ansible Lint](https://github.com/johanneskastl/ansible-role-suse-ses-prepare_minions/workflows/Ansible%20Lint/badge.svg)

suse-ses-prepare_minions
=========

Prepare the minions in a SUSE Enterprise Storage Cluster

Requirements
------------

None.

Role Variables
--------------

- `domain_name`: Domain name to use for the entries in `/etc/hosts`.
- `salt_minion_packages`: List of packages needed for a salt minion.
- `salt_minion_service`: Name of the salt minion service, by default `salt-minion`.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: 'johanneskastl.suse-ses-prepare_minions' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
