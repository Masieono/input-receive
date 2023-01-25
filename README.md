# input-receive
firmware for the input receiver of a eurorack modular system

This is primarily for an ESP32 or similar microcontroller embedded on a eurorack-style faceplate. The eurorack module hosts inputs that get sent to a raspberry pi controlling an LED matrix. 

Inputs:
- 3 Digital inputs
  - Can be set to gate or trigger mode
  - Each input has a capacative touch input routed in an OR fashion.

- 3 CV inputs
  - Can be set to 5V or 10V unipolar or bipolar
  
- Stereo audio input
  - Can be set to L/R or 2 audio channels
  
Other Features:
- Program and settings interface, likely requiring a small screen and click knob
