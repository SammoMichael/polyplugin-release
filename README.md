# PolyPlugin Dev Modes

## Local development

Use the dev symlink so IINA loads the plugin directly from this repo:

```bash
npm run dev:link
npm run dev:watch
```

`dev:watch` rebuilds, syncs, and restarts IINA on changes.

## Release testing

Remove the local dev install before testing the GitHub-distributed plugin:

```bash
npm run dev:unlink
```

Then restart IINA, open `Preferences → Plugins`, choose `Install from GitHub...`, and paste one of:

`https://github.com/SammoMichael/polyplugin-release`

IINA also accepts the GitHub URL path form:

`github.com/SammoMichael/polyplugin-release`

IINA also accepts the shorthand repo path:

`SammoMichael/polyplugin-release`

This avoids false results where IINA is still loading the local source repo through
`polyplugin.iinaplugin-dev`.
