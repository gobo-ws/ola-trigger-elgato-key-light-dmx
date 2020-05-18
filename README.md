**OLA trigger config to control Elgato Key Light & Key Light Air with DMX (Art-Net, sACN or via DMX input)**

**Requirements**

* [OLA](https://www.openlighting.org/ola)
* [curl](https://curl.haxx.se)
* [Elgato Key Light](https://www.elgato.com/en/gaming/key-light) or [Key Light Air](https://www.elgato.com/en/gaming/key-light-air)


**Installation**
  
* Download the [elgato_key_light.conf](elgato_key_light.conf) and edit the configuration section

[OLA trigger documentation](https://www.openlighting.org/ola/advanced-topics/ola-dmx-trigger/)

**Usage** 

* Before running ola_trigger, make sure that olad is running and the universe has been configured with a DMX512 source.  
The config file is provided on the command line:

`ola_trigger elgato_key_light.conf`
