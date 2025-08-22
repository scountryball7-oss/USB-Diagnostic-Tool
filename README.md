# USB Diagnostic Tool

A simple utility to list removable USB drives, show their capacity and filesystem, and run a quick non-destructive speed test. Includes a Tkinter GUI and a CLI mode.

## Run (Python)
```bash
python usb_diagnostic_tool.py
```

## Build a .exe (Windows, with custom icon)
```bash
pip install pyinstaller
pyinstaller --noconfirm --onefile --windowed --name "USB Diagnostic Tool" --icon icon.ico usb_diagnostic_tool.py
```
The EXE will be in the `dist` folder.

## CLI
```bash
python usb_diagnostic_tool.py --scan
```
