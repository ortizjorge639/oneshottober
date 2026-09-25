# OneShotTober

One prompt, one shot, shown out loud.

This repository contains the static OneShotTober site and 31-day prompt
challenge. It uses plain HTML and CSS with no dependencies or build step.
`index.html` contains the main page, and `example.html` contains the embedded
generative-canvas one-shot example. The supplied OneShotTober mark lives at
`assets/oneshottober-mark.png` and is used in the hero, favicon, and social
sharing metadata.

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
