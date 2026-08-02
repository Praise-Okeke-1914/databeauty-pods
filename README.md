# Databeauty Tribe — Pod Allocation Board

The public "Meet Your Pod" board for the Databeauty Tribe Business Challenge.
Participants open it to find which pod (team) they've been assigned to.

**Live:** https://praise-okeke-1914.github.io/databeauty-pods/

## What's here

| File | Purpose |
|---|---|
| `index.html` | The whole board — self-contained HTML + CSS (only external request is Google Fonts) |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Editing participant names

Open `index.html` and find the pod you want, e.g.:

```html
<!-- GOLD POD PARTICIPANTS -->
<ol class="participant-list">
  <li class="participant-row"><span class="participant-name">Participant Name</span></li>
</ol>
```

- **Change a name** — replace the text `Participant Name`.
- **Add someone** — copy a whole `<li>…</li>` line and paste it below.
- **Remove someone** — delete their `<li>…</li>` line.

Row numbers (01, 02, 03…) are generated automatically, so they always stay
correct after adding or removing people. Save, commit, and push — the live
page updates within about a minute.

## Why this is a separate repository

This repo is **public** so GitHub Pages can serve it for free. It contains
only static HTML — no source code, no configuration, and no secrets. The main
application lives in a separate **private** repository.
