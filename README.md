# VL.ILDA
ILDA laser control for VL

Inspired on https://github.com/memo/ofxIlda
Dependencies: 
https://www.nuget.org/packages/VL.2D.Simplify
https://gitlab.com/superbien/vl.2d.simplify

This version provides an audio implementation, but the engine itself is agnostic and can be adapted to any kind of PC -> Beamer communication method.

Some laser beamers work direcly with digital audio input, other models just have ILDA socket connection.
Here you can find a way to make your own DAC_ILDA box.
https://github.com/ffd8/dac_ilda
