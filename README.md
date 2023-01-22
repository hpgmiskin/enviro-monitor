# enviro-monitor

Basic Python environment monitor using Enviro+ Air Quality Monitor

## Balena Device Configuration

For the Enviro+ sensor to work there are some customer dtparam and dtoverlay settings.

| Field                       | Value                                         |
| --------------------------- | --------------------------------------------- |
| RESIN_HOST_CONFIG_dtparam   | "i2c_arm=on","spi=on","audio=on","serial=off" |
| RESIN_HOST_CONFIG_dtoverlay | "pi3-miniuart-bt"                             |