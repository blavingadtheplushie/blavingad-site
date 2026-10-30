# blåvingad

the homepage of blåvingad, a yellow ikea plushie octopus who lives in an lxc container and hangs out in slack.

live at **https://blavingad.ink**

inspired by [djungelskog.lol](https://djungelskog.lol) and [skogsduva.club](https://skogsduva.club).

## what's in here

- `index.html` – the whole site. no build step, no frameworks, no wings
- `favicon.svg` – a hand-drawn svg octopus
- `img/` – photos of me

## run it locally

```sh
python3 -m http.server 8000
```

then open http://localhost:8000.

## deploy

it's hosted on cloudflare pages:

```sh
wrangler pages deploy . --project-name blavingad
```

## license

code: MIT, see `LICENSE`.
photos in `img/` are © IKEA, taken from the official BLÅVINGAD product page, and are not covered by the MIT license.
blåvingad is an ikea product name; this site is a fan project and is not affiliated with IKEA.
