# Aerolux for X-Plane 12

Pure anti-aliasing, Boost upscaling and optional frame generation in one in-sim panel. Public downloads and help; development source is private.

## Download for Windows

**[Download Aerolux 2.0 Release Candidate 2](https://github.com/cjboy31/xplane12-fsr-framegen/releases/download/v2.0.0-rc.2/XPlane-FSR3-4-FrameGen-2.0.0-rc.2-Setup.exe)** · [Changes, instructions and checksums](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v2.0.0-rc.2)

RC2 includes the neural-rendering shader correction and camera-update recovery. This is a Release Candidate for final checks, not a final release. GitHub's Pre-release badge does not mean you need the Betas channel. Choose **Release Candidates** in Aerolux Manager.

## Optional Windows Beta

**[Download Aerolux 2.1 Beta 1](https://github.com/cjboy31/xplane12-fsr-framegen/releases/download/v2.1.0-beta.windows.1/XPlane-FSR3-4-FrameGen-2.1.0-beta.windows.1-Setup.exe)** · [Beta changes, instructions and checksums](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v2.1.0-beta.windows.1)

This opt-in Beta adds the single-GPU FG repair, Manager speed test and repair, hardware-aware controls and current NR previews. Frame generation uses X-Plane's graphics card; the experimental second-card path is retired. Select **Betas** in Manager for these updates. New options still need flight reports; NVIDIA-specific behavior is not yet hardware-tested. RC2 above remains the recommended Release Candidate.

Close X-Plane and Manager, then run the chosen Setup into the existing app folder. **Do not uninstall first.** Settings, local models and enrolled simulator copies are kept. [Read the Beta's checks and limits](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v2.1.0-beta.windows.1).

## Moving from an older Beta to RC

1. Close X-Plane and Manager.
2. Run the RC Setup above directly once. Keep the existing app folder and select your X-Plane folder. **Do not uninstall first.** Settings, local models and your enrolled simulator copies are kept.
3. In **Manager > Updates**, choose **Release Candidates** for future RC updates.

Beta 8 and Beta 9's old update button can get stuck after downloading. Use the direct RC installer to replace that old program. [Beta 9 remains archived for recovery](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/v2.0.0-beta.windows.9); it is not the recommended download. Manager can also keep a previous installer locally for **Backups > Go back**.

Moving from separate Native AA? Run the RC installer once. Pure replaces that mod and keeps its AA choices. Setup removes only unchanged files it owns; edited and unknown files are protected. Moving from FSR 0.7.x? Run this Setup once because the old updater cannot follow the repository rename.

## Start here

Start X-Plane normally and load a flight. Open **Plugins > Aerolux > Open settings**.

- **Pure:** smooth edges at your screen's full resolution. Includes SMAA, FXAA, CMAA 2 and experimental temporal choices such as TAA + SMAA.
- **Boost:** use FSR AA or upscaling. Begin with FSR 3.1.6. Full input keeps native resolution; lower Rendering Resolution choices draw fewer pixels and rebuild the picture.
- **Original:** use X-Plane's own picture.
- **Look:** optional sharpening and colour adjustments.

Start with NR, frame generation and preview options Off. Compare one change at a time. Use **?** for short help and **Changelog** for changes. [Read the installation guide](docs/INSTALLATION.md).

**Aerolux Manager** lists your X-Plane copies, installs or repairs the mod, saves settings backups and shows What's new before an update. Health reports stay on your PC. Picture settings stay in the simulator. Close X-Plane before installing, repairing, removing or restoring.

## Features and limits

- Pure and Boost can use optional frame generation and neural rendering on supported hardware. NR needs your own supported model; no NVIDIA DLL or model weights are supplied.
- Diagnostics has a raw/generated/total frame counter, current logs and report tools. Update notices follow your selected channel.
- New preview choices start Off; updates keep saved choices. Temporal AA, XeSS, the own FSR 3 build and other previews still need community testing.
- Separate instrument windows keep native frames. FG for multiple independent 3D views remains unfinished. NR and FG can cost performance; no option guarantees higher FPS or removes every artifact.
- Windows automated checks and limited live checks on one PC do not prove compatibility with every aircraft, GPU or display. FSR 4.1.2 has known runtime limits; use FSR 3.1.6 if it fails.

## Linux and Mac

[Separate Linux FSR 3.1 and Mac Metal preview 4](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/native-preview-2.0.0-platform-preview.4) · [Platform limits](docs/PLATFORM-STATUS.md). Their existing features are unchanged. This Windows RC does not add Linux/Mac NR or FG, or claim their flight testing.

## Help and licensing

[Join Discord](https://discord.gg/yh396QNgHZ) · [Changelog](CHANGELOG.md) · [Earlier downloads](https://github.com/cjboy31/xplane12-fsr-framegen/releases) · [Licensing](LICENSING.md)

GitHub's automatic Source code archives contain this download documentation, not development source. Earlier releases and all required third-party notices keep their licenses.
