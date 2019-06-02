# 8bit
About 8-Bit Music Macro Language.

## Limitations
- No volume, no pitch bending

## Track Limit
You get 8 tracks (0-7).  Each track can only play one note at a time.

## Waveform Character Strings
Character strings are 64 or 128 characters long in hexadecimal (32 or 64 bytes).  Each byte is one sample.  Additional parameters (may not have been available originally):
1. Attack 0-127
2. Decay 0-127
3. Sustain 0-127
4. Release 0-127

## You Get These Sound Lengths
| # | Meaning       |
|---|---------------|
| 0 |	1/32          |
| 1 |	1/16          |
| 2 |	dotted 1/16   |
| 3 |	1/8           |
| 4 |	dotted 1/8    |
| 5 |	1/4           |
| 6 |	dotted 1/4    |
| 7 |	1/2           |
| 8 |	dotted 1/2    |
| 9 |	1             |

## You Get These Octaves
3 Octaves!

1. Octave 3 (-)
2. Octave 4
3. Octave 5 (+)

## You Get These Tempos
1. 30 BPM
2. 60 BPM
3. 90 BPM
4. 120 BPM
5. 150 BPM
6. 180 BPM
7. 210 BPM

## You Get These Pitches
- A,A#,B,C,C#,D,D#,E,F,F#,G,G#
- And of course `R` for Rest.

### References
* https://en.wikipedia.org/wiki/Music_Macro_Language
