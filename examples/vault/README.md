# Ansible Vault Example

This directory demonstrates how encrypted secrets can be managed using Ansible Vault.

Typical data includes:

- Passwords
- API Keys
- Tokens
- Certificates

Example:

```bash
ansible-vault create secrets.yml
ansible-vault edit secrets.yml
ansible-vault view secrets.yml
```

Vault files should never be committed unencrypted.
