# Lupstrument
This is a project within the "Music Informatics Seminar" held by Winfried Ritsch at the Institute of Electronic Music and Acoustics, Graz. 

The idea behind this project was to build a multichannel looper instrument
that can be played solely by acoustic and haptic feedback. The interface
design doesn’t contain any visual feedback and enables the performer to
play entirely by ear.
Furthermore, the instrument integrates concepts of the musique-concrète
technique that was developed by Pierre Schaeffer in the 1950s. [1] In
contrast to a traditional looper pedal, this instrument allows drastic live-
modifications to the recorded and looped sound material. The possible
modifications include selecting the start and end of the loop within the
recorded audio material, as well as playing the loop reversed and at altered
speed.
The concept has been realised with the open-source hardware platform "Bela"
[2], with software being developed in the computer music language Pure
Data. 
A video were I recorded a first experimental piece can be found on vimeo [3].

The _main.pd file is the top layer which shows all controls and buttons as they are layed out in my hardware box. The looper core is contained in loopclip.pd. Each channel is basically a loopclip.pd and can be edited when selected by one of the buttons.

[1] https://en.wikipedia.org/wiki/Musique_concr%C3%A8te

[2] https://github.com/BelaPlatform/bela-hardware

[3] https://vimeo.com/277252836
