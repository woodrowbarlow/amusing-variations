# ARS340 Final Project

Made with pd-extended. Launch `main.pd` first.

When launched, it immediately generates one riff of music containing two layers. Press the big toggle to play that riff on a loop. The controls on the left modify the riff: you can change the key signature and set octave offsets for each layer. The buttons beside the offset radio will re-generate each layer with a new riff. These controls can be fiddled with live.

My next step will be to introduce an "evolution" algorithm that very slightly mutates the generated riff over time. I would also like to create a sort of percussive track on top, whose cycle is not the same length as the motif riff.

The actual synthesis technique is very crude at the moment. I plan to create a proper ADSR envelope using line objects and layer in a little bit of frequency modulation.

Something seems to be wrong with the big loop; some samples get randomly dropped. Also, adjusting the speed tends to mess up the current playback momentarily; everything will eventually "settle in" when the loop starts again.

Eventually, playback parameters will be adjusted automatically by mapping the five power bands of my brainwaves (using a Muse Brain Sensing Headband); that is, my brain will automatically "play" this "instrument".