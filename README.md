# Aerolux for X-Plane 12

FSR, Native AA and optional frame generation in one in-sim panel. Public downloads and help; development source is private.

## Downloads

| Channel | Windows download |
| --- | --- |
| **Betas — latest features, still being tested** | [Aerolux 2.0 Beta 8 installer](https://github.com/cjboy31/xplane12-fsr-framegen/releases/download/v2.0.0-beta.windows.8/XPlane-FSR3-4-FrameGen-2.0.0-beta.windows.8-Setup.exe) · [Notes and checksums](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v2.0.0-beta.windows.8) |
| **Release Candidates — earlier tested baseline** | [0.7.10 installer](https://github.com/cjboy31/xplane12-fsr-framegen/releases/download/v0.7.10/XPlane-FSR3-4-FrameGen-0.7.10-Setup.exe) · [Notes and checksums](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v0.7.10) |

[Experimental Linux FSR 3.1 and Mac Metal preview 4](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/native-preview-2.0.0-platform-preview.4) · [Platform limits](docs/PLATFORM-STATUS.md). These keep their separate features; the Windows update does not replace them.

## Start here

1. Close X-Plane and run the installer. Select your X-Plane folder. Keep the existing app folder when updating.
2. Start X-Plane normally and load a flight.
3. Open **Plugins > Aerolux > Open settings**.
4. Choose **Pure** to smooth edges at Full resolution, **Boost** for FSR, or **Original** for X-Plane's own picture. Restart when asked.
5. Begin with NR, frame generation and Beta previews Off. Compare one change at a time. Hover over **?** for help.

Boost starts with FSR 3.1.6 and follows X-Plane's Rendering Resolution slider. Pure includes SMAA, FXAA, CMAA 2 and experimental temporal methods such as TAA + SMAA. Look adds optional sharpening and colour adjustments. Diagnostics has the raw/generated/total frame counter, current logs and report tools. Read the [installation guide](docs/INSTALLATION.md).

**Moving from FSR v2:** this is a normal Beta update. Saved choices and local models are kept. **Moving from separate Native AA:** run this installer once; setup imports its settings and removes only unchanged owned files. Edited files are protected. **Moving from FSR 0.7.x:** run the new installer once because the old updater cannot find v2 after the repository rename.

**Beta 8:** adds Aerolux Manager, settings backups, local health reports and matching icons. Native AA is Pure inside Aerolux; its separate updater is retired. [Previous Beta 7](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v2.0.0-beta.windows.7) stays available.

## Features and limits

- Pure and Boost can use optional frame generation and neural rendering on supported hardware. NR needs your own supported model; no NVIDIA DLL or model weights are supplied.
- New previews, including the own FSR 3 build, start Off. Temporal AA, XeSS and other previews still need community testing.
- In-sim update notices follow your selected channel. Close X-Plane before installing. Aerolux Manager lists your simulator copies, installs and repairs the mod, saves settings backups and shows what changed before an update. Health reports stay on your PC.
- Separate instrument windows keep native frames; FG for multiple independent 3D views remains unfinished. NR and FG can cost performance. No setting guarantees more FPS or removes every artifact.
- Windows automated checks and limited live checks on one PC do not prove compatibility with every aircraft, graphics card or display. FSR 4.1.2 has separate runtime compatibility limits; use FSR 3.1.6 if it fails.

## Help and licensing

[Join Discord](https://discord.gg/yh396QNgHZ) · [All downloads](https://github.com/cjboy31/xplane12-fsr-framegen/releases) · [Changelog](CHANGELOG.md) · [Licensing](LICENSING.md)

Download the installer or RAR under Assets. GitHub's automatic “Source code” archives contain this download page, not the plugin's development source. Earlier releases and required third-party notices keep their licenses.

