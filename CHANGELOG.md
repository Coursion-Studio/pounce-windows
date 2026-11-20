# Changelog

## 0.5.0 — 2026-11-20
- **Window switcher.** Type part of a window's title or app, such as `chrome docs`, and jump straight to it. `:win` lists every open window.
- **Clipboard history.** Type `clip` to see the last 50 things you copied, text and images, and paste one with Enter. Stored only on this PC, encrypted with your Windows account; copies from password managers are skipped. Turn it off or clear it in Settings.
- **Conversions.** `5 km in miles`, `72f to c`, `2 gb in mb`, `3 cups to ml`. Currency (`100 usd to try`) is opt-in and uses daily European Central Bank rates.
- **Scopes.** Type `:` to search just one thing: `:apps`, `:files`, `:win`, `:clip`, `:web`, `:sys`, `:snip`.
- **System actions.** Dark mode, volume, mute, sleep, lock, restart, shut down and sign out (these ask first), empty Recycle Bin, Wi-Fi and Bluetooth settings, screenshot.
- **Snippets and quick links.** `;addr` pastes your saved text (`;date` and `;time` built in). `gh pounce`, `yt`, `wiki`, `maps` open searches; add your own in Settings.
- **Wider file search.** Searches everything Windows indexes, and every drive instantly when Everything (voidtools.com) is running.
- **14 languages.** English, Deutsch, Español, Français, Italiano, Português (Brasil), Nederlands, Polski, Türkçe, Русский, Українська, 日本語, 한국어 and 简体中文. Auto follows Windows; change it in Settings → General → Language.
- **Works over admin windows.** Optional: Settings → General. Asks for permission once.

## 0.4.1 — 2026-11-20
- **Recents as a button.** Recent items now have three modes: Show (the list), Button (a “Recent” button you open with a click or ↓) and Hide (just the search bar). Settings → Search, the tray menu, or right-click the bar.

## 0.4.0 — 2026-11-20
- **Your own theme from any colour.** Pick a colour in the new colour picker, or click any pixel on screen with the eyedropper, and Pounce builds a whole theme from it, dark or light. Also: type `theme #ff7a59` or `theme pick` in Pounce.
- **Settings follows your theme.** Settings, the tray menu and every Pounce window now change with the theme, straight away.
- **Live preview** in Settings → Appearance shows the bar in the selected theme and style as you click.

## 0.3.0 — 2026-11-20
- **Automatic updates.** Pounce checks once a day and shows what's new; one click downloads, verifies
  and installs the update. Every update is signed by Coursion Studio. Settings → Updates, or the tray.
- **15 themes**, the same palettes as Pounce in Hutch: Aurora, Hibiscus, Eclipse (default), Neon, Wildfire,
  Ember, Hutch, Coral, Midnight, Forest, Sunset, Mono, Candy, Paper (light) and Graphite.
- **3 styles**: Glass (frosted, colour wash), Ledger (flat ink, hairline rules, monospace labels) and
  Compact (one-line rows). Pick them in **Settings → Appearance**, or type `theme` / `style` in Pounce.
- **Show recents** can be turned off: then Pounce is just the search bar until you type.
- **Right-click menus.** On a result: Open, Show in Explorer, Run as administrator, Copy path / name / link,
  Remove from recents. On the bar: change theme or style, show recents, re-centre, Settings.
  The keyboard's menu key opens the selected result's menu.
- **Move the bar.** Drag the top of the search bar or its bottom hint bar to put Pounce anywhere.
  It remembers the spot, relative to the screen, so it lands in the same place on any monitor.
  Double-click to re-centre, or use **Settings → General → Bar position → Re-centre**.

## 0.2.0 — 2026-11-19
- **Installer.** `PounceSetup.exe`: one file, installs just for you with no admin rights, adds a Start menu
  entry, can start with Windows, updates in place, and uninstalls from Installed apps.
- **New look.** Pounce's own tray menu, Settings, About and Licence windows, in the Coursion style.
- **Settings** from the tray, the ⚙ in the search bar, `Ctrl+,`, or by typing "settings".
- **Ctrl+Space** is now the main shortcut. Alt+Space and Win+S still work and can each be turned off.
- Fixed: opening Pounce could leave the Windows key stuck.
- The keyboard hook runs on its own thread, so typing never lags while Pounce loads icons.

## 0.1.0 — 2026-11-18
- First version: apps, files, maths, web search, links, `>` commands and recent items, opened with Win+S.
