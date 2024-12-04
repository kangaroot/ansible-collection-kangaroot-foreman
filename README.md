# Ansible collection: kangaroot.foreman

Collection to manage Foreman (and derived products))configuration and contents.

## Requirements

Ansible Core 2.13.0 or higher is required for the roles in the collection.

## Collection Variables

The `group_vars` directory contains example vars files for the important variables used in the collection roles.

## Dependencies

The roles in this collection make use of the `theforeman.foreman` and `theforeman.operations` collections.

To install the required collections, execute

```shell
ansible-galaxy collection install -r requirements.yml
```

in the collection directory.

