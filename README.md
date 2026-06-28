# Andrúm

Official website for **Andrúm**, an Icelandic post-rock band active from 2003 to 2008. The site preserves and shares the band's work - music, photos, and videos - including their two full-length albums, *Andvakar* and *Gott Andrúm*.

This website was built as a school project at the University of Skövde in Sweden in 2011.

## Structure

- `index.html`, `about.html`, `music.html`, `pictures.html`, `videos.html`, `contact.html` — site pages
- `music/` — MP3s for the *Andvakar* and *Gott Andrúm* albums, played with native HTML5 `<audio>` on the music page
- `pictures/` — photo galleries (including studio shots)
- `css/`, `js/` — stylesheets and scripts
- `fancybox/` — jQuery FancyBox lightbox library used for the photo galleries

## Running locally

This is a static site. Serve it with any web server, e.g.:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.
