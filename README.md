fever.jbmorley.co.uk
====================

Ansible deployment script for https://fever.jbmorley.co.uk.

Usage
-----

Create `passwords.yml` in the root directory of this repository. This should contain your preferred MySQL root user password, and fever user password. For example,

```yml
---

mysql_root_password: abc123
mysql_user_password: password
```

Run the playbook, providing your become password when asked:

```bash
ansible-playbook fever.yml
```
