# NiceRF SX1280 Mikrobus compatible boards

A number of my projects use Mikrobus compatible boards. They allow the function of the board to be readily changed without requiring a re-design or separate board.

Most of these boards are breadboard friendly so can be used on standard 0.1" spacing breadboards, stripboards or matrix boards. The standard layout of a Mikrobus board is 2 rows of 8 pins. My boards extend this to 2 rows of 10 pins. The extra 4 pins are often needed for LoRa devices.

The Arduino boards I was using for the SX1280 distance testing accept a Mikrobus board so the function of the board can be easily changed for Hope RFM9x, Dorji DRF127x or as in the tests the NiceRF SX1280 LoRa module.  

There are printouts of the Mikrobus board schematic and PCB layout, be sure to fit the antenna connection to the right place. 

The Mikrobus boards I used are available from;

[http://www.loratracker.uk/](http://www.loratracker.uk/)

Note the SX1280 Mikrobus board can be used on the standard 2 x 8 pin Mikrobus layout, but the analogu pin needs to be able to be set as digital. If you make LK1 on the board then the SX1280 BUSY pin is connected to AN1.