# Deployment Example

Typical deployment workflow:

1. Update inventory
2. Validate playbook syntax
3. Run playbook in check mode
4. Execute deployment
5. Verify services
6. Review logs
7. Roll back if required

Example:

```bash
ansible-playbook -i inventories/production.ini playbooks/site.yml

ansible-playbook --check playbooks/site.yml

ansible-playbook --limit webservers playbooks/nginx.yml
```
