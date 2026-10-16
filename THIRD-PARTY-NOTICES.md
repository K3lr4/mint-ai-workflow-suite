# Third-party notices for mint-ai-workflow-suite 1.0.0

The complete attribution inventory and license texts are included in the
`licenses/` directory of the attached source archive
`mint-ai-workflow-suite-1.0.0.tar.gz`. The archive is the authoritative
source bundle for this release; the repository root contains the publication
metadata and the release page contains the binary Flatpak assets.

The project-owned source and release metadata are licensed under 0BSD. The
application bundles include or are built with the following separate works:

| Component | Version | License / notice |
| --- | --- | --- |
| Tcl and Tk | 9.0.2 | Tcl/Tk custom license; full text in `licenses/Tcl-Tk-9.0.2-license.terms` |
| LibTomMath | Tcl 9.0.2 internal source | Public-domain dedication / upstream terms |
| Python | 3.13.15 | Python-2.0 and accompanying notices |
| Python Xlib | 0.33 | LGPL-2.1-or-later |
| Pillow | 12.3.0 | MIT-CMU and included codec notices |
| Papirus icon asset | retained source icon | GPL-3.0-only |
| Adwaita icon assets | 46.0-1 at build time | Upstream GNOME/Debian copyright notices |

The exact files and upstream attribution links are in the archive-level
`THIRD-PARTY-NOTICES.md` and `licenses/` directory. The Flatpaks use the
`org.gnome.Platform//50` runtime, which is installed separately; its license
metadata remains authoritative. Audio/video encoding and capture rely on the
runtime's FFmpeg and codec configuration, so jurisdiction-specific patent and
redistribution obligations must be reviewed by anyone redistributing the
bundles.
