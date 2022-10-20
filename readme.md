# Autostart electron application on linux Ubuntu

## Navigate to autostart
```sh
$ cd /etc/xdg/autostart
```

## Create new file
```sh
$ sudo nano electronapp.desktop
```

## Fill this text
```
[Desktop Entry]
Name=Electron
Exec=npm start --prefix /home/ady/electronapp
Terminal=false
Type=Application
```

> Don't forget to change name and application directory 
