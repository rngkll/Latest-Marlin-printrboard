# Latest-Marlin-printrboard

## Clonar la última version de Marlin

Al día de hoy 20210521 es el branch 2.0.x

```
git clone https://github.com/MarlinFirmware/Marlin.git
```

```
git checkout 2.0.x
```

## Como usar dfu-programmer

Estando en el path del repositorio de Marlin

``` bash
sudo dfu-programmer at90usb1286 get
sudo dfu-programmer at90usb1286 erase --debug 3
sudo dfu-programmer at90usb1286 flash ./.pio/build/at90usb1286_dfu/firmware.hex --debug 3
```
