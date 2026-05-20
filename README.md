# product-hello-world

A tiny personal landing page used to teach **VSCode, Git, and the command line**. No installs required — if you have a web browser and VSCode, you have everything you need.

## What's in here

| File            | What it is                                                 |
| --------------- | ---------------------------------------------------------- |
| `index.html`    | The page itself — structure and content                    |
| `styles.css`    | The colours, fonts, and layout                             |
| `app.js`        | A tiny script that reads `projects.json` and renders cards |
| `projects.json` | The list of projects, as data                              |

## See it running

The fastest way:

1. Open this folder in VSCode (`File → Open Folder…`).
2. Install the **Live Preview** extension (search "Live Preview" by Microsoft in the Extensions panel).
3. Right-click `index.html` → **Show Preview**.

You can also double-click `index.html` to open it in your browser, but the projects list won't load that way — browsers block `fetch()` against local files for security reasons. Live Preview gets around this.

## Try editing something

- Change your name in `index.html` (look for `Sam Rivera`).
- Tweak the accent colour in `styles.css` (look for `--color-accent`).
- Add a new project to `projects.json` — make sure to keep the commas tidy.

Save the file and the preview updates automatically.

## Using the command line

Open VSCode's built-in terminal with **Ctrl + `** (the backtick, top-left of most keyboards). Some commands to try:

```bash
ls            # list files in this folder (use 'dir' on Windows cmd, 'ls' in PowerShell works too)
pwd           # show where you are
git status    # see what's changed
git log       # see the history of changes
```
