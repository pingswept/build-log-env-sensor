My plan is to build something like 10 or 20 small internet nodes that lurk around my house, measuring temperature and humidity. Once a minute, they wake up, read the sensors, and post the data to an RPi 4 sitting on my desk. Then I revel in data.

![A small sensor PCB plugging into a USB wall receptacle](initial-concept-sketch.jpg?raw=true "Initial concept sketch")

### Commercial products ###

* https://buythermopro.com/product/thermopro-tp90-wireless-indoor-hygrometer-thermometer-alexa-compatible/, $45 on Amazon, but looks like there is no aggregation of data between nodes. Accuracy ±1°C and ±3% RH.

### Sensor candidates ###

* Sensirion SHT35-DIS-F2.5KS, accuracy ±0.1°C and ±1.5% RH, $9.10 each in qty.10, 8-VFDFN package
* TI HDC1080DMBT: accuracy ±0.2°C and ±2% RH, $2.31 each in qty. 10, 6-WSON package
* TI HDC2080DMBT: accuracy ±0.2°C and ±2% RH, $2.51 each in qty. 10, 6-WSON package

### Sensor modules ###

* SHT35 with passives on a tiny PCB: https://www.aliexpress.com/item/33051448440.html, $8.30 each, lead time 5 weeks
* Grove SHT35 module: https://www.amazon.com/gp/product/B07JQH5MPJ/, $17.99 each, lead time 2 days
