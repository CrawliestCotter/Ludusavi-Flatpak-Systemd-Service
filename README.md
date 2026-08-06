### Ludusavi Flatpak Systemd Service

Runs ludusavi's backup every 5 minutes.

Edit the `RestartSec=300s` line to adjust frequency.

### Setup:

Copy ludusavi-flatpak.service to ~/.config/systemd/user folder

Then run: 
```
cd ~/.config/systemd/user

systemctl --user enable ./ludusavi-flatpak.service
```
