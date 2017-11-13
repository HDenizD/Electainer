# Electainer
Its just a simply Portainer App combined with the Power of Electron.

---Made for Linux---

# Pre-Install
- Download and install Docker
- open terminal and paste 

`docker run -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer`

https://portainer.io/install.html

# Install Electainer

- I recomend to `mv` Electainer-linux-x64 into /opt folder inside root

`sudo mv Electainer/release-builds/Electainer-linux-x64 /opt`



# To make a launcher shortcut just Copy&Paste this into:

`sudo gedit /usr/share/applications/electainer.desktop`

```
[Desktop Entry]
Name=Electainer
Comment=Docker-GUI
Exec=/opt/Electainer-linux-x64/Electainer
Icon=/opt/Electainer-linux-x64/docker_icon.png
Terminal=false
Type=Application
StartupNotify=true
```
