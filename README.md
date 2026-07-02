# Cowrie Honeypot Lab 🍯

Honeypot SSH desplegado con Cowrie para captura y análisis 
de comportamiento de atacantes.

## Stack tecnológico
- Cowrie 3.0.6 — honeypot SSH
- Python 3 — análisis automatizado de logs
- Ubuntu Server 26.04 — entorno de despliegue

## Capacidades
- ✅ Captura de sesiones SSH de atacantes
- ✅ Registro de comandos ejecutados con timestamp
- ✅ Captura de descargas maliciosas con hash SHA-256
- ✅ Script de análisis automatizado de logs JSON

## Hallazgo de ejemplo
Sesión de ataque completa capturada desde 192.168.5.45:
- Reconocimiento del sistema (whoami, uname, /etc/passwd)
- Intento de descarga de malware desde http://evil.com/backdoor.sh
- Hash SHA-256 del payload capturado para análisis en VirusTotal
