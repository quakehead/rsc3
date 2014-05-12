
## Installing

You need to install SuperCollider and the Dr Racket package.

### 1. Installing SuperCollider

Go to https://supercollider.github.io/download.html and download the latest version (3.6.6 as of the time of writing.)

Then follow these instructions per operating system.

#### Linux

- install jack

#### Windows

#### Mac OS X


### 2. Installing oregano

This can be installed in two different ways:
- Either through the command line: `raco pkg install rsc3`

- Or through DrRacket: TODO



## Concepts

You can play notes from instruments on specific tracks.

The purpose of playing notes on different tracks is we can have different filters on different tracks. For example, the melody track can have a low pass filter, and and the drums track could have a delay filter.


- Instrument: This is equivalent to choosing what the note sounds like. There are default instruments (saw wave, piano, etc.) and you can also define your own using samples.
- Note: specifies a key from an instrument, and can be played on a track
- Track: 
- Filters: can be added to a track. The order in which they are added matters.


## Example

- Creating an instrument


  ;; this uses the preset
  (define my-piano (make-instrument 'piano))

TODO:
- use an instrument to play a note on a track.
- add filters to  a track


    (append-effect track3 (reverb-effect 0.5 0.9))
