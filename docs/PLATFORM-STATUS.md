# Platform status

- FSR Windows: public Release Candidate baseline and newer v2 Betas. Feature support depends on your graphics hardware and driver.
- FSR Linux: [experimental native FSR 3.1 upscaling preview 3](https://github.com/cjboy31/xplane12-fsr-framegen/releases/tag/native-preview-2026.11.03.1). Optional FSR 4 requires a library you build yourself; AMD does not ship FSR 4 for Linux and it is not included. No neural rendering or frame generation. The launcher lists every X-Plane folder.
- FSR macOS: the same experimental preview includes a double-click installer, a Frame survey mode and basic edge smoothing for the 3D scene only. Menus and instruments are never changed. It does not upscale or generate frames yet. Please send Output/preferences/XPFSRMetalPreview.jsonl from a survey flight to help the next MetalFX step. The plugin is signed but not notarized: approve only the specific plugin in Privacy & Security if needed, never disable Gatekeeper.
- These Mac/Linux preview packages have passed automated builds and package checks only. No real X-Plane flight testing on either platform has been completed. Windows users should keep using 2.0 Beta 3.
- Native AA Windows: public baseline, manual Zink hotfix and newer v2 Beta.
- Native AA Linux: separate native beta. Automated build and Vulkan tests passed; actual Linux X-Plane flight compatibility is still being evaluated.

Beta and preview downloads may have problems. Longer flights, low-memory recovery, moving objects and night scenes still need feedback. No setting guarantees higher FPS or removes every artifact. Use the status messages and ? help in the simulator.