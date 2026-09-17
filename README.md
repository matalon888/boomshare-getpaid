# BoomShare for Freelancers — get-paid landing page

A landing page for the BoomShare freelancer pivot: upload the finished work, set a price,
send one link. **The files stay locked until the client pays**, then they unlock instantly.

**Live:** https://matalon888.github.io/boomshare-getpaid/

## What's here

| File | |
|---|---|
| `index.html` | The page. Self-contained — one HTML file, no build step, no dependencies. |
| `img/pb/` | 35 original picture-book illustrations (gouache style, matted to transparency). |
| `img/people/` | Painted portraits for the testimonial wall. |
| `apple-design.html` | An abandoned alternative direction, kept for reference. Not linked from the site. |

## How it's built

Plain HTML, CSS and vanilla JS in a single file. No framework, no bundler — open `index.html`
in a browser. Fonts come from Google Fonts; everything else is local.

Motion is scroll-driven and self-playing: the page performs for the reader rather than waiting
for clicks. Every animation is disabled under `prefers-reduced-motion`.

## Note on the testimonials

The quotes on the wall are **written examples, not real customer quotes**, and the page says so
in a marked notice above them. They are there to show the layout and the tone. They get replaced
with real quotes from the pilot before this goes anywhere near paid traffic.

## Status

Design draft. Not wired to a backend, a payment processor or an analytics tag.
