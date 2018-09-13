# hts-engine-world

This software contains an integration of the WORLD vocoder (https://github.com/mmorise/World) and the hts_engine API-1.10 (http://hts-engine.sourceforge.net). It also uses functions from the Speech Signal Processing Toolkit (SPTK) (http://sp-tk.sourceforge.net/).

The main modification can be found in [lib/synthworld.cpp](lib/synthworld.cpp).

Use

./configure

and

make

to create bin/hts_engine.

You have to call hts_engine with the option -w to use the WORLD vocoder, otherwise the default vocoder will be used.

Michael Pucher michael.pucher@oeaw.ac.at
