
# RetroArch_LRS (Light sensor ready Android Fork)

This custom fork includes specialized enhancements for Android:
- **Native Ambient Light Sensor Support**: Integrates Android's `SensorManager` (`Sensor.TYPE_LIGHT`) to automatically drive solar sensor games like *Boktai*.
- **Ozone Menu Default**: Configured with the Ozone menu driver and visible Quit button out-of-the-box.
- **Optimized Storage Directory**: Defaults the file browser content directory to internal storage (`/storage/emulated/0`).
- **Game Boy Camera Integration**: Full Android camera permission and driver support for *Game Boy Camera*.
- **Stability Fixes**: Robust null pointer safety checks in save/autosave infrastructure.
