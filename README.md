# XFWM-Arc-Dark-Slim

A minimalist Arc Dark variant for the XFCE window manager (XFWM4), manually modified by William Barrera.  
Removes window titlebar and buttons, with a solid 4-pixel border for easy resizing and clean aesthetics.

## Preview

<p align="center">
  <img src="preview.png" alt="Preview of xfwm-arc-dark-slim" width="340">
</p>

## Installation

1. Clone or download this repository.

2. Copy the theme folder into your local themes directory:

   ```bash
   mkdir -p ~/.themes
   cp -r xfwm-arc-dark-slim ~/.themes/
    ```
3. Apply the theme using the command line:
    ```bash
    xfconf-query -c xfwm4 -p /general/theme -s "xfwm-arc-dark-slim"
    ```
    Or use the graphical interface:
    ```
    Settings > Window Manager > Style
    ```
    Then select xfwm-arc-dark-slim.

## Included

- `xfwm-arc-dark-slim/xfwm4/` - modified XFWM4 theme files.
- `preview.png` - screenshot showing the theme in use.

## Based on
- Arc Theme (XFWM4 variant): https://github.com/horst3180/arc-theme
- Inspired by onepx: https://github.com/superjamie/onepx

## Author

William Barrera
Manual modification and adaptation for XFWM4.

## License
This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).
Based on Arc (GPL-3.0). Inspired by onepx (CC0).
