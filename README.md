# FSR 3.1 / 4.1 + Frame Gen for X-Plane 12

Public downloads, updates and help. Development source is private.

## Downloads

| Channel | Windows download |
| --- | --- |
| **Betas — latest features, still being tested** | [2.0 Beta 5 installer](https://github.com/cjboy31/xplane12-fsr-framegen/releases/download/v2.0.0-beta.windows.5/XPlane-FSR3-4-FrameGen-2.0.0-beta.windows.5-Setup.exe) · [Notes and checksums](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v2.0.0-beta.windows.5) |
| **Release Candidates — earlier tested baseline** | [0.7.10 installer](https://github.com/cjboy31/xplane12-fsr-framegen/releases/download/v0.7.10/XPlane-FSR3-4-FrameGen-0.7.10-Setup.exe) · [Notes and checksums](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v0.7.10) |

[Experimental Beta: Linux FSR 3.1 and Mac Metal preview 4](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/native-preview-2.0.0-platform-preview.4) · [Platform limits](docs/PLATFORM-STATUS.md)

## Install and open the controls

1. Close X-Plane. Download the Windows installer above and run it.
2. Select your own X-Plane folder. Keep in-sim integration enabled.
3. Start X-Plane normally and load a flight.
4. Open **Plugins > FSR 3.1 / 4.1 + Frame Gen > Open settings**.

The desktop Plugin Updater checks updates. Picture controls are inside X-Plane; FSR follows the simulator's Rendering Resolution slider. Start with NR and frame generation Off, then compare one feature at a time. Read [installation help](docs/INSTALLATION.md) and [hardware/settings guidance](docs/HARDWARE-AND-SETTINGS.md).

**Moving from before v2:** close X-Plane and back up your saved choices and imported models. If removing the old version, use its uninstaller; keep your saved settings and model files. Run the new v2 installer in the same application folder. The old 0.7.x updater cannot find v2 after the repository rename, so this first v2 install is manual. Later updates use the Plugin Updater.

**Beta 5 combines current development in one installer.** It adds selected-channel in-sim update notices, adaptive spare caches, separate instrument-window routing and optional image-motion/NR-reuse/shading/stutter/cache measurement previews. New previews start Off. Independent multi-view FG remains unfinished; new flight/display checks go to community testers. [Read the limits and changes](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v2.0.0-beta.windows.5).

## Included features

- FSR upscaling to build a larger output picture, or native-resolution AA to smooth edges.
- Optional frame generation, frame-pacing choices and a real/generated/total frame counter.
- Optional neural rendering with user-supplied supported models.
- Live supported controls, saved choices, ? help, diagnostics and an in-sim changelog.

NR and frame generation depend on hardware and drivers and can cost performance. Close the settings panel to resume FG. Use one scene processor at a time if Native AA is also installed. No models are supplied.

## Help and licensing

[Join Discord](https://discord.gg/yh396QNgHZ) · [All downloads](https://github.com/cjboy31/xplane12-fsr-framegen/releases) · [Changelog](CHANGELOG.md) · [Licensing](LICENSING.md)

Download the installer or RAR listed under Assets. GitHub's automatic “Source code” archives contain this download page, not the plugin's development source. Previously released packages keep their existing licenses.