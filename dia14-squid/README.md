# Día 14 — Servidor Proxy con Squid

## Descripción
Implementación de Squid como servidor Proxy HTTP/HTTPS con políticas dinámicas de navegación por departamento en Ubuntu Server 24.04 LTS.

## Archivos
- squid.conf — Configuración principal con ACLs por perfil
- bloqueo_ocio.txt — Lista de sitios de ocio bloqueados
- bloqueo_multimedia.txt — Lista de sitios multimedia bloqueados
- whitelist_admin.txt — Sitios permitidos para administración

## Perfiles configurados
- Desarrollo: 192.168.1.100-120 — Sin ocio, acceso total al resto
- Marketing: 192.168.1.121-140 — Libre solo en horario de descanso
- Administración: 192.168.1.141-160 — Solo whitelist profesional

## Entorno
- Servidor: svr (192.168.1.49)
- Puerto Proxy: 3128
- SO: Ubuntu Server 24.04 LTS
