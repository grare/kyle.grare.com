# kyle.grare.com

Personal site in the "Graphite & Signal" style. One scrolling page, static HTML, CSS,
and a little JavaScript. No build step. Open `index.html` in a browser or serve the
folder with any static host.

```
index.html    markup plus a little inline JS (sticky nav, scroll reveals)
styles.css    all styling and responsive rules
headshot.jpg  the About portrait (800x1000, cropped from the source photo)
resume.pdf    downloadable résumé (linked from the hero and contact)
```

## Headshot

`headshot.jpg` is already in place. To swap it, drop a new photo in this folder with the
same name. A 4:5 portrait (around 800x1000) fills the frame best. If the file is ever
missing, the page falls back to a placeholder. To use a different filename or format,
change the `<img src>` inside `.headshot` in the About section of `index.html`.

## Content

Experience, capabilities, selected work, and contact links are wired from the résumé
(VP of Development at Goliath Technologies, then Bloomberg, Unitrends, and RPI). Edit the
text directly in `index.html`.

## Notes

- `resume.pdf` is a redacted copy. The home address and phone are removed, while email and
  LinkedIn are kept. Your full résumé stays on your Desktop (KGrareResume-1.pdf) and is not
  committed to this repo.
- The phone is also kept off the web page itself. To show it anywhere, add a `tel:` channel
  in the Contact section.
- Fonts (Newsreader, Hanken Grotesk, JetBrains Mono) load from Google Fonts.
- Motion respects `prefers-reduced-motion`.
