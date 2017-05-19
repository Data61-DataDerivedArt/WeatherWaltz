# Weather Waltzes

This program generates a waltz from weather data.  It uses Mozart's
'Musikalisches Würfelspiel K.V. Anhang 294d (516f), Wien 1778' as
implemented by Martin Tarenskeen [WaltzDice
1.2])http://members.tele2.nl/m.tarenskeen/tmp/DiceWaltz-1.0.zip)

The idea is to grab one (or two) days worth of humidity and pressure
data from an [Australian Bureau of
Meteorology](http://www.bom.gov.au/climate/data/stations/) dataset,
use the humidity data to generate the dice that selects the snippets,
then 'ominise'  the harmonies in response to the gradient of the mean
sea-level pressure curve.

The faster pressure  falls, the more ominous the music will sound; if
it is rising or steady, the music is unaltered.

The music is ominised a bar at a time by adding parallel music 2 or 4
semitones below the main music.

A waltz is 24 bars long; if you select only one day, each hour will
correspond to one bar.

To use the program you will need a dataset and the [Lilypond](http://lilypond.org/) program;
to hear the music you either need to play it on an instrument, or feed
the generated MIDI into a program like timidity.
