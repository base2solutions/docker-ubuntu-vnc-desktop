docker-ubuntu-vnc-desktop
=========================


Build yourself
```
git clone https://github.com/mbrewster/docker-ubuntu-vnc-desktop.git
docker build --rm -t mbrewster/ubuntu-desktop-lxde-vnc docker-ubuntu-vnc-desktop
```

Run
```
docker run -i -t -p 6080:6080 mbrewster/ubuntu-desktop-lxde-vnc
```

Browse http://127.0.0.1:6080/vnc.html

<img src="https://raw.github.com/fcwu/docker-ubuntu-vnc-desktop/master/screenshots/lxde.png" width=400/>


Trobleshooting
==================

1. boot2docker connection issue, https://github.com/fcwu/docker-ubuntu-vnc-desktop/issues/2
