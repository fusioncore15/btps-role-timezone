# btps.timezone

Configuration de la timezone du système d'exploitation.

## Variables

```yaml
---
# Timezone name - Default value is UTC
timezone_name: "Etc/UTC"

```

## Exemple d'utilisation du rôle

```yaml
---
- hosts: all
  vars:
    timezone_name: "Europe/Paris"

  # Use role
  roles:
    - role: btps.timezone

```

## Compatibilités

Ce role fonctionne sur Debian 9.
