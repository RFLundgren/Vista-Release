# Vista Capture

Vista Capture is a lightweight, portable screenshot and annotation application for Windows. It runs without installation and is available for both x64 and ARM64 systems.

## Download

Download the latest portable build from the [Releases page](https://github.com/RFLundgren/Vista-Release/releases/latest):

- **x64 EXE**: for most Windows PCs using Intel or AMD processors; run it directly.
- **ARM64 ZIP**: for Windows PCs using an ARM processor, including supported Snapdragon devices; extract the complete folder, then run Vista Capture.exe.

If you are unsure, open **Settings > System > About** in Windows and check **System type**.

## Using Vista Capture

1. Download the build that matches your computer.
2. For x64, place the executable in your preferred folder. For ARM64, extract the complete ZIP to that folder.
3. Run the x64 executable or Vista Capture.exe inside the extracted ARM64 folder. No installer or administrator access is normally required.
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
- Configurable global shortcuts and PrintScreen support where Windows and keyboard firmware permit it.
- Automatic clipboard copying after capture and editing.
- Annotation tools for highlights, circles, text, crop, arrows, numbered steps, blur, and pixelation.
- Undo, redo, individual saving, bulk saving, and Menu-based multi-select actions.
- PNG and JPEG export options.
- Optional automatic saving with configurable filename templates.
- Optional local capture history with count, size, and age limits.
- Resizable always-on-top pinned references with opacity control.
- Preferred monitor selection for full-screen captures.
- Optional privacy-conscious update checks.
- Drag captures directly into Explorer and compatible applications.
- Optional portable data mode stores settings and history in a VistaData folder beside the executable.
- Optional Stripe support links with locally controlled reminders.
- Light, dark, and follow-system appearance modes.
- Comprehensive Help, Release Notes, and Roadmap windows inside the application.

## Portable Data and Privacy

Vista Capture works locally and does not require an account or cloud service. Screenshots are not uploaded by the application. Preferences and any capture history you explicitly enable are stored in your Windows user profile.

To update, quit Vista Capture from its notification-area icon. Replace the x64 executable, or replace the extracted ARM64 application folder, then start the new build.

## Windows Security Notice

The portable builds are currently unsigned. Windows SmartScreen may therefore display an **Unknown publisher** warning. Download Vista Capture only from this repository's official Releases page.

## Current Version

**Vista Capture v1.6.1**

### Highlights

- Configurable Draw Area overlay hue and opacity with persistent preferences.
- Reliable left/right Ctrl, Shift, and Alt handling in the native shortcut helper.
- Non-blocking native hook diagnostics and stale modifier-key reconciliation.
- Faster Window and Dialog pickers using lightweight previews without reducing final capture resolution.
- Defensive overlay colour validation and expanded regression coverage.

### SHA-256 Checksums

- `Vista Capture-1.6.1-x64-portable.exe`: `493454B665BC7FA6ECDF53F1C8AE7683254C822C334D9B3B36DC0D2EB79C2B17`
- `Vista Capture-1.6.1-arm64-win.zip`: `42F54D2D8109F746762945DAC3562C2269CA80A6FD7C3668194B5EE162A55B63`
