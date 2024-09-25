<img src="https://user-images.githubusercontent.com/23436953/166644338-278662d5-1cc5-4bfb-ad64-866e87dd789a.png" alt="Calido" width="300"> 

> [!IMPORTANT]  
> **This project is deprecated. Please see the [OpenCalido](https://github.com/LucasPlacentino/OpenCalido) Project (ESP32 based Smart Thermostat with Matter)**
> [https://lucasplacentino.github.io/OpenCalido/](https://lucasplacentino.github.io/OpenCalido/)

---------------------------

# Calido - Open Smart Thermostat and Smart Home Controller based on a Nordic Semiconductor Thingy:91

**Project can be found [here (Electromaker.io)](https://www.electromaker.io/project/view/calido-open-source-smart-thermostat-and-home-controller).**

A *Make it smart with Nordic Thingy:91 (Electromaker.io)* contest project.

Built with a [Thingy:91 (nrf9160)](https://www.nordicsemi.com/Products/Development-hardware/Nordic-Thingy-91).

## Description/Use
Calido was built to monitor and control a house temperature, humidity, vibrations, overall air quality and its heating system, to control other smart-home devices and to notify the user.

It can send data via MQTT to Home Assistant for user monitoring and automations.

Calido can also use its BLE to fetch data from various external sensors.

Calido can send signal via its GPIOs to relays, for example to turn on and off home heating and cooling.

TinyML can be run on the device to learn and later predict the user's preferred home teperature based on time of day and outside climate.

Data can be sent to Edge Impulse to process it, it could for example be trained with vibrations data to predict earthquakes. This data could be massively crowdsourced in high seismic activity areas to help those regions or countries better predict and prevent future natural disasters.

## Set up
1. Update your Thingy:91's firmware ([instructions here](https://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/ug_thingy91_gsg.html#getting-started-with-thingy-91)).  
<img src="https://user-images.githubusercontent.com/23436953/167595520-1b0fb046-ba61-4232-8d08-11c32154893b.JPG" alt="Get Started with Thingy:91" width="700">

2. Put your included iBasis SIM card in your Thingy:91, and register it in nRF Cloud ([instructions here](https://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/ug_thingy91_gsg.html#activating-the-ibasis-sim-card)).  
<img src="https://user-images.githubusercontent.com/23436953/167595594-336eebea-66d2-4c8c-8ea5-b52606a671d2.JPG" alt="nRF Cloud SIM card registering" width="500">

3. Build the firmware.

4. Flash it onto your Thingy:91.

5. Have your MQTT Broker up and linked to HomeAssistant  

6. Connect Edge Impulse [docs.edgeimpulse.com/nordic-semi-thingy91](https://docs.edgeimpulse.com/docs/development-platforms/officially-supported-mcu-targets/nordic-semi-thingy91)  
Get the Edge Impulse project at [Calido's EI project page](https://studio.edgeimpulse.com/public/104522/latest).  
<img src="https://user-images.githubusercontent.com/23436953/167595648-7dbdf51b-cb6a-4e83-b741-d9edbbb47db1.JPG" alt="Calido's Edge Impulse project page" width="800"> 


## Contributing
Please be welcome to contribute [here](https://github.com/LucasPlacentino/Calido/tree/dev).

----------------------

## Details
### UI
<img src="https://user-images.githubusercontent.com/23436953/166644193-d2915bdf-1988-400b-9aa1-ebb900e805da.png" alt="Calido UI" width="300">

----------------------

## License
Licensed under an [Apache-2.0 license](https://github.com/LucasPlacentino/Calido/blob/main/LICENSE).
