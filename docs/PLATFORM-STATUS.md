# Native platform status

Windows: use FSR 2.0 Beta 5 or the earlier Release Candidate baseline. Linux and Mac use the separate [experimental native preview 4](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/native-preview-2.0.0-platform-preview.4). They do not have all Windows features.

- Linux x86_64: FSR 3.1 upscaling preview; optional compatible FSR 4 library supplied by the user. MSAA Off. No NR or frame generation.
- Mac: universal Apple Silicon/Intel Metal preview with Off, Frame survey, experimental scene-only edge smoothing and a development MetalFX spatial-upscale option on supported macOS 13+ devices. No frame generation. Basic signatures; not notarized. Never disable Gatekeeper.
- Native build/rendering/lifecycle/package checks passed. Real Linux/Mac simulator flight quality and Intel Mac execution remain unverified. Please share the Mac Frame survey log from Output/preferences/XPFSRMetalPreview.jsonl after reviewing it.

[Community help](https://discord.gg/yh396QNgHZ)
