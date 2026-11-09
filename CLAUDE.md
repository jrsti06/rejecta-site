# Rejecta Film Festival
A one-page website for the Rejecta Film Festival, a tongue-in-cheek "festival for rejected films" built around the short film MOOCH and its screening.

The owner isn't a developer: explain in plain language, keep steps short, and do the work rather than handing over commands where you can.

## What's here
- `index.html`: the whole site. Styles and JavaScript are inside this one file.
- Page sections (by id): `submissions`, `films`, `countdown-section`, `map`, `about`, `ugc` (a sign-up/submission form).
- `images/`: logos, MOOCH artwork and stills, social icons, and GIFs used on the page.

## Run, build, deploy
- Static files, no build step. Open `index.html` in a browser to preview.
- Hosting isn't recorded in this repo; ask the owner before assuming where it's published.

## Working on it
- Default branch: main. This repo is public: never commit keys, passwords, or private files. Keys go in a local .env, which stays out of git.
- Phone/cloud sessions work on a fresh copy from GitHub and hand back a branch to merge. Commit and push finished work.
- The countdown timer is hard-coded in the script near the bottom of `index.html` (`const premiere = new Date(...)`, currently June 8, 2025). Update it for a new event, or it will show a past date.
- The form sends entries to a Google Apps Script web address written in `index.html`. Don't change or remove that address unless asked; entries would stop arriving.
- The "Higher Jump" headline font loads from an outside (Squarespace) link; if that link breaks, headings fall back to another font.
- Ticket links point to Eventbrite.
- Some image filenames contain spaces (for example `mooch teaser art.jpg`); prefer simple lowercase names for new ones.
- Large photos (several MB) slow the page down: shrink them before adding to `images/`.
- Don't commit `.DS_Store` files (Mac clutter).
