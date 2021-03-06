# Low cost, high efficiency, step-up DC-DC converter  
> [ input min 0.7V or 0.85V - output 3V, 3.3V or 5V - boost efficiency max 95% ]

![see](https://c1.staticflickr.com/9/8018/7257815024_a1fe84bef0_b.jpg)

This is an easy and tiny way to manage variable and small input voltage with your MCU project.
Using the [LTC3525](http://www.linear.com/product/LTC3525) you always get constant output voltage whatever your input voltage. Even at 1.2V as input the step-up keep >85% of the energy.

* **Up to 95% Efficiency**
* **Ultra small case 6x11mm**
* External solar panel input **with diode protection**
* Input startup voltage at 0.7V or 0.85V
* Plug external small battery or a super capacitor
* Output Disconnect and Inrush Current Limit
* Fixed Output Voltages of 3V, 3.3V or 5V
* Delivers 65mA at 3V from a 1V Input
* Delivers 60mA at 3.3V from a 1V Input, or 140mA at 3.3V from a 1.8V Input
* Delivers 175mA at 5V from a 3V Input
* <1μA Shutdown Current

<!-- ![efficiency](http://cds.linear.com/image/6470.png) -->

# The PCB
![The PCB board](https://raw.github.com/evaletolab/evaletolab-tiny-dcdc/master/docs/pcb.png "v0.0")


**THIS IS ALPHA SOFTWARE/HARDWARE AND SHOULD BE TREATED ACCORDINGLY.**
**IT IS FUN TO GET RUNNING, BUT EXPECT THINGS TO BE BROKEN.**
 
## License
GPL3
> Copyright (c) 2012 Olivier Evalet (http://evaletolab.ch/)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
