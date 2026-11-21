## Launcher v1.0.3 — Updater & AI Diagnostics Update
* **Updater Fix:** Fixed an issue where clicking **Install update** could crash if the download link pointed to a webpage instead of a direct `.exe` installer.
* **Consistent Installer Naming:** Standardized the installer filename to `TheFrostlinerZ-Launcher-Setup.exe` for seamless updates.
* **Improved AI Log Diagnostics:** Updated the **Pack logs (AI help)** prompt to clearly separate vanilla DayZ engine errors from modded errors, distinguish client-side fixes from genuine admin tickets, and reference the Desktop `.zip` archive for deeper inspection.

## Launcher v1.0.2 — Settings, Auto-Refresh & UI Polish
* **Automatic Update Check:** Silently checks GitHub for new launcher releases on startup without spamming the Activity Log.
* **Live Background Refresh:** Automatically refreshes player count, in-game time, ping, and Discord status every 5 minutes in the background.
* **Restart Countdown Timer:** Live countdown to the next scheduled server restart (`01:00, 04:00, 07:00, 10:00, 13:00, 16:00, 19:00, 22:00` UK time) with automatic timezone detection and manual override.
* **Settings Tab (`⚙`):** Added a dedicated Settings panel for timezone selection, custom DayZ installation path, and one-click backup/restore of DayZ profiles & keybinds (`Documents\DayZ`).
* **Discord Rich Presence:** Enabled by default to automatically display your current FrostlinerZ activity in Discord.
* **Hover Tooltips:** Added custom dark tooltips across sidebar controls explaining what each tool does.
* **Sidebar & Footer Refinement:** Moved **Verify mods** into **Tools & Support**, pinned **Join Discord** to the bottom of the sidebar, unified typography, and added the Activity Log copyright footer.

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
