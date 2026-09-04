# Light Painting Stick v2.0.3

Browser-based firmware installer for the **Light Painting Stick** project.

## 🚀 Flash Firmware

Flash the Light Painting Stick firmware directly from a supported web browser without installing desktop flashing software.

**[Open the Light Painting Stick Web Flasher](https://richardtruong0123.github.io/LightPaintingStick-WebFlasher/)**

> **Recommended:** Use the latest desktop version of Google Chrome or Microsoft Edge with a USB data cable.

## 💻 Source Code

The complete Light Painting Stick firmware source code is available on GitHub.

**[View the Light Painting Stick Source Code](https://github.com/RichardTruong0123/LightPaintingStick)**

## Supported Hardware

- **Board:** Waveshare ESP32-S3-Touch-LCD-2
- **Chip:** ESP32-S3
- **Project:** Light Painting Stick
- **Creator:** Richard Truong

## Before Flashing

1. Connect the ESP32-S3 board using a USB **data** cable.
2. Close Arduino Serial Monitor, PlatformIO, PuTTY, or other programs using the serial port.
3. Open the Web Flasher using the button above.
4. Click **Flash Firmware**.
5. Select the ESP32-S3 serial device.
6. Follow the on-screen instructions.

If the board is not detected, try another USB data cable or USB port and, if necessary, manually enter ESP32-S3 bootloader mode using the board's **BOOT** and **RESET** controls.

## Browser Requirements

The Web Flasher uses **Web Serial** and requires a supported browser and secure HTTPS connection.

Recommended:

- Google Chrome — desktop
- Microsoft Edge — desktop

The Web Flasher is hosted securely through GitHub Pages.

## Troubleshooting

If the Web Flasher reports **Failed to download manifest**:

- Verify the Web Flasher page is accessible.
- Verify the manifest is available at:
  `https://richardtruong0123.github.io/LightPaintingStick-WebFlasher/manifest.json`
- Check that the firmware files are accessible from their expected paths.
- Try a hard refresh or an incognito/private browser window.

If the ESP32-S3 does not appear:

- Make sure the USB cable supports data.
- Close all serial-monitor applications.
- Try another USB port.
- Check Windows Device Manager.
- Try manually entering bootloader mode.

## Web Flasher

**[Open Web Flasher →](https://richardtruong0123.github.io/LightPaintingStick-WebFlasher/)**

## Source Code

**[Open Source Code Repository →](https://github.com/RichardTruong0123/LightPaintingStick)**

---

© 2026 Richard Truong — Light Painting Stick
