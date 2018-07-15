# PSoC_Grbl Native USB
PSoc5 Port of Grbl CNC Controller

This is a port of the amazing [Grbl CNC Controller](https://github.com/gnea/grbl) firmware to the [Cypress PSoC 5 CPU](http://www.cypress.com/products/psoc-5). Grbl is targeted at the Atmel ATMega328P and ATMega2650 8 bit CPUs.  The PSoC 5 is a much more powerful CPU and is a mixed signal processor. 

This version uses the native USB feature of the PSoC. This removes the need for a separate USB/TTL device and allows for very high transfer rates. You can choose any baud rate in your sender program up to 2Mbps.

You can read more at this blog post and [this blog post](http://www.buildlog.net/blog/2017/02/psoc-5-port-of-the-grbl-1-1-cnc-controller/).


![enter image description here](http://www.buildlog.net/blog/wp-content/uploads/2017/02/PSoC-4-M-Series-Lego1.jpeg)

![enter image description here](http://www.buildlog.net/blog/wp-content/uploads/2017/02/step_pulse.png)