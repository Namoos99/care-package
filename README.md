# care package

A tiny illustrated room you fill with notes for someone you miss.

You build the room: dress your avatar, tuck notes into things (the letter, the chai, the record player, Selena the cat…), pick the big words at the top and add a song. Then you send a link. Your friend opens an envelope, and your avatar walks them around the room to each note.

**Live:** https://namoos99.github.io/care-package/

## What's in it

- A walking avatar in a chunky, hand-drawn style: tap the floor (or use the arrow keys) and she walks there, swinging her arms; she waves when she reaches something.
- A room that moves on its own: swaying lamp, curtains and plants, steam from the chai, a breathing cat with floating z's, twinkling stars, dust in the lamplight.
- Night mode, a spinning record with a built-in lo-fi tune, or your own Spotify song.
- Greetings in English, Urdu, Hindi, Farsi, Arabic and Spanish.

## How the links work

There is no database and no account. The whole package (names, notes, avatar, song) is compressed into the part of the link after the `#`. Nothing is stored on a server, and the notes never end up in this repo.

## Run it

It's one self-contained file. Open `index.html` in a browser, or serve the folder with any static host. On GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `(root)`.

If you host it somewhere other than `namoos99.github.io/care-package/`, the app picks up its own address automatically when links are made from the live site. The `HOSTED` constant near the top of the script is only the fallback used when previewing locally.

## Credits

Room illustration generated with Figma AI and hand-edited (Selena became a tuxedo cat). Avatar, motion, music and everything else are hand-written SVG, CSS and JavaScript. Inspired by Prasiddhi Jain's [care package](https://carepackage.prasjain.com).
