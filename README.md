# OneShotTober

One prompt, one shot, shown out loud.

This repository contains the static OneShotTober manifesto and 31-day prompt
challenge. The site is a single self-contained HTML file with no dependencies
or build step.

## Run locally

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000>.

## Deploy to Vercel

Import this repository as a new Vercel project named `oneshottober`.

- Framework preset: **Other**
- Build command: leave empty
- Output directory: `.`

The intended production URL is
<https://oneshottober.vercel.app/>.
