# zmk-shield-custom-22

ZMK shield module for a single keyboard half with 11 direct GPIO keys on a Seeeduino XIAO BLE.

Includes a GPIO hog on P0.13 to set the BQ25101 charging current to 100mA.

## Hardware

- **Board:** Seeeduino XIAO BLE (nRF52840)
- **Keys:** 11 direct GPIO inputs on xiao_d pins 0-10
- **Charging:** P0.13 LOW = 100mA (via GPIO hog)

## Usage

Add to your `west.yml` or mount as `ZMK_EXTRA_MODULES`.

Left/right split configuration (col-offset) is applied via user config overlays, not in this shield.
