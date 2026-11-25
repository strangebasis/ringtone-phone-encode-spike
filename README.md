# Phone encode spike

A temporary test page for [strange_ringtone](https://github.com/strangebasisdevs/strange_ringtone),
a self-hostable tool that turns an audio clip into an iPhone ringtone.

The page asks one question: can a phone make a finished ringtone by itself?
It synthesises a short loop, encodes it to AAC with the browser's own
`AudioEncoder`, wraps it in an M4A file written in JavaScript (`m4a.js`), and
offers the result to the share sheet. No audio leaves the device and no server
takes part.

This repository exists only to serve the page over HTTPS for a test on a
phone, and will be deleted afterwards. The files are a copy of
`tools/spike/phone_encode/` from strange_ringtone.

Licence: AGPL-3.0-or-later, the same as strange_ringtone (see `LICENSE`).
