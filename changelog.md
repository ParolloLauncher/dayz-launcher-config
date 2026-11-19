## Launcher v1.0.1 — 2026-11-19
### New Features
- **Live Markdown Support** – Announcements, Changelog, Rules, and Guides now pull directly from GitHub `.md` files with full formatting (headings, lists, tables, callouts, and clickable links).
- **AI-Assisted Log Diagnostics** – Clicking **Pack logs** now saves the `.zip` archive to your Desktop, automatically copies a redacted error & system summary prompt to your clipboard, and opens AI chat so you can simply press `Ctrl + V` to diagnose crashes.
- **Custom DayZ Folder Selection** – Added a **Set DayZ folder** button in the sidebar for players with non-standard Steam library paths.

### Improvements
- **Expanded Log Cleaner** – **Clear logs** now also removes the new `error_*.log` files generated directly inside the main DayZ installation folder.
- **Improved Log Packing** – Recent `error_*.log` files from the DayZ directory are now automatically included in the support `.zip` and error summary.

---

## Launcher v1.0.0 — Initial Release
### Highlights
- **One-Click Join** – Launches **The FrostlinerZ (Namalsk)** with all required Steam Workshop mods loaded automatically.
- **Live Server Status** – Real-time player count, in-game time, map info, and direct UDP ping via DZSA API.
- **Automatic Mod Verification** – Checks installed Workshop mods against Steam and opens missing or outdated mods directly in Steam.
- **Persistent Nickname** – Save your custom survivor name once and use it every time you join.
- **Server Hub UI** – Dark Namalsk ice-blue theme with collapsible cards for Announcements, Changelog, Rules, Guides, and active Mods.
- **Support Tools** – Built-in DayZ client log packer (with automatic Windows username & SteamID redaction) and log cleaner.