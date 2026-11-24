# TogetherBed website pages

The pages that run inside the TogetherBed Wix Studio site. Wix shows each page in an HTML embed that points at this repository's GitHub Pages address, so a change saved here goes live on the Wix site within a couple of minutes. No Wix republish is needed.

| Page | File | Live address | Shown on |
| --- | --- | --- | --- |
| Home page (3D bed story) | `index.html` | `https://bedheadmarketing.github.io/togetherbed/` | becausemarketing.wixstudio.com/togetherbed |
| Comparison | `compare/index.html` | `https://bedheadmarketing.github.io/togetherbed/compare/` | becausemarketing.wixstudio.com/togetherbed/comparison |

## How to make a change

1. Open the file on GitHub and click the pencil icon (or press `.` to open the full editor).
2. Make your edit.
3. Click **Commit changes** and write one line saying what you changed.
4. Wait 1–2 minutes, then refresh the Wix page. If you still see the old version, do a hard refresh (Ctrl+Shift+R, or Cmd+Shift+R on a Mac).

For bigger changes, commit to a new branch and open a pull request so someone can review it before it goes live. Only changes on `main` go live.

## Good to know

- Both pages must stay in this one repository. They pass the visitor's chosen chapter and edition between them through the browser's storage, which only works when both come from the same address.
- The 3D models (.glb files) are hosted on Sirv, not here. Their addresses are near the top of the script in `index.html`, under `const ASSETS` and `FILES`.
