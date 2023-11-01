# Teams

## Debian, Ubuntu, Kali

* kali-rolling, jammy, focal
* bookworm, bullseye

### Install

```
cat teams-debian-bookworm.tgz.split-* > teams-debian-bookworm.tgz

tar xf teams-debian-bookworm.tgz
sudo cp -r usr/share/teams /usr/share/
sudo chmod -R go+rX /usr/share/teams
sudo cp usr/bin/teams /usr/bin/
sudo chmod go+rX /usr/bin/teams
rm -fr usr teams-debian-bookworm.tgz

sudo cp teams.desktop /usr/share/applications/
sudo chmod go+r /usr/share/applications/teams.desktop
sudo cp teams.png /usr/share/pixmaps/
sudo chmod go+r /usr/share/pixmaps/teams.png
```
