# ⚙️ Configuration Serveur avec Ansible

Ce projet utilise **Ansible** pour configurer automatiquement un serveur Linux (VPS).

## 📁 Contenu

- `inventory.ini` – Liste des serveurs à configurer  
- `playbook.yml` – Playbook principal

## ▶️ Utilisation

```bash
ansible-playbook -i inventory/hosts.ini playbooks/setup.yml
