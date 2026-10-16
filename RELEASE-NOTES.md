# Release Notes — mint-ai-workflow-suite 1.0.0

## Current feature set

- Audio Clipping Tool: refreshed recording interface, global hotkey, current
  system-output detection, and persistent file clipboard ownership.
- Video Clipper: refreshed recording interface, `Ctrl+G`, 30 fps, a
  twenty-second limit, H.264/CRF 18, AAC audio, and mixing of all available
  output monitors.
- Screenshot Marker: refreshed interface, fully visible window text,
  8-pixel outline grip zone, and correct movement and rotation of arrows and
  ellipses.

## Packaging and licensing

- The combined release metadata, installer, and project-owned source are
  provided under 0BSD.
- Video Clipper now includes its license, Python dependency declaration, and
  third-party notices for FFmpeg and the desktop capture stack.
- The included `install.sh` creates user-local application directories and
  desktop entries from the selected installation path.
- The Screenshot Marker Flatpak metadata identifies the project as 0BSD;
  the bundled Papirus icon remains documented under its upstream license.
- All three tools include GNOME 50 Flatpak manifests and current x86_64
  single-file bundles with the required X11, clipboard, and audio permissions.
- The release carries full license texts and attribution records for Tcl/Tk,
  LibTomMath, Python, Python Xlib, Pillow, Papirus, and Adwaita assets. The
  separate GNOME runtime and codec obligations are explicitly documented.
- All three AppStream release entries use version `1.0.0`, matching the root
  `VERSION` file and the rebuilt application bundles.
- `RELEASE-DESCRIPTION.md` contains the prepared public release text with the
  AI authorship, support, maintenance, warranty, and installation disclaimers.
- The public source snapshot contains no machine-specific launcher paths,
  local account paths, private configuration, credentials, or Codex/MEMORY
  material.

## Validation

The three source snapshots were checked individually before bundling. The
Video Clipper test suite passes all 8 tests. The Screenshot Marker suite
passes 39 tests; its native GUI integration class is skipped in the current
headless test environment because no display is available. Python
compilation, desktop-file validation, AppStream validation, and shell syntax
checks also pass. The installed Video Clipper main file was synchronized to
its current source snapshot.

## Scope

This release contains local source snapshots and rebuilt application Flatpaks
for all three tools. It is stored as a combined local release preparation. It
carries no public publication or ongoing support promise.
