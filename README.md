### Ludusavi Flatpak Systemd Service

Runs ludusavi's backup every 5 minutes.

Edit the `RestartSec=300s` line to adjust frequency.

### Setup:
Create a folder called ~/.services and copy ludusavi-flatpak.service to ~/.services folder

Then run: 
```
cd ~/.services

systemctl --user enable ./ludusavi-flatpak.service
```
