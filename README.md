# Polyscript for IINA

Polyscript brings dual subtitles, hover dictionary, AI-assisted translation, and language learning workflows directly into IINA.

## Install

### Option 1: Install from GitHub (recommended)

1. Open IINA.
2. Go to `Preferences` -> `Plugins`.
3. Click `Install from GitHub...`.
4. Paste:
   - `https://github.com/SammoMichael/polyplugin-release`
5. Confirm installation.

### Option 2: Install from package file

1. Download `polyscript-iina.iinaplgz` from this repository (or Releases).
2. In IINA, go to `Preferences` -> `Plugins`.
3. Click `Install from Package...`.
4. Select the downloaded `.iinaplgz` file.

## Features

- Dual subtitles with flexible layout controls
- Hover dictionary for quick term lookup
- AI translation workflow for subtitle lines
- TTS and language-learning focused playback tools

## Updates

If you install from GitHub, IINA can detect updates using plugin metadata (`ghRepo` + `ghVersion`).

## Known Issue (IINA 1.4.1)

On some machines, using `Plugins -> Reload Plugins` can crash IINA due to a host-side plugin reload race.

Recommended workflow:
- After install/update, restart IINA instead of using `Reload Plugins`.
- If IINA crashes while reloading plugins, relaunch IINA and continue normally.

## Support

- Website: [polyscript.app](https://polyscript.app)
- Email: support@polyscript.app
