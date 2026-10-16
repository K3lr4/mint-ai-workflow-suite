# License status for the combined release structure

The combined release metadata, installer, and application source code owned
by this project are provided under the 0BSD license. Component-specific
third-party notices and upstream licenses remain authoritative for bundled
external material.

## License audit for the 1.0.0 Flatpaks

The three Flatpak manifests were reviewed against the contents that are
installed into the application images. The release now carries the complete
license texts or upstream copyright files for Tcl/Tk 9.0.2, the internal
LibTomMath source, Python 3.13.15, Python Xlib 0.33, Pillow 12.3.0, the
Papirus icon, and the two Adwaita presentation icons. The inventory and file
mapping are maintained in the root `THIRD-PARTY-NOTICES.md`.

The Flatpak application bundles are app-only exports. `org.gnome.Platform//50`
is a separate runtime reference and is therefore not included in the
application archive. The runtime's own license metadata, source obligations,
FFmpeg build configuration, and codec notices remain applicable to anyone who
redistributes or installs that runtime.

## AudioClippingTool

The source snapshot includes its own `LICENSE` file with the 0BSD license
and `THIRD-PARTY-NOTICES.md` for dependent components. The FFmpeg binary
from the local development installation is deliberately excluded from this
source release directory.

## Screenshot-Markierer

The source snapshot includes the 0BSD license and the existing third-party
notices. The Papirus icon remains covered by its respective upstream license,
which is documented in the included notices. The existing Flatpak build is
rebuilt from the current source with its supporting metadata. The unchanged
Papirus icon is covered by GPL-3.0-only; the complete GPL text and attribution
record are included in `licenses/`.

## VideoClipper

The project source and documentation are provided under 0BSD in
`VideoClipper/LICENSE`. FFmpeg, H.264/libx264, AAC, Python Xlib, X11,
PulseAudio/PipeWire, `pactl`, and the Linux desktop remain under their own
licenses and usage conditions, as documented in
`VideoClipper/THIRD-PARTY-NOTICES.md`.

The Video Clipper Flatpak uses the FFmpeg and `pactl` components supplied by
the GNOME 50 runtime. The runtime and its codec extensions retain their
respective licenses and distribution conditions.

## Open publication constraints

Public publication remains pending. Before publication, verify the exact
GNOME runtime revision used by the final distribution, provide its runtime
license/source information as required, and complete a jurisdiction-specific
review of H.264/libx264, AAC, and any other codec or patent obligations. The
current local x86_64 bundles and their checksums document this build, but do
not constitute a legal opinion or a runtime redistribution grant.
