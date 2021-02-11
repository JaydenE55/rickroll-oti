# RickRoll-OTI (Over The Internet)
RickRoll-OTI allows you to connect to an ESP8266 using Blynk and trigger a buzzer that plays "Never Gonna Give you Up" By Rick Astley.

## Getting Started
1. Download the Blynk App from the Google Play or App Store and install it.
2. Create an account. 
3. Create a new project, once youve created your project you shoulve been emailed an authorization key, save that for later.
4. Click the + button on the top right and add a button.
5. Click that button and change the output pin to V1.
6. Download the code and the required dependincies located below.
7. Edit the Auth Key, WiFi Name and Password, if needed also change the buzzer pin.
2. Then flash the ESP with the edited code.
9. The ESP should restart and start playing the tune.
10. Wait for it to stop then open the Blynk app and click the play icon, then click your button to trigger the tune wirelessly from your smartphone.

## WiFi Connection
This device will require internet access at all times to function properly. The ESP will only need internet access to comunicate with Blynk's server's. I am in no way interfering with your connection to and from Blynk.

## Remote control over WiFi
1. Power on the Rick Flash and wait until the song stops playing.
2. Open the Blynk app 
3. Select the play button to start the connection
4. Click your Button
5. Watch the ESP start playing the Rick Roll Tune

## Requires Dependincies
|                    |                                                                 | 
|--------------------|-----------------------------------------------------------------| 
| ESP8266 Libraries  | https://www.amzn.com/dp/B08B4P67N8/                             | 
| Blynk Library      | https://www.amzn.com/dp/B07Q42WH3C                              | 
| ESP8266 Board      | http://arduino.esp8266.com/stable/package_esp8266com_index.json |

## Bill of Materials
|     |                                   |                                                                                                                         | 
|-----|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------| 
| Qty | Description                       | Link                                                                                                                    | 
| 1   | ESP8266/12E                       | https://www.amzn.com/dp/B08B4P67N8/                                                                                     | 
| 1   | Piezo Buzzer                      | https://www.amzn.com/dp/B07Q42WH3C                                                                                      | 
