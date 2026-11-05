Aerolux — 2.0 BETA 7 (WINDOWS)

INSTALL
1. Close X-Plane and the Plugin Updater.
2. Run the file ending in Setup.exe. If you chose the RAR, extract it completely and run its setup.
3. Choose your X-Plane folder, the one containing X-Plane.exe. It may be on another drive. Keep your current mod app folder when updating.
4. Start X-Plane with your normal shortcut or launcher and load a flight.
5. Open Plugins > Aerolux > Open settings.
Your image controls are inside X-Plane. The separate app only updates plugins.

Updating from 0.7.x: the old updater cannot find v2 after the repository rename.
Run the new Setup.exe once; saved choices and imported models are kept.

FIRST COMPARISON
1. In Picture, choose an engine: Pure smooths edges at your screen's full resolution; Boost uses FSR to smooth edges or rebuild a lower-resolution picture; Original shows X-Plane's own picture. Restart when the panel asks. Less common settings are under Advanced.
2. Start with frame generation and NR Off. Leave preview options Off.
3. For Boost, begin with FSR 3.1.6. FSR follows Rendering Resolution in X-Plane's own Graphics menu. Full keeps native resolution and smooths edges. Lower choices draw fewer pixels, then FSR builds the output picture. You can change the slider while flying. For Pure, use Full.
4. The X-Plane resolution row explains what is running. Look for BOOST ACTIVE or PURE ACTIVE. If it says Waiting or Bypassed, read its reason.
FSR 4.1.2 needs a supported GPU and driver. Its separate AMD runtime has known compatibility limits; use FSR 3.1.6 if it fails. Intel XeSS is an experimental alternative and needs your own compatible libxess.dll; the panel explains where to copy it.
The mod keeps FXAA Off after a normal exit. It does not change your display size or Zink. MSAA with temporal processing remains experimental.
Use ? for short help. Click ? to pin it; press Esc to close the card.

PURE AND LOOK
Pure includes SMAA, FXAA, CMAA 2, TAA, TAA + SMAA, TAA + FXAA and SMAA T2x. Temporal methods use earlier frames to steady edges and remain experimental. Start with SMAA High, then compare TAA + SMAA for moving edges. Pure works without AMD's files when extra frames are Off.
Look adds optional sharpening and colour adjustments. Change one control at a time and compare On with Off. Your aircraft's instruments and X-Plane's menus stay outside the scene adjustments.
Setup replaces an unchanged separate Native AA installation and keeps its saved choices. Edited or unknown files are protected; read setup's message if it keeps them.

FRAME GENERATION
Set Frame generation to a method (Off turns it off), then restart if asked. Close the panel to let FG run. The frame counter (Diagnostics > Show frame counter) shows Raw, Generated and Total output FPS. When one generated frame is added per real frame, Raw and Generated FPS can match; Total includes both.
Try one separate instrument window, then move, resize, close and reopen it. Its frames stay native and do not increase the main view's counter. Mixed window batches use an extra wait and may lower FPS. FG for several independent 3D views and extracting 2D panels from the main scene are unfinished.
OBS can stay installed. A loaded capture hook selects synchronized compatibility, which can lower real FPS. Diagnostics explains what is active.

OPTIONAL NR AND PREVIEWS
Import your own supported NR model from Neural rendering > Model library. We do not include NVIDIA DLLs or model weights. NR costs GPU time; begin with one pass and Performance or Balanced. Do not assume more passes look better.
The same Beta includes image-motion matching, NR result reuse, NR after the frame, adaptive shading, short stutter stand-ins, shader caching, pass-time measurement and Aerolux's own FSR 3 build. They are optional previews, start Off and have help. Compare one at a time and turn it Off if the picture or pacing worsens. Stutter stand-ins need FG Off. The own FSR 3 build uses open-source FSR 3.1.4 in FSR 3.1.6 sessions; it is not FSR 4. No preview guarantees faster FPS or removes every artifact.
Spare caches follow available video memory and 6/8/10/12/16/24/32 GB capacity tiers. Quality choices are kept. This cannot prevent every out-of-memory error.
The old cockpit-screen restore and green alignment tint are retired.

UPDATES AND HELP
Updates opens the optional plugin updater. Select Release Candidates or Betas. Automatic checks follow that channel and display a brief notice in sim when a newer build is available; the panel keeps an Update indicator. Checks run separately from rendering. You may check while flying, but close X-Plane before installing.
Read Changelog inside the panel. Diagnostics opens current logs and report tools.
Help: https://discord.gg/yh396QNgHZ

MORE SIMULATOR FOLDERS
Run setup again, keep the same mod app folder and select another X-Plane folder. The earlier folders keep the mod and receive owned updates. Modified or unavailable folders are skipped with a reason in logs/simulators.txt. Each simulator keeps its own renderer selection. If Native AA is also installed, choose one image processor and restart.

UNINSTALL
Close X-Plane and run the mod's Uninstall.exe or use Windows Settings > Apps.
Owned plugin files are removed from enrolled folders; saved choices/models and unrelated files are kept. Start X-Plane normally afterward.

STATUS
This Windows Beta has automated checks and limited live checks on one Windows PC. These do not prove every aircraft, overlay, display or graphics card works. Multiple memory sizes are simulated, not tests of seven physical cards. Linux and Mac keep their separate preview downloads and limits; this Windows package does not add Linux/Mac NR or FG, or merge their rendering engines.
