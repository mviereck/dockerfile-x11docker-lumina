# x11docker/lumina

Run [Lumina desktop](https://lumina-desktop.org/) in docker. 
 - Use x11docker to run image. 
 - Get x11docker from github: https://github.com/mviereck/x11docker 

Run desktop with:
```
x11docker --desktop x11docker/lumina
```
Run single application:
```
x11docker x11docker/lumina xterm
```
Options:
- You can add hardware acceleration with option `--gpu`
- You can create a persistent home folder with option `--home`
- You can share clipboard with option `--clipboard`
- You can enable sound with option `--alsa`
- See `x11docker --help` for further options.

![screenshot](https://raw.githubusercontent.com/mviereck/x11docker/screenshots/screenshot-lumina.png "lumina desktop running in a Xephyr window using x11docker")
