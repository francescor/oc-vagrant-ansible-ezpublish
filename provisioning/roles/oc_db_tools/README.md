Role Name
=========

postgres/mysql import from shared folder, remote db, ecc..


Role Variables
--------------

Defaults that should be set as group/host variables:
- DB_DUMP_DIR - where to load db dump, defualt is ./database_dump
- DB_DUMP_FILENAME

Dependencies
------------

None.

Example Playbook
----------------

```
ansible-playbook playbook.yml --tags "restore_db"

```

Author Information
------------------

Opencontent.it
