# Vista Capture

Vista Capture is a lightweight, portable screenshot and annotation application for Windows. It runs without installation and is available for both x64 and ARM64 systems.

## Download

Download the latest portable build from the [Releases page](https://github.com/RFLundgren/Vista-Release/releases/latest):

- **x64 EXE**: for most Windows PCs using Intel or AMD processors; run it directly.
- **ARM64 portable EXE**: single-file option for Windows PCs using an ARM processor, including supported Snapdragon devices.
- **ARM64 ZIP**: alternative folder-based build; extract the complete folder, then run Vista Capture.exe.

If you are unsure, open **Settings > System > About** in Windows and check **System type**.

## Using Vista Capture

1. Download the build that matches your computer.
2. Place either portable executable in your preferred folder, or extract the complete ARM64 ZIP to that folder.
3. Run the portable executable or Vista Capture.exe inside the extracted ARM64 folder. No installer or administrator access is normally required.
4. Use **Menu > Settings** to choose a default capture mode and configure global shortcuts.

Vista Capture can capture an entire display, a window, a dialog, or an area drawn with the mouse. New captures are copied automatically to the Windows clipboard and held on a compact shelf for quick reuse.

## Screenshots

<table>
  <tr>
    <td align="center"><img src="screenshots/main%20window%20light.png" alt="Vista Capture compact window in light mode" width="230"><br><sub>Compact window - light</sub></td>
    <td align="center"><img src="screenshots/main%20window%20dark.png" alt="Vista Capture compact window in dark mode" width="230"><br><sub>Compact window - dark</sub></td>
    <td align="center"><img src="screenshots/menu.png" alt="Vista Capture application menu" width="230"><br><sub>Application menu</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="screenshots/capture.png" alt="Vista Capture annotation window" width="360"><br><sub>Capture editor</sub></td>
    <td align="center"><img src="screenshots/settings.png" alt="Vista Capture settings" width="360"><br><sub>Settings</sub></td>
    <td align="center"><img src="screenshots/help.png" alt="Vista Capture comprehensive help" width="360"><br><sub>Help</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="screenshots/text.png" alt="Adding text to a Vista Capture screenshot" width="360"><br><sub>Text annotation</sub></td>
    <td align="center"><img src="screenshots/blur.png" alt="Blurring information in Vista Capture" width="360"><br><sub>Blur tool</sub></td>
    <td align="center"><img src="screenshots/pixelate.png" alt="Pixelating information in Vista Capture" width="360"><br><sub>Pixelate tool</sub></td>
  </tr>
</table>

## Features

- Portable Windows application with no installation required.
- Native x64 and ARM64 builds.
- Entire-screen, window, dialog, and drawn-area capture modes.
- Configurable Draw Area overlay with preset or custom colours, adjustable opacity, live preview, and pixel-safe isolation.
- A dock icon toggle arms and disarms delayed capture in one click, remembers the last duration used, and by default automatically returns to instant after one delayed capture.
- Configurable global shortcuts and PrintScreen support where Windows and keyboard firmware permit it.
- Automatic clipboard copying after capture and editing.
- Annotation tools for highlights, circles, text, crop, arrows, numbered steps, blur, and pixelation.
- Undo, redo, individual saving, bulk saving, Menu-based multi-select actions, and a per-thumbnail close button to remove a single capture from the shelf.
- PNG and JPEG export options.
- Optional automatic saving with configurable filename templates.
- Optional local capture history with count, size, and age limits.
- Resizable always-on-top pinned references with opacity control.
- Preferred monitor selection for full-screen captures.
- Optional privacy-conscious update checks.
- Drag captures directly into Explorer and compatible applications.
- Optional portable data mode stores settings and history in a VistaData folder beside the executable.
- Closing the dock window sends it to the system tray instead of quitting, matching minimize; use the tray menu's Quit command to fully close Vista Capture.
- Optional Stripe support links with locally controlled reminders.
- Light, dark, and follow-system appearance modes.
- Comprehensive Help, Release Notes, and Roadmap windows inside the application.

## Portable Data and Privacy

Vista Capture works locally and does not require an account or cloud service. Screenshots are not uploaded by the application. Preferences and any capture history you explicitly enable are stored in your Windows user profile.

To update, quit Vista Capture using the tray menu's **Quit** command (closing the dock window alone sends it to the tray rather than exiting). Replace the portable executable, or replace the extracted ARM64 application folder, then start the new build.

## Windows Security Notice

The portable builds are currently unsigned. Windows SmartScreen may therefore display an **Unknown publisher** warning. Download Vista Capture only from this repository's official Releases page.

## Current Version

**Vista Capture v1.6.6**

### Highlights

- A dock icon toggle arms and disarms delayed capture in one click without opening Settings, remembers the last duration used, and offers 3, 5, or 10 seconds from a small popover. It defaults to automatically returning to instant after one delayed capture; Settings can keep it on instead.
- Closing the dock window now sends it to the system tray instead of quitting, matching minimize. The tray menu's Quit command still fully exits.
- Save All and Clear All sit side by side in the docked shelf toolbar, and each capture shelf thumbnail has a close button to remove a single capture without entering multi-select mode.
- The portable launcher's self-extraction folder is now pinned to a fixed name, so relaunching no longer accumulates duplicate tray icons under Windows Settings > Other system tray icons.
- New captures appear on the shelf before clipboard conversion and background processing begins, so the workflow no longer waits on notifications, export caching, or persistence.

### SHA-256 Checksums

- `Vista Capture-1.6.6-x64-portable.exe`: `F90D856C346AD63F6E0282DE8C3F48F3A87A4783BF90BE20CE42D0126E36571F`
- `Vista Capture-1.6.6-arm64-portable.exe`: `C9875990C14BBF2C2DE2B27E6C6A02824EF68418C1ADAE7C0CAA71A1689506B5`
- `Vista Capture-1.6.6-arm64-win.zip`: `C90AB2812031BD2AE7A8A16B3216C1D5B5719BD01FA0E2CE9D6D742AB47DFF44`
