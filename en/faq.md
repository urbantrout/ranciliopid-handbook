---
title: FAQ
parent: EN - Manual
has_children: false
nav_order: 7
---

# FAQ

Question: The warning „emergency stop“ appears on the display at 120°C, why?

> The emergency shutdown kicks in at 120 °C in order to prevent overheating of the machine, which caused by onforseen behaviour of the software or hardware. After the temperature has dropped below 100 °C, the PID will resume normal operation. When in steam mode, this message will apear regulary (temp. above 120 °C), but doesn't influence the function of the machine since steam is not controlled by the PID.  


Question: why does the heating SSR not function properly?

> A common mistake is that the signal pin is not connected to "+", but to the "-" connector of the SSR. Please double check if you have connected the SSR correctly 


Question: My PID values don't seem to work, e.g. the temperature overshoots

> Please have a look at our PID-value list [PID-values](https://manual.rancilio-pid.de/de/customization/pid-werte.html), where many working values are listed for cold-start, normal operation and brew-detection. In case you want to ask for help in the chat, please explain the exact problem (best would be to also send the values from Blynk).


