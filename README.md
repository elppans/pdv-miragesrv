# pdv_miragesrv

- Arquivo para SystemD: `/etc/systemd/system/mirage.service`

- Ativar serviço
```bash
systemctl daemon-reload
systemctl enable --now mirage.service
```
- Verificar status
```bash
systemctl status mirage.service
```
