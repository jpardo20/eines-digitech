# eines-digitech

----

## Instal·lació git

----

## Instal·lació Visual Studio Code

----

## Instal·lació Virtual Box

[VC_redist.x64.exe](https://aka.ms/vs/17/release/vc_redist.x64.exe)

[VirtualBox-7.2.2-170484-Win.exe](https://download.virtualbox.org/virtualbox/7.2.2/VirtualBox-7.2.2-170484-Win.exe)

----

## Instal·lació Docker

# 1) Paquets
```bash
sudo apt-get update
sudo apt-get install -y ca-certificates curl gnupg
```

# 2) Clau i repo Docker

```bash
sudo install -m 0755 -d /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] \
  https://download.docker.com/linux/ubuntu $(. /etc/os-release; echo $UBUNTU_CODENAME) stable" \
  | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```

# 3) Instal·la i habilita

```bash
sudo apt-get update
sudo apt-get install -y docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```

# 4) Executar sense sudo

```bash
sudo usermod -aG docker "$USER"
```

# (Tancar sessió i tornar a entrar)

----

### Alpine distribution

* Similar to standard. Slimmed down kernel. Optimized for virtual systems.
* Current Alpine Version 3.22.1 (Released Jul 15, 2025)

[alpine-virt-3.22.1-x86_64.iso](https://dl-cdn.alpinelinux.org/alpine/v3.22/releases/x86_64/alpine-virt-3.22.1-x86_64.iso)

----

### Apache OpenOffice 4.1.15

[Descargar Apache OpenOffice](https://sourceforge.net/projects/openofficeorg.mirror/files/4.1.15/binaries/es/Apache_OpenOffice_4.1.15_Win_x86_install_es.exe/download)

----

### Descargar Cisco Packet Tracer
Para obtener e instalar su copia de Cisco Packet Tracer, siga las instrucciones del siguiente enlace: [Cisco Packet Tracer](https://www.netacad.com/resources/lab-downloads)


### Python

[python.org](https://www.python.org/)

[Python Releases for Windows](https://www.python.org/downloads/windows/)

[Latest Python 3 Release - Python 3.13.7 (python-3.13.7-amd64.exe)](https://www.python.org/ftp/python/3.13.7/python-3.13.7-amd64.exe)

[Python Tutorial (w3schools.com)](https://www.w3schools.com/python/default.asp)

[Python 3.13.7 online documentation](https://docs.python.org/3/)

### 0221 — Muntatge i Manteniment d’Equips

[fp_smx_m01_material_paper.pdf](./docs/fp_smx_m01_material_paper.pdf)

[montaje-y-mantenimiento-de-equipos-2012.pdf](./docs/montaje-y-mantenimiento-de-equipos-2012.pdf)

[SMX-Montaje-y-mantenimiento-de-equipos-Editex.pdf](./docs/SMX-Montaje-y-mantenimiento-de-equipos-Editex.pdf)

[Muntatge i Manteniment d’Equips](https://jpardo20.github.io/mme-apunts-recu/)