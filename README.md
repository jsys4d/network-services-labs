# 🌐 Network Services Labs

Laboratorios de configuración de servicios de red en Ubuntu Server 24.04 LTS, desarrollados durante la formación en CodeArts Solutions.

## 📦 Laboratorios incluidos

| Lab | Servicio | Descripción |
|---|---|---|
| dia12-bind9 | DNS (BIND9) | Servidor DNS interno con zonas directa e inversa para codearts.local |
| dia13-dnsmasq | DNS/DHCP (dnsmasq) | Sustitución de BIND9 por dnsmasq como servidor DNS y DHCP interno |
| dia14-squid | Proxy (Squid) | Servidor proxy HTTP/HTTPS con ACLs y políticas por departamento |

## 🔧 Entorno

- **Servidor:** svr (192.168.1.49)
- **Dominio:** codearts.local
- **SO:** Ubuntu Server 24.04 LTS

## 🔒 Políticas Squid por departamento

| Perfil | Rango IP | Política |
|---|---|---|
| Desarrollo | 192.168.1.100-120 | Sin ocio, acceso total |
| Marketing | 192.168.1.121-140 | Libre en horario de descanso |
| Administración | 192.168.1.141-160 | Solo whitelist profesional |

## 🏗️ Stack

![Linux](https://img.shields.io/badge/Linux-Ubuntu_24.04-orange?logo=linux&logoColor=white)
![BIND9](https://img.shields.io/badge/DNS-BIND9-blue)
![dnsmasq](https://img.shields.io/badge/DNS%2FDHCP-dnsmasq-green)
![Squid](https://img.shields.io/badge/Proxy-Squid-red)

---
*Desarrollado durante formación en CodeArts Solutions — CESUR Zaragoza 2024-2026*
