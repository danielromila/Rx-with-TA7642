# Rx-with-TA7642
Rx with TA7642
You can see it in function at: https://www.youtube.com/watch?v=vMCvm132ae8

I tried to love this 3 point IC radio, but there is not much to do with it. Any attempt to add some regeneration altered the radio too much. Many people tried to make it a regenerative radio, but those who succceeded in fact transformed it into a one transistor radio and no longer use its AM and amplification function, so what's the point? This IC simply wants the output to be decoupled with 0.1 micro F at the ground, so there it goes down the drain any regeneration.

What I did was to put a FET repeater in front. While apparently this loses some signal, actually it made the signal a little stronger, due to the high impedance seen now by the inductor. I used a 470 uH molded inductor, which has a ferrite perfectly fine for medium waves. The use of this repeater arrangement also allowed me to have the variable capacitor with a terminal at the ground.

The selectivity is bad. One must be very desperate to use it as radio.
