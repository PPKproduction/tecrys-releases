# Tecrys releases

Downloads of **Tecrys**, a parametric 3D CAD program, and **Tecrys PDM**, the team's vault of
Tecrys files, for macOS (Apple Silicon, macOS 14+) and Windows (x64 and ARM64), and the feeds
their built-in updaters read.

- **Download**: see [Releases](../../releases). Mac: the `.dmg`; Windows: `windows-x64.exe`
  (most PCs) or `windows-arm64.exe` (ARM PCs).
  - **Tecrys**: releases `v<version>-<build>`, files `Tecrys-…`.
  - **Tecrys PDM**: releases `pdm-v<version>-<build>`, files `TecrysPDM-…`. It includes the vault
    server (`tecrys-pdm-server`) and the `tecrys-pdm` command line: on the Mac inside the app
    (`Tecrys PDM.app/Contents/MacOS`), in Windows next to it. See the app's Help ▸ Administration.
- **First start**: the apps are not signed by Apple or Microsoft. On the Mac open System Settings ▸
  Privacy & Security ▸ Open Anyway; in Windows click More info ▸ Run anyway. Later versions arrive
  through *Check for Updates…* in the app and need no approval.
- **Source**: every release includes its `…-source.tar.gz`. Tecrys and Tecrys PDM are free
  software under the GNU GPL version 3.

**Ideas and problems**: [open an issue](../../issues/new/choose) (Suggest a feature / Report a problem;
a free GitHub account is needed). In Tecrys: Help ▸ Suggest a Feature… / Report a Problem….

The `appcast-*.xml` files are the update feeds (`appcast-pdm-*` for Tecrys PDM; signed with the Tecrys update key); don't edit them by hand.
