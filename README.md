Metal-Corsa — beta downloads
Metal-Corsa is a native Apple-Silicon macOS mod manager for Assetto Corsa running under CrossOver/Wine. This repo holds beta downloads only — no source code.

Requirements: Apple-Silicon Mac (M1 or newer), macOS 14 (Sonoma) or later, a legitimate copy of Assetto Corsa installed in a CrossOver bottle.

Install
Download Metal-Corsa.zip from the latest release and unzip it.

Drag Metal-Corsa.app into your /Applications folder.

These beta builds aren't notarized by Apple yet, so macOS quarantines a fresh download. Clear it once — open Terminal and paste:

xattr -dr com.apple.quarantine /Applications/Metal-Corsa.app && open /Applications/Metal-Corsa.app
(Alternatively: right-click the app → Open → Open on the warning. The Terminal line is more reliable.) You only do this once per download; updates you install later need it again.

The app checks for updates on its own and shows Update available when a newer beta is posted here.

Something broke?
Join the Discord and tell us in #dev-log — a screenshot of the Library screen and what you were doing is gold. Beta builds are pre-release; keep your own backups of your Assetto Corsa content.

Metal-Corsa is an unofficial tool, not affiliated with or endorsed by Kunos Simulazioni, 505 Games, CodeWeavers, or the authors of Custom Shaders Patch, Pure or Content Manager. The app is proprietary; see the in-app license.
