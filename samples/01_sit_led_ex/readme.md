## usage
```bash
west build -t guiconfig
west build -b decawave_dwm1001_dev -- -DCONF_FILE=prj.conf
west flash
```
## Usage on vscode 
Select the target as `decawave_dwm3001cdk/nrf52833`, then build and flash: