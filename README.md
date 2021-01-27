# groot

A simple tiling window manager for Windows, written in Rust. Inspired by Budgie Window Shuffler's grid functionality. Currently only tested on a single monitor.

## Download

- Download executable from [latest release](https://github.com/wgalyen/groot/releases/latest)

## Usage

- Run `groot.exe` or `cargo run`. Program will run in the background.
- Activate the windowing grid with hotkey `CRTL + ALT + S`.
- Increase / decrease grid rows / columns with `CTRL + arrows`.
- Hovering cursor over the grid will show a preview of that zone in the window.
- Select a window you want resized, then click on a tile in the grid. Window will resize to that zone.
- Hold `SHIFT` down while hovering after a selection, zone will increase in size across all tiles. Select again to resize to larger zone.

## TODO

- Multi-monitor support
- System tray icon
- Settings window to edit hotkey & margin config
- Option to autostart