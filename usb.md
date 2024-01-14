# USB
- USB (Universal Serial Bus) is the most popular connection used to connect a computer to devices such as digital cameras, printers, scanners, and external hard drives. #ref/2023/12/09/124901 #glossary 

Troubleshooting USB:
- Try a shorter cable (spec limits this to 5m)
- Plugging modern devices into legacy versions (e.g. a USB 3.0 disk on a USB 2.0) may give poor performance
- Un-powered hubs (including built-in motherboard root hubs) will only provide 500mA
- Default device drivers for USB devices may not support full functionality - get the manufacturer's drivers where possible
- On Windows, check for `USB Selective Suspend` by changing power plan settings in `Control Panel; System and Security; Power Options; Change Plan Settings; Change advanced power settings; USB Settings`
- Check `Allow the computer to turn off this device to save power` in `Device Manager` if a specific device is not showing up
- Check USB specific BIOS  settings
## My Notes
[Notes](mynotes/usb-notes.md)
