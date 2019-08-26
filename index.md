
##  Google Summer of Code 2019, with Berkman Klein Center for Internet and Society, Harvard University

#### Ayanda : Ayanda is an Open Source Android Library that makes it easy to discover nearby devices and share files through a simple API.
##### Atul Nair | Sabelo Mhlambi

## Overview:

Ayanda is an Open Source Android Library that makes it easy to discover nearby devices and share files through a simple API. Ayanda is meant to detect nearby devices using WiFi and Bluetooth technology. Currently the Ayanda library uses Wifi-Direct and Bluetooth to pair to nearby enabled Android devices and send files between devices. This library can be useful for creating apps that can respond to nearby users and provide proximity based services. It also is essential in allowing for Offline communication in a situation such as the internet is censored or shutdown completely -- A mesh network can be built on this.

## Major Areas of My Contributions and Goals Achieved

### Testing :

 - Tested the bluetooth functionality on various physical android devices.
 - [Screenshots](https://drive.google.com/drive/folders/0B7nXUQ68yx8Qfk1kQWNSSWQ0aXdHVHBCTzYyVHY2WW1abk9MUE5fekhVbjBYRDBTRE1ETk0?usp=sharing)
 - Tested Devices :

| Device                      | Android version   
-----------------------------------------------------    
| Poco F1                     | Android 9.0  
| Moto G5S plus               | Android 8.0  
| Redmi note5 pro             | Android 9.0  
| Oppo A37                    | Android 5.1.1  
| Vivo y53                    | Android 6.0  
| Moto G5S plus               | Android 8.0.1  
| Samsung J5 pro SMJ530F      | Android 7.0  
| Motorola one power P30 note | Android 9.0  
| Oppo A37F                   | Android 5.1  
| Lava Z61_2GB                | Android 8.1.0  
| LG K10                      | Android 8.1  
| Lenovo A7020                | Android 6.1  
| SM-G611FF                   | Android 9  
| Realme 1                    | Android 8.1.0  
| Nokia 2.1                   | Android 9 go e  
| VivoY81                     | Android 8.1.0  
| Samsung galaxy Note 4       | Android 6.0.1  
| Moto g6                     | Android 9  
| Samsung j6                  | Android 9  
| Honor Holly 3               | Android 6.0  
| Lenovo Z2 plus              | Android 7.0  
| Redmi note4                 | Android 7.0
 
 
### Unit testing :
Unit tests for core ayanda classes and ui elements are written using Roboelectric. 
 - [unit tests for core ayanda classes](https://github.com/sabzo/ayanda/pull/48)
 - [unit tests for ui elements](https://github.com/sabzo/ayanda/pull/46)

### Demo apps using ayanda :
   The main objective is to document real world use cases of Ayanda Library.
 - Chat app : It uses Ayanda library for offline communication.
 - Tic-tac-toe : A multiplayer game using Ayanda library.

## Important Links
**Repositories:**  

 - [Ayanda](https://github.com/sabzo/Ayanda)

**Demo repositories:** 

 - [Chat app using Ayanda](https://github.com/atulnair/Chat-app-using-ayanda)
 - [Multiplayer Game using Ayanda](https://github.com/atulnair/Tic-tac-toe-using-Ayanda)

## Credits

First of all, this would not have been possible without the support of my mentor and friends. So a huge shout-out to my mentor Sabelo Mhlambi and to my friends.

Next, I would like to thank Google for organising such an amazing program for students who are passionate about coding and giving them an opportunity to gain some hands-on experience.

Last but not the least, I would like to thank my family for teaching me that it’s okay to fail, to fall and hit a dead end, but never give up.

### Contact
Contact me at [atulnair2202@gmail.com](mailto:atulnair2202@gmail.com) if you have any queries regarding GSoC.
