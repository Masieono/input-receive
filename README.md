firmware for the input receiver of a eurorack modular system

I am currently planning on using a STM32 MCU with various peripherals hooked to it.

Inputs:
- 3 Digital inputs
  - Can be set to gate or trigger mode
  - Each input has a capacative touch input routed in an OR fashion.

- 3 CV inputs
  - Can be set to 5V or 10V unipolar or bipolar
  - Attenuverters allow for offsetting signal much like a maths module
  
- Stereo audio input
  - Can be set to L/R or 2 audio channels
  
Other Features:
- Program and settings interface, likely requiring a small screen and click knob
- USB/UART interface, for pushing firmware and accessing images from USB drive


