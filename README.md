# iBottle
#### A Hydration Management Platform
A smart water bottle that satisfies the needs of a variety of groups, including athletes that want to enhance performance, dieters that want to achieve their weight goals, as well as elderly in group homes or living alone that often suffer from dehydration. Since people actually have low awareness in achieving the right water consumption for their body where water intake differs from one person to another. In addition to this, people may have problems remembering to drink, while others may ignore drinking enough water due to the rush of everyday life.
***
Folder containing presentation slides :
https://drive.google.com/drive/folders/1NP0jgBJHgOfpTQxn8js35-GhJ3vMZImU?usp=sharing
***
### Submitted by Group #5:
* Eman Ateya - https://github.com/Emannegm9
* Hassan El Rashidy - https://github.com/HassanELRashidy
* Mariam Farghaly - https://github.com/Mariamfarghaly99
* Mohamed El Shenawy - https://github.com/Shenawy7
* Mohamed Hassan - https://github.com/MohamedGamal99
* Salma Wafa - https://github.com/SalmaWafa

### Under the Supervision of:
Dr. Mohamed Shalan

### Motivation 
* Research area is relatively new
* Ensuring proper hydration
* High potential of improving life of individuals with prevailing diseases
* Maintaining a healthier lifestyle
* Achieve goal of “Sustainable Procurement”
* Fill in literature gap and potential to contribute

# System Architecture
![Picture9](https://user-images.githubusercontent.com/75340968/154065881-a224d389-52ea-4c36-b90c-73d92cde419a.png)

# Software Design
![Picture99](https://user-images.githubusercontent.com/75340968/154066056-93e3f951-959b-4c02-804b-479560d31eff.png)

# Prototype
![Screen Shot 2022-02-15 at 2 32 47 PM](https://user-images.githubusercontent.com/75340968/154062831-96826aea-cd7f-4904-8e58-4077f21a87d0.png)

# Mobile Application Frontend Development
* Framework: React Native 
* Code Editor: VS Code
* IDE: XCode 
* State-management: Overmind
* GitLab
* Testing: iOS Simulator and iPhone

# App Storyboard 
![Picture1](https://user-images.githubusercontent.com/75340968/154060771-c0b98ca2-86c6-4cd2-94fb-29e655faa1d1.png)

![Picture2](https://user-images.githubusercontent.com/75340968/154060784-06148fe6-d31e-4969-95e8-206c18e2bc7e.png)

# Database ER Diagram
![Picture999](https://user-images.githubusercontent.com/75340968/154068254-1bee43c8-d158-4ed1-bbf0-b36e5cd0d15a.png)

# App Demo
https://youtu.be/lejtm_nlhbU

## Agile Developement Methodology 
### First Sprint
#### Software Backend
* Subscribed to a webhosting service 
* Implemented initial database tables and APIs

#### Hardware
* DS18B20 "Digital Temperature Sensor" 
* Transmitted data using Bluetooth module 
* Used STM32 microcontroller
***
### Second Sprint
#### Software Frontend
* Developed Mobile App
* Implemented home tab, bottle tab, setting tab, water intake form, bottle pairing and communication
#### Software Backend
* Restructured database tables and APIs
#### Hardware
* Set up Arduino Nano33 BLE Sense with the built-in LPS22HB temperature and pressure sensor
* Send readings app and display
***
### Third Sprint
#### Software Frontend
- Completed the UI implementation of all screens
- Google Login- UI and Google Services integration
- Overmind Implementation
#### Hardware
* Changing Baud Rate since value was staying constant after a long amount of time
* Use of one sensor: using LPS22HB only and eliminated HTS221 sensor since sensors affected each other which caused a massive fluctuation in values
***

# References
* https://datasheets.maximintegrated.com/en/ds/DS18B20.pdf
* Cico, Orges, and Betim Cico. "Reliable IoT Systems for Improving Quality of Battery Life Through The Exploitation of Cloud, Mobile and BLE Technologies. Case Study: Battery Charge Protect." 2020 9th Mediterranean Conference on Embedded Computing (MECO). IEEE, 2020.
* Majchrzak, Tim. Comprehensive Analysis of Innovative Cross-Platform App Development Frameworks (2017). Retrieved September 21, 2021, from https://scholarspace.manoa.hawaii.edu/bitstream/10125/41909/paper0760.pdf
* Radhi, Ahmed. (2015). Data Acquisition and Controlling System by Using Mobile Phone Based Microcontroller via Bluetooth. 319-339
* Harris-Fry, N. (2021, June 8). Best running water bottle: Top bottles for runners to quench their thirst. Expert Reviews. Retrieved September 21, 2021, from https://www.expertreviews.co.uk/fitness-equipment/1408654/best- running-water-bottle-quench-thirst
* Shaban, Mostafa. (2016). Risk factors of dehydration among elderly in Egypt. 10.13140/RG.2.2.26607.87208.
* W. Cheungpasitporn, S. Rossetti, K. Friend, et al. (2016) Treatment effect, adherence, and safety of high fluid intake for the prevention of incident and recurrent kidney stones: asystematic review and meta-analysis. J Nephrol.
* Borwankar, A. A., Ladkat, A. S., & Mhetre, M. R. (2015). Thermal Transducers Analysis.
* Make your first IOT react native ... - blog.bam.tech. (n.d.). Retrieved November 4, 2021, from https://blog.bam.tech/developer-news/make-your-first-iot-react-native-application-with-the-bluetooth-low-energy.
* https://datasheets.maximintegrated.com/en/ds/DS18B20.pdf 
* https://docs.arduino.cc/static/b9f5a45249d42194eaff8b0d803b71d0/ABX00031-datasheet.pdf
* https://infocenter.nordicsemi.com/pdf/nRF52840_PS_v1.1.pdf 
* https://pdf1.alldatasheet.net/datasheet-pdf/view/880681/STMICROELECTRONICS/LPS22HB.html 
* https://dlnmh9ip6v2uc.cloudfront.net/datasheets/Prototyping/TP4056.pdf
* https://www.mouser.com/datasheet/2/315/Panasonic-Battery-Energy_catalog-182686.pdf
