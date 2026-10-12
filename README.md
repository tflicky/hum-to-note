# 🎷 Hum to Note

Hum or sing a melody and see the notes, with fingering charts for your instrument.

**Try it:** https://tflicky.github.io/hum-to-note/

## Features
- Live pitch detection from your microphone. Say "doo" once for each note, and type a name to save your melody as a song (it keeps saving as you go)
- Drawn icons for every instrument, and fingering diagrams for sax (tenor and alto), piano, guitar, bass, ukulele, violin, cello, flute, clarinet, trumpet, recorder and ocarina
- Automatic transposition for B♭ and E♭ instruments
- Edit notes, add chords and play melodies back with real recorded instrument sounds, all at an even volume. ← → step through notes, Alt+← → moves one
- Hum a song: when you stop, it becomes a song you can name and edit. 🎤 Hum adds more to a song, ↩ Undo last note takes back a wrong one, and ✕ Cancel throws the whole take away
- View options: note size, fit the whole song on screen, spacing, and hiding fingering pictures
- Piano diagrams show three octaves, each in its own color
- A built-in library of 22 classic and traditional songs (kids, holiday, classical, folk), all free to use. Preview any song, then Remix it to save your own editable copy
- Paste a song: copy letter notes from any website, lyrics and all. Lyric lines are skipped, `^C` means an octave up, and dash-joined notes like `D-C-Bb` stay together
- Edit songs in place: click the title to rename, click the icon to change it, type or paste notes right into the song
- Practice mode: split a song into phrases, mark each run Clean or Mistake (3 clean in a row passes), practice the joins between phrases and build sections up to the whole song, with a metronome, a day streak, and your best tempo and progress saved over time
- Save songs in colored folders, give them your own icons, search them, drag one song onto another to merge, duplicate them, and export or import backups

Everything runs in your browser as a single `index.html` with no build step. Songs are saved in your browser's local storage.

## Credits
Instrument sounds load from the internet the first time each note plays; without a connection the app uses simpler built-in sounds. Sax, flute, recorder and ocarina always use the built-in sounds.

- Piano: [Salamander Grand Piano](https://tonejs.github.io/audio/salamander/README) by Alexander Holm, [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
- Acoustic guitar and clarinet: [tonejs-instruments](https://github.com/nbrosowsky/tonejs-instruments) by Nicholaus Brosowsky, [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
- Bass, ukulele (nylon guitar), violin, cello and trumpet: FluidR3 GM soundfont via [midi-js-soundfonts](https://github.com/gleitz/midi-js-soundfonts), [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
