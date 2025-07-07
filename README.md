# ⚙️ Ansible – Configuration Serveur

Ce projet utilise **Ansible** pour automatiser la configuration d’un serveur (VPS).

## 📁 Contenu du dépôt

- `playbook.yml` – Playbook principal  
- `inventory.ini` – Fichier d’inventaire avec les adresses IP  
- `roles/` – Dossier contenant les rôles Ansible organisés par tâche  

## ▶️ Exécution du playbook

```bash
ansible-playbook -i inventory.ini playbook.yml

