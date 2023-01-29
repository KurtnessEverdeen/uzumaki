# uzumaki
![Defined as:](https://filmschoolrejects.com/wp-content/uploads/2019/09/B933157C-8327-4109-9F1A-69A6880A1D3E.jpeg)
Or simply "a spiral" I do not watch naruto.

This pd patch generates customizable visualizations which are no more than a battle between oscillator and samplerate.
Much like a fan blade stops when hit with a strobe light spawnpoints are stopped, and a new shape is born from the cubes. 

It's vanilla and gem, so hopefully that makes setup more universal.

# Controls

- X/y Freq: control the oscialltors on the screen
- x/y phase: control the phase between osciallators, 1/4 phase difference draws a circle
- grav pos/pow: allows for a point at which the cubes fall towards, and how hard
- paritcle speed: rate at which it all moves
- particle size: bigggg small
- outer radius: increase radius/size of oscillations
- snapshot delay: this breaks up when the oscillators are sampled- drawing lines between points
- age depth: cubes have life spans, and they grow or shrink based on their time in this realm
- max age: their time till they die
- fade point: cubes are only visible 100% at this percentage point in their life, they fade in and out on either side
- fill thresh: at some point they may change from wireframes to fully drawn (though maybe transparant)
- pulse size: cubes can change size in oscillation, this is how much
- pulse depth: oscillation of pulse size, in msec
- red/green/blue: this is the starting color cubes are given
- redx/greenx/bluex: this is the amount each color value changes until the end of their time
- randomload: this cycles preset values for all of the above, you can save edit or sequence these "states", see below
- next/back: loads the next or previous "state"
- save: saves the current settings above to file to create a new uzumaki state
- overdub: when this is checked all settings wil be saved to the current # state that is loaded, this is an edit feature
- trans speed: this controls how fast settings are transitioned between states
- linger: this is how long (from the start of the transition) a state will stick around, before the next one is loaded

# Sequencer Controls
While randomly loading from a list of interesting states is fun maybe theres more to be had in designing a little show.
You can save/load state sequences with this allowing for a more controlled performance, including the state, transition speed, and linger time

- add to end: add the current sequence, trans speed, and linger time to the seq
- del last: remove the last state from sequence
- save/load: saves and loads sequeneces from file
- play seq: plays the currently loaded or created sequence of states
- clr seq: clears it out
