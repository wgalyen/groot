# groot
![Rust](https://github.com/wgalyen/groot/workflows/Rust/badge.svg)

A simple tiling window manager for Windows, written in Rust. Inspired by Budgie's Window Shuffler grid functionality.

- [Demo](#demo)
- [Download](#download)
- [Usage](#usage)
- [Config](#config)
- [TODO](#todo)

## Download

- Download executable from [latest release](https://github.com/wgalyen/groot/releases/latest)

## Usage

-- Run `groot.exe` or `cargo run`. Program will run in the background and options can be accessed by right clicking the system tray icon.
- Activate the windowing grid with hotkey `CRTL + ALT + S`.
- Increase / decrease grid rows / columns with `CTRL + arrows`.
- Hovering cursor over the grid will show a preview of that zone in the window.
- Select a window you want resized, then click on a tile in the grid. Window will resize to that zone.
- Hold `SHIFT` down while hovering after a selection, zone will increase in size across all tiles. Select again to resize to larger zone.
- Resizing can also be achieved by click-drag-release. Click & hold cursor down, drag cursor across multiple tiles and release to make selection.

## Config

See [example config](https://github.com/wgalyen/groot/wiki/Example-Config) in the wiki for a full list of all options.

- A configuration file will be created at `%APPDATA%\groot\config.yml` that can be customized. You can also open the config file from the system tray icon.

## TODO

- Option to autostart
- Switchable "profiles" via F-keys