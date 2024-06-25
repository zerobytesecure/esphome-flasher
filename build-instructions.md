# macOS

`pyinstaller -F -w -n ESPHome-Flasher -i icon.icns esphomeflasher/__main__.py`

# Windows

1. Start up VM
2. Install Python (3) from App Store
3. Download esphome-flasher from GitHub
4. `pip install -e.` and `pip install pyinstaller`
5. Check with `python -m esphomeflasher.__main__`
6. `python -m PyInstaller.__main__ -F -w -n ESPHome-Flasher -i icon.ico esphomeflasher\__main__.py`
7. Go to `dist` folder, check ESPHome-Flasher.exe works.
