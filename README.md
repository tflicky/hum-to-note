# 🎷 Hum to Note

Hum or sing a melody and see the notes, with fingering charts for your instrument.

**Try it:** https://tflicky.github.io/hum-to-note/

## Features
- Live pitch detection from your microphone. Say "doo" once for each note.
- Drawn icons for every instrument, and fingering diagrams for sax (tenor and alto), piano, guitar, bass, ukulele, violin, cello, flute, clarinet, trumpet, recorder and ocarina
- Automatic transposition for B♭ and E♭ instruments
- Edit notes, add chords and play melodies back with real recorded instrument sounds, all at an even volume. ← → step through notes, Alt+← → moves one
- Sing more onto a song you already made, optionally keeping the last chord going
- View options: note size, fit the whole song on screen, spacing, and hiding fingering pictures
- Piano diagrams show three octaves, each in its own color
- A built-in library of 22 classic and traditional songs (kids, holiday, classical, folk), all free to use. Preview any song, then Remix it to save your own editable copy
- Paste a song: copy letter notes from any website, lyrics and all. Lyric lines are skipped, `^C` means an octave up, and dash-joined notes like `D-C-Bb` stay together
- Save songs in colored folders, give them your own icons, search them, drag one song onto another to merge, duplicate them, and export or import backups

Everything runs in your browser as a single `index.html` with no build step. Songs are saved in your browser's local storage.

## Credits
Instrument sounds load from the internet the first time each note plays; without a connection the app uses simpler built-in sounds. Sax, flute, recorder and ocarina always use the built-in sounds.

- Piano: [Salamander Grand Piano](https://tonejs.github.io/audio/salamander/README) by Alexander Holm, [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
- Acoustic guitar and clarinet: [tonejs-instruments](https://github.com/nbrosowsky/tonejs-instruments) by Nicholaus Brosowsky, [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
- Bass, ukulele (nylon guitar), violin, cello and trumpet: FluidR3 GM soundfont via [midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts), [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
