# Launchy download shelf

The finished Launchy app for Android TV, ready to install. No code or settings live here.

**Install on a TV with Downloader:** type
`github.com/tahoebear/Launcy-Shelf/releases/latest/download/Launchy.apk`

After that, Launchy updates itself.

- `apps.json`: the apps offered in Launchy's **Get apps** page. Each one installs from its own official download
  page (`"github": "owner/project"`) or opens in the Play Store (`"playStore": true`). `"apk"` picks the file by a word in its name; `"prerelease": true` for projects that only publish test versions.
- `setup.json` (when present): a shareable look, home rows and screensaver, without anyone's add-ons.
