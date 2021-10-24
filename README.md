# Brenn-Slow-LFO

![Brenn Photo](/Docs/Brenn-Photo.png)

100mm Quad Slow LFO

- 4 Lfo's
- Each has a cycle duration between a few seconds and a few minutes, approx 6 sec 12 minutes
- Each LFO has it's own speed control
- A single global speed control
- CV control for the global speed (not 1V/Oct)
- Each LFO has both unipolar and bipolar outputs

I have been using the lfo for slow evolving movement of sounds, it is not a replacement for a standard lfo, normal tremolo
and vibrato can not be realized with this module.

It is based on the single cell VCO on the LM13700 datasheet, this is a triangle wave with a big step so I added
a LPF to each oscillator.

Contained are schematics & gerber files for pcb fabrication of both electrical aux and front panel. This is sutiable for entry level however a basic level of electronics, soldering, fault finding, and some basic tools are required.


[Schematic](/Docs/Brenn-Schematic.pdf)

[BOM](Docs/Brenn-BOM.pdf)


If you wish to edit in ki-cad the following dependencies are required

 https://github.com/holmesrichards/Kosmo_panel
 
 https://github.com/holmesrichards/aoKicad