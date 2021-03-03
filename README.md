# Shouty Cat
## Restive Filter Effect Module
This mod is based on the Rattle Crow pedal by Lastgasp Art Laboratories. It's been modified to work better with synths/toy keyboards and to be a bit simpler and more flexible.

# Notes
* Based on how flexible the TL072 is, I expect this will work with a wide range of voltages. It definitely works at 9 and 12 volts as I was able to test with those with no issue. 
  * 4.5 volts wasn't quite enough, but you might get as low as 6-7 volts. 
  * I wouldn't go much higher than 12 volts but I think technically the IC can handle 18 if you're brave? I dunno what keyboard uses over 12 volts though so I figured it was a moot point.
* See schematic/PCB for different values for the "Cuts." These capacitors can filter/clip different frequencies to tweak the effect to better suit different applications. Cut 1 creates a kind of clipping effect, while Cut 2 is essestially a Low Pass Filter.
  * I have added some additional solder points to the PCB to easily connect switches for connecting/disconnecting the Caps.
  * Experiment, but I expect by using pots/crossing these points you could do some really wacky things.
  * They can also be left unconnected to let all sound through. The original uses 58pF caps, but I didn't hear any difference with those caps and nothing during my testing.
*  The "Scream" Frequency control feel much better with a Reverse Log pot, but for cheaper builds a linera pot works fine.
*  The "Shout" Sensitivity control is adjusted for high input signals coming off of a synth/toy keyboard. Tweak this as needed for lower level signals like a guitar/line level input. (The original pedal uses a 50k pot for reference).
*  The original pedal has a Level control that can be installed by connecting a 10k Log pot. 
  *  Wire Output from board to Pin 2 of pot; wire Ground from board to Pin 1 of pot.
   
#### Not required or expected by any means, but if you like it you can use the Sponsor button to buy me a beer!
