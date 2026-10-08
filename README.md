# PCMote para Linux

Agente de PCMote para Linux (servicio systemd). Descarga el paquete desde **Releases**:

```sh
tar xzf pcmote-linux-X.Y.Z.tar.gz
cd pcmote-linux-X.Y.Z
sudo ./install.sh
sudo pcmote-ctl login
```

Requisitos: una distribucion con systemd y Python 3.6+. Cada release incluye su firma `.sig` (Ed25519) para verificar la autenticidad;
`sudo pcmote-ctl update` la comprueba automaticamente antes de instalar.

# PCMote for Linux

PCMote agent for Linux (systemd service). Download the package from **Releases** and follow the commands above.
Requires a systemd distribution and Python 3.6+. Every release ships a `.sig` (Ed25519) signature; `sudo pcmote-ctl update` verifies it before installing.

(c) CRONOSF DEV. Todos los derechos reservados / All rights reserved.
