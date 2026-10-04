# cc0-obxf-multisamples

380 multisampled synthesizer instruments, rendered from **CC0-licensed OB-Xf patches**, as FLAC files with ready-to-use SFZ mappings.

Each folder under a category contains one instrument: a `.sfz` file and five 24-bit/48 kHz stereo FLAC samples (one every octave, about 4 s held + 1.5 s release tail, velocity 100). The SFZ files map each sample to a key range around its root note and carry a per-region `volume` so that all instruments sit at a similar level. Any SFZ player (sfizz, sforzando, ...) can load them. Sustained patches have no loop points; use your sampler's loop tools if you need endless sustain.

## License

The rendered audio and the SFZ files are dedicated to the public domain under **CC0 1.0 Universal** (see `LICENSE`) to the fullest extent of the rights held by the person who made these renders. Every input patch declares `license="CC0"` or `license="CC0 / Public Domain"` in its own file metadata (see `SOURCES.md` for the author and license text of every patch). The audio was rendered with OB-Xf 1.0.3 (GPL-3.0, https://github.com/surge-synthesizer/OB-Xf). Under the GNU GPL FAQ ("GPLOutput"), the copyright status of a program's output inherits that of its input unless substantial parts of the output are copied from the program itself; OB-Xf generates its sound algorithmically and ships no sample or wavetable data. No warranty of any kind.

## What is not included

Drum, percussion, FX, atmosphere and soundscape patches, and patches without a license declaration in the file.

## Categories

- Basses: 45
- Bells: 4
- Brass: 31
- Guitars: 17
- Keys: 86
- Leads: 43
- Mallets: 9
- Organs: 19
- Pads: 64
- Plucks: 12
- Strings: 22
- Voices: 11
- Winds: 17

See `SOURCES.md` for the full list with credits.
