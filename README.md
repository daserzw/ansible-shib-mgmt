# MGMT Operations

## Basic Operations (ansible roles)

### Backup

Create an up-to-date dump of mysql [and ldap if present].

playbook: make_a_backup.yml

### Enable maintenance

Shutdown all the IdP related services.

Disable the apache2 idp.conf.

Set up an all-catch maintenance page.

playbook: enable_maintenance.yml

### Disable maintenance

Disable the maintenance page.

Enable the apache2 idp.conf.

Turn on all the IdP related services.

playbook: maintenance-disable.yml




