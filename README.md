# Teams

## Debian, Ubuntu, Kali

* kali-rolling, jammy, focal
* bookworm, bullseye

### Install

```
cat teams-debian-bookworm.tgz.split-* > teams-debian-bookworm.tgz

tar xf teams-debian-bookworm.tgz
sudo mv usr/share/teams /usr/share
sudo mv usr/bin/teams /usr/bin
rm -fr usr teams-debian-bookworm.tgz
```
