hmpps-delius-core-management-server-bootstrap
=========

Bootstrap Ansible role to setup the delius-core management server


Role Variables
--------------

```yaml
training_scripts_dir: Directory to hold the training scripts - defaults to /u01/training
app_scripts_dir: Directory to hold the app scripts - defaults to /u01/app
training_scripts_repo: Git repo containing the training scripts
app_scripts_repo: Git repo containing the app scripts
database_host: Hostname of the delius database
database_sid: SID of the delius database
ldap_host: Hostname of the LDAP
ldap_port: LDAP port
```

License
-------

MIT

Author Information
------------------

HMPPS Digital Studio
