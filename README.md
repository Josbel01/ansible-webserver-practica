# Práctica: Automatización de servidor web con Ansible

## Objetivo
Configurar un servidor web Apache automáticamente usando Ansible.

## Archivos
- **hosts.ini** → Inventario de Ansible (usa localhost).
- **playbook.yml** → Playbook que instala y configura Apache.
- **README.md** → Documentación de la práctica.

## Pasos para ejecutar
1. Instalar Ansible en Ubuntu WSL:
   ```bash
   sudo apt update && sudo apt install ansible-core -y
