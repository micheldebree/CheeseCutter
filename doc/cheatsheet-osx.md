# Cheesecutter OSX Cheatsheet


## Newbie

| Key   | Function |
|-------|----------|
| F10   | Load song |
| F2    | Play song from start|
| F4    | Stop playing |
| Esc (Esc)  | Quit (for real) |

## Navigate

| Key   | Function |
|-------|----------|
| (Ctrl-)Tab | Switch main (sub) window | 
| Alt-v | Sequencer |
| Alt-1/2/3 | Voice 1/2/3|
| Alt-i | Instruments |
| Alt-w | Waves |
| Alt-p | Pulses |
| Alt-f | Filters |
| Alt-m | Commands |
| Alt-d | Chords |
| Alt-Enter | Fullscreen on/off |


## Play

| Key   | Function |
|-------|----------|
| F1    | Play song from marker |
| F2    | Play song from start|
| F3    | Play song from cursor |
| F4    | Stop playing |
| (Shift-)F8     | (Hyper) fast forward |
| Ctrl-1/2/3 | Voice on/off |


## Pattern (alt-v)

| Key            | Function            |
|----------------|--------|
| ??? Backspace  |              Set playback marker |    
| (Shift-)Delete / (Shift-)Fn-Backspace        | Delete row ( and  shrink pattern) |
| (Shift-)Fn-Enter      | Insert row (expand)         |
| Ctrl-Delete       |                 Shrink pattern |
| Ctrl-Q/A      |  Transpose pattern up / down |
| Shift-Enter    | Quick expand pattern|

## Note (alt-v, F6)

| Key            | Function            |
|----------------|--------|
| q2w3er5ty...   | Note                |
| Space          | Clear          |
| + / -          | Instrument   |
| < / >          | Octave              |
| a / 1          | Gate on / off       |
| ,              | Tie note            |
|Ctrl-Space      | Keyjam mode         |


## Song sequence (alt-v, F5)

| Key            | Function|
|----------------|---------|
| F5 | Switch track / note column |
| F6 | Note column |
| F7 | Song overview |
| Ctrl-Enter | Insert row |
| Ctrl-f | Find next empty sequence |

## Instruments (alt-i)
| Key            | Function|
|----------------|---------|
| Tab | Switch data / name |
| Ctrl-L/S | Load/Save current instrument |
| Ctrl-D | Delete |
| Ctrl-C | Copy |

## Wavetable
| Key            | Function|
|----------------|---------|
| Fn-Enter | Insert row |
| Fn-Backspace | Delete row |

## Song properties

| Key            | Function|
|----------------|---------|
|[ / ] | Speed |
|Cmd-F3 | 6581 / 8580 |
|(Shift)-Cmd-F8 | filter preset |
|{ / } | Multispeed |
|Alt-t | Title / Author / Year |

## Load / Save
| Key            | Function            |
|----------------|---------|
| (Ctrl-)F11| (Quick) save song |



# Player

## Command column

|Value|Function|
|-----|--------|
|01-3F|Execute command from command table|
|40-5F|Change pulse table pointer|
|60-7F|Change filter table pointer|
|80-9F|Set chord table pointer|
|A0-AF|Set attack|
|B0-BF|Set decay|
|C0-CF|Set sustain|
|D0-DF|Set release|
|E0-EF|Set global volume|
|F0-FF|Set song speed|

## Command table

| Command     | Byte b     | Byte c | Effect |
| ------------- | ------------- |
| 0       | ?       | ? | Slide up |
| 1       | ?       | ? | Slide down |
|  2      | ?       | ? | Vibrato |
|  3      | ?       | ? | Detune |
|  4      | ?       | ? | ADSR |
|  5      | Speed   | Depth | Lofi vibrato |
|  6      | -       | Waveform | Waveform |
|  7      | -       | - | Portamento on |
|  8      | -       | - | Portamento off |

# How to

Shuffle speed
- Set speeds to alternate between as entry 0 in chord table
- Set song speed to 1

Vibrato1
