# Vista Capture

Vista Capture is a lightweight, portable screenshot and annotation application for Windows. It runs without installation and is available for both x64 and ARM64 systems. An optional per-user installer is also available for anyone who prefers a conventional setup.

## Download

Download the latest build from the [Releases page](https://github.com/RFLundgren/Vista-Release/releases/latest):

- **x64 portable EXE**: for most Windows PCs using Intel or AMD processors; run it directly, no installation.
- **x64 installer EXE**: optional conventional setup with a Start Menu shortcut and uninstaller. Installs to your user profile only; no administrator access required.
- **ARM64 portable EXE**: single-file portable option for Windows PCs using an ARM processor, including supported Snapdragon devices.
- **ARM64 installer EXE**: optional conventional setup for ARM64, with the same no-administrator, per-user install as the x64 installer.
- **ARM64 ZIP**: alternative folder-based portable build; extract the complete folder, then run Vista Capture.exe.

If you are unsure, open **Settings > System > About** in Windows and check **System type**.

## Using Vista Capture

1. Download the build that matches your computer.
2. **Portable:** place the portable executable in your preferred folder, or extract the complete ARM64 ZIP to that folder, then run it directly. **Installer:** run the setup EXE; it installs to your user profile only and adds a Start Menu and desktop shortcut. Neither option requires administrator access.
3. Use **Menu > Settings** to choose a default capture mode and configure global shortcuts.

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

- Portable Windows application with no installation required, or an optional per-user installer for a conventional setup.
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
- Closing the dock window sends it to the system tray instead of quitting, matching minimize; use the tray menu's Quit command to fully close Vista Capture. The dock also reappears automatically after a capture completes if it was hidden.
- A Settings option keeps the dock window on top of others or lets it behave like a normal window.
- Optional Stripe support links with locally controlled reminders.
- Light, dark, and follow-system appearance modes.
- Comprehensive Help, Release Notes, and Roadmap windows inside the application.

## Portable Data and Privacy

Vista Capture works locally and does not require an account or cloud service. Screenshots are not uploaded by the application. Preferences and any capture history you explicitly enable are stored in your Windows user profile in either distribution.

**Portable:** to update, quit Vista Capture using the tray menu's **Quit** command (closing the dock window alone sends it to the tray rather than exiting). Replace the portable executable, or replace the extracted ARM64 application folder, then start the new build.

**Installer:** run the new version's installer over the existing install to update in place, or use Windows' **Apps & Features** to uninstall.

## Windows Security Notice

The portable and installer builds are currently unsigned. Windows SmartScreen may therefore display an **Unknown publisher** warning. Download Vista Capture only from this repository's official Releases page.

## Current Version

**Vista Capture v1.6.8**

### Highlights

- Added a Settings option (Appearance > Window layering) to keep the dock on top of other windows or let it behave like a normal window, replacing the previous unconditional always-on-top behaviour.
- The dock now restores automatically after a capture completes or is cancelled, even if it was hidden in the tray beforehand, so the shelf is visible without a manual restore.
- Added optional per-user installer builds for x64 and arm64 alongside the existing portable executables. The installer requires no administrator access, installs to the current user's profile, and adds a Start Menu and desktop shortcut with a standard uninstaller. The portable build remains the primary, recommended download.
- A dock icon toggle arms and disarms delayed capture in one click without opening Settings, remembers the last duration used, and offers 3, 5, or 10 seconds from a small popover. It defaults to automatically returning to instant after one delayed capture; Settings can keep it on instead.
- Each capture shelf thumbnail now has a close button to remove a single capture without entering multi-select mode.

### SHA-256 Checksums

- `Vista Capture-1.6.8-x64-portable.exe`: `1AC13222175439B338B8F85F87F2DEA855328D5FD1517832C2402C5115F9C665`
- `Vista Capture-1.6.8-x64-setup.exe`: `A6E08CC3C3E99531C0F6448734FB0CCDC040B98D4F1213FA674C326B204895A5`
- `Vista Capture-1.6.8-arm64-portable.exe`: `CDDC9A1F6D12AD1832262C6AB199E859AAC0D71F0C88E2F3E097A34516B1515F`
- `Vista Capture-1.6.8-arm64-setup.exe`: `5481024766472A021AE4E5E1C8D7074A71F2075911EB181AE4208647EA93C1A9`
- `Vista Capture-1.6.8-arm64-win.zip`: `6A41BD930677B2D2D0FCB61C9114519E2C84F55E8A2E463A700AA0C05978A6D3`
