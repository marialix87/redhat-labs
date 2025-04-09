# redhat-labs

# 🧪 Lab 1 – Servidor Apache con LVM y SELinux

## 🎯 Objetivo
Instalar y configurar Apache (`httpd`) en RHEL/AlmaLinux con un volumen lógico LVM montado en `/var/www/html`, habilitar firewall y asegurar que SELinux no bloquee el servicio.

---

## 🔧 Entorno
- SO: AlmaLinux 8 / CentOS 8 / RHEL 8
- Usuario: root o con privilegios sudo
- Requiere: 1 disco adicional para LVM

---

## 🔹 Paso 1: Instalar Apache
```bash
sudo dnf install httpd -y
sudo systemctl enable --now httpd
