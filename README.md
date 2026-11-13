![W4lterSec — Blue Team | Red Team](banner-w4ltersec.svg)

<h1 align="center">💻 W4lterSec · Blue Team | Red Team</h1>
<p align="center">Ciberseguridad · Laboratorios prácticos · Writeups</p>
<p align="center"><a href="https://w4ltersec.github.io/cybersecurity-labs/red-team/hackmyvm/banner/Banner-Writeup.html"><strong>🌐 Ver Banner</strong></a> &nbsp;·&nbsp; <a href="https://w4ltersec.github.io/cybersecurity-labs/red-team/vulnhub/earth/Earth-Writeup.html"><strong>🌐 Ver Earth</strong></a> &nbsp;·&nbsp; <a href="https://w4ltersec.github.io/cybersecurity-labs/red-team/hackmyvm/aegis/Aegis-Writeup.html"><strong>🌐 Ver Aegis</strong></a> &nbsp;·&nbsp; <a href="https://w4ltersec.github.io/cybersecurity-labs/red-team/hackmyvm/madlabs/MadLabs-Writeup.html"><strong>🌐 Ver MadLabs en formato visual</strong></a> &nbsp;·&nbsp; <a href="https://github.com/W4lterSec/cybersecurity-labs">📂 Explorar mis laboratorios</a></p>

## 👋 Sobre mí

Soy **W4lterSec**. Estoy construyendo mi portfolio de ciberseguridad con laboratorios prácticos y documentación de lo aprendido. Me interesan tanto la defensa como la seguridad ofensiva: entender cómo se produce un ataque ayuda a comprender cómo prevenirlo y detectarlo.

```text
W4lterSec@lab:~$ cat profile.txt

ENFOQUE    Blue Team | Red Team
MÉTODO     Practicar → Investigar → Documentar
PORTFOLIO  Laboratorios y writeups
```

## 📦 Descargas e instalación

### 🍯 T-Pot

Guía en español con descarga desde la fuente oficial, pasos de instalación y cuatro capturas del laboratorio. Repositorio independiente para quien quiera montar su propio entorno.

