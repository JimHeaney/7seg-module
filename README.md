# Large 7 Segment Module

## Summary
Many hobbyist projects can benefit from the addition of a numercial output, most commonly achieved with 7-segment displays. The issue, though, is that these displays consume a lot of GPIO to run. While multiplexing can be implemented to mitigate this, this'll increase both code and wiring copmlexity and will limit the use of certain types of code (such as the use of blocking functions).

To mitigate this, I have developed an infinitely-chainable large 7-segment display that can be used with any microcontroller, without the need for architecture-specific librarites. An infinite number of digits can be controlled with only 2 GPIO, with the use of an additoinal 2 allowing for additoinal control, such as dimming and more rapid updates. Each module then independently takes care of driving its 7-segment display, freeing up the main microcontroller for other tasks or to use blocking code. The microcontroller can even be totally disconnected, and the displays will maintain their information until powered down.

Each digit is nearly 2 inches tall, allowing the display to be read easily from over 20 feet away. Modules can directly plug into each other, or strung together with standard jumper wires to space out numbers or create another line. All modules support hot-plug, allowing for the size of the display to be changed on the fly. For protection against short-circuits, each module integrates a self-healing polymer fuse that will safely disconnect the impacted module in the event of a short, without interrupting the operations of the other modules. Modules can easily be mounted into a larger project with the integrated M3 threads above and below each digit.

An optional input board at the start of the chain allows the modules to be used with 3.3v or 5v logic levels, as well as breaks out the connecitons to a standard pin header, for easy connection to hobbyist development boards. 


### More information can be found on the [GitHub Wiki](https://github.com/JimHeaney/7seg-module/wiki).


## Current Release
There are no stable versions for release. The latest WIP is Version 1.1

## Current State
Version 1.1 is currently in testing.

## Instructions & Further Documentation
[See the wiki on GitHub!](https://github.com/JimHeaney/7seg-module/wiki) 

## Photos & Media
Coming Soon!

## Support Me
You can buy me a coffee [here](https://www.buymeacoffee.com/jimheaney)!

## License
This project is licensed under the Creative Commons 4.0 Attribution-NonCommercial-ShareAlike. For more information, click [here](https://creativecommons.org/licenses/by-nc-sa/4.0/).

If you are interested in using this project under a different license (e.g. for commercial use), please contact me. 

