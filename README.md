<p align="center">
  <img src="logo/logo.svg" width="112" alt="Logo: las letras T y P con un LED encendido">
</p>

<h1 align="center">Tito Pinardo Gutiérrez</h1>

<p align="center">
  <b>Administración de Sistemas · Infraestructura como Código · DevOps</b><br>
  Alcalá de Henares, Madrid · <a href="https://titopinardogutierrez.com/es/">titopinardogutierrez.com</a> ·
  <a href="https://www.linkedin.com/in/tito-pinardo-gutierrez-b7341b293">LinkedIn</a>
</p>

Técnico Superior en ASIR + DAW. Gestiono infraestructura real con Terraform y
Ansible, despliego con Kubernetes y GitOps, y me obsesiona entender por qué
falla algo antes de arreglarlo.

## Lo que hay aquí

| Repo | Qué es |
|---|---|
| [**homelab-infra**](https://github.com/Tito-Pinardo/homelab-infra) | Mi homelab entero como código: Terraform crea los contenedores de Proxmox y Ansible los configura (red, DNS, proxy inverso, copias cifradas, monitorización, secretos en OpenBao y CI/CD). Es la copia pública y saneada; se publica sola tras cada cambio. |
| [**landing**](https://github.com/Tito-Pinardo/landing) | [Mi web](https://titopinardogutierrez.com/es/): un servidor en Rust (Axum + PostgreSQL) con una sala de servidores en 3D. Cada unidad del rack cuenta por dentro una parte del homelab, con sus averías reales. Aquí solo llega lo que ya está desplegado. |

El origen de todo vive en casa, en mi propio **GitLab CE**: CI en cada push en
un runner sin secretos, cambios de infraestructura por MR con el plan a la
vista, despliegue con un clic y agentes IA que trabajan desde las issues (y
cuyas MR reviso yo). Lo que se va subiendo, en
[titopinardogutierrez.com/es/repos](https://titopinardogutierrez.com/es/repos/).

**Con qué trabajo:** Proxmox · LXC · ZFS · Terraform · Ansible · GitLab CI ·
Kubernetes · Argo CD · Rust · PostgreSQL · Traefik · OpenBao · Wazuh · Zabbix ·
MikroTik · WireGuard

---

<sub>🇬🇧 Systems administration, infrastructure as code and DevOps (ASIR + DAW).
I run real infrastructure at home as code. More on
[my site](https://titopinardogutierrez.com/en/).</sub>