[**⬇ Abrir T-Pot · Descarga e instalación**](https://github.com/W4lterSec/T-Pot)

### 🛡️ Wazuh

Guía en español para instalar Wazuh, añadir agentes y recorrer el panel con cuatro capturas del laboratorio. Incluye la descarga del asistente oficial.

[**⬇ Abrir Wazuh · Descarga e instalación**](https://github.com/W4lterSec/Wazuh)

## 🛡️ Blue Team & ⚔️ Red Team

| 🔵 Blue Team | 🔴 Red Team |
| :--- | :--- |
| Espacio dedicado a defensa y análisis.<br/>**Proyectos:** [🍯 T-Pot](https://w4ltersec.github.io/cybersecurity-labs/blue-team/t-pot/) · [📊 Splunk](https://github.com/W4lterSec/Splunk)<br/>🌐 Acceso público | Máquinas y laboratorios ofensivos.<br/>**[Banner](https://w4ltersec.github.io/cybersecurity-labs/red-team/hackmyvm/banner/Banner-Writeup.html) · [Earth](https://w4ltersec.github.io/cybersecurity-labs/red-team/vulnhub/earth/Earth-Writeup.html) · [Aegis](https://w4ltersec.github.io/cybersecurity-labs/red-team/hackmyvm/aegis/Aegis-Writeup.html) · [MadLabs](https://w4ltersec.github.io/cybersecurity-labs/red-team/hackmyvm/madlabs/MadLabs-Writeup.html)** |
| Logs, detección y respuesta a incidentes como áreas de aprendizaje | Reconocimiento, acceso inicial y escalada de privilegios |
| [Explorar Blue Team →](https://github.com/W4lterSec/cybersecurity-labs/tree/main/blue-team) | [Explorar Red Team →](https://github.com/W4lterSec/cybersecurity-labs/tree/main/red-team) |

## 🔵 Proyecto Blue Team

### 🍯 T-Pot · Estudio del comportamiento de atacantes

Demostración del mapa de actividad de T-Pot y su registro de eventos. Un proyecto de estudio para observar patrones, reconocer señales de ataque y mejorar la detección temprana y la prevención.

[![T-Pot · Mapa de actividad](https://raw.githubusercontent.com/W4lterSec/cybersecurity-labs/main/blue-team/t-pot/tpot-preview.jpg)](https://w4ltersec.github.io/cybersecurity-labs/blue-team/t-pot/)

[**▶ Reproducir demostración de T-Pot**](https://w4ltersec.github.io/cybersecurity-labs/blue-team/t-pot/) · [Documentación de T-Pot](https://github.com/W4lterSec/cybersecurity-labs/tree/main/blue-team/t-pot)

## 🔬 Laboratorios destacados

### 🏴 Banner · HackMyVM

**Completada hasta root** · Linux / Debian · Red Team

Manipulación de la cookie de puntuación del quiz, recuperación de credenciales en un banner FTP dinámico y acceso SSH. Escalada mediante una configuración de sshd escribible y permiso sudo para reiniciar el servicio.

`quiz web → FTP (111) → SSH (welcome) → root`

[**▶ Abrir writeup visual de Banner**](https://w4ltersec.github.io/cybersecurity-labs/red-team/hackmyvm/banner/Banner-Writeup.html) · [Leer documentación de Banner](https://github.com/W4lterSec/cybersecurity-labs/tree/main/red-team/hackmyvm/banner)

### 🌍 Earth · VulnHub

**Completada hasta root** · Linux / Fedora 34 · Dificultad oficial fácil · Red Team

Enumeración de vhosts mediante TLS, recuperación de una clave XOR con texto plano conocido, ejecución autenticada en Django y escalada por ingeniería inversa de un binario SUID.

`terra (panel) → apache → root`

[**▶ Abrir writeup visual de Earth**](https://w4ltersec.github.io/cybersecurity-labs/red-team/vulnhub/earth/Earth-Writeup.html) · [Leer documentación de Earth](https://github.com/W4lterSec/cybersecurity-labs/tree/main/red-team/vulnhub/earth)

### 🛡️ Aegis · HackMyVM

**Completada hasta root** · Linux · Dificultad media · Red Team

Backup rsync expuesto y secreto HMAC en Git, ejecución de código mediante pickle y escalada a través de un socket IPC y una configuración interpretada con sudo.

`operator → adrian → root`

**Técnicas documentadas:** rsync anónimo · HMAC en Git · deserialización pickle · path traversal IPC · inyección mediante source.

[**▶ Abrir writeup visual de Aegis**](https://w4ltersec.github.io/cybersecurity-labs/red-team/hackmyvm/aegis/Aegis-Writeup.html) · [Leer documentación de Aegis](https://github.com/W4lterSec/cybersecurity-labs/tree/main/red-team/hackmyvm/aegis)

### ⚡ MadLabs · HackMyVM

**Completada hasta root** · Linux · Red Team

Writeup de una cadena de explotación desde una subida de archivos hasta el control de la máquina, con notas sobre los obstáculos encontrados y las medidas de remediación.

`www-data → igor → frankenstein → root`

**Técnicas documentadas:** bypass de subida de archivos · RCE · PATH hijacking · inyección de comandos · clave SSH expuesta.

[**▶ Abrir writeup visual**](https://w4ltersec.github.io/cybersecurity-labs/red-team/hackmyvm/madlabs/MadLabs-Writeup.html) · [Leer documentación](https://github.com/W4lterSec/cybersecurity-labs/tree/main/red-team/hackmyvm/madlabs)

## 🧰 Herramientas presentes en mis writeups

![Linux](https://img.shields.io/badge/Linux-0d1117?style=for-the-badge&logo=linux&logoColor=fcc624)
![Bash](https://img.shields.io/badge/Bash-0d1117?style=for-the-badge&logo=gnubash&logoColor=4ade80)
![Nmap](https://img.shields.io/badge/Nmap-0d1117?style=for-the-badge&labelColor=075985&color=075985)
![curl](https://img.shields.io/badge/curl-0d1117?style=for-the-badge&logo=curl&logoColor=38bdf8)
![SSH](https://img.shields.io/badge/SSH-0d1117?style=for-the-badge&color=9f1239)

## 📚 Mi forma de trabajar

- Practicar en entornos de laboratorio autorizados.
- Documentar los pasos, las evidencias y las lecciones aprendidas.
- Conectar cada fallo con su posible remediación.
- Mantener Red Team y Blue Team organizados por separado.

---

<p align="center"><strong>Aprender. Investigar. Documentar.</strong><br/>🔵 Blue Team &nbsp;|&nbsp; 🔴 Red Team</p>


