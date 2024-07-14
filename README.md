Offline Tracker Device concept.


| RF Options |      | Frequency   | Data | Distance |
| ---------- | ---- | ----------- | ---- | -------- |
| Lora       | **** | 915/868 Mhz | 4    | 4        |
| nRF24L01   | ***  | 2.4 Ghz     | 4    | 4        |
| RF         | ***  | 433 Mhz     | 1    | 5        |
| BLE        | **   | 2.4 Ghz     | 4    | 1 - 2    |
| WiFi       | *    | 2.4 Ghz     | 4    | 1 - 2    |


| Distance Measurement | Challenge                                                  |         |     |       |
| -------------------- | ---------------------------------------------------------- | ------- | --- | ----- |
| Signal Power         | Low reliability                                            |         |     |       |
| Ping Time            | Based on the time it took to send and receive a data back. |         |     |       |
| Triangulation        | Multiple trackers must.                                    |         |     |       |
| GPS                  | Expensive, high power consumption                          |         |     |       |


| Direction Determination | Challenge                                                                                |         |     |       |
| ----------------------- | ---------------------------------------------------------------------------------------- | ------- | --- | ----- |
| Multi Frequencies       | Most likely expensive, interference might be an issue.                                   |         |     |       |
| Antenna Array           | Calculation required. High clock speed might be required = Power                         |         |     |       |
| Triangulation           | Might give rough estimation.                                                             |         |     |       |
| Ultrasonic Sound        | Ultrasonic audio, requires multiple microphones, works in close distance (which is fine) |         |     |       |
|                         |                                                                                          |         |     |       |


|     | Other Comments |                                                                                                                                           |     |     |
| --- | -------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | --- | --- |
| 1   | UI             | Screen isn't a must simple LED is fine, can be turned on while tracking.                                                                  |     |     |
| 2   | Mesh           | Mesh might be a good idea, neighboring devices would increase reliability, although means more power.                                     |     |     |
| 3   | Mesh           | Mesh can be done in 2 ways, just relaying anything or like a router might keep neighboring device list with ids.                          |     |     |
| 4   | DIY            | Parts should be easy to get for common Joe                                                                                                |     |     |
| 5   | Existing Tech  | There is a project called meshtastic, exiting network might be utilized in favor.                                                         |     |     |
| 6   | Power          | Tracking devices should be able to run at least a week.                                                                                   |     |     |
| 7   | Portability    | Tracker device, shouldn't be heavy to carry around. Desired form factor is something in between Walkie Talkie / Cellphone to smart watch. |     |     |

|     | Device Identification                                                         |     |     |     |
| --- | ----------------------------------------------------------------------------- | --- | --- | --- |
| 1   | Trackers should have an ID, how to assign these id's are challenge.           |     |     |     |
| 2   | Main device can be paired and can be assigned through.                        |     |     |     |
| 3   | Main device might have a bluetooth or wifi, for configuring through a phone.  |     |     |     |
| 4   | Impersonation might be an issue. Something like a mac adress could be useful. |     |     |     |
|     |                                                                               |     |     |     |
|     |                                                                               |     |     |     |
|     |                                                                               |     |     |     |
	

|     | Expansion                                                                            |     |     |     |
| --- | ------------------------------------------------------------------------------------ | --- | --- | --- |
|     | I have another idea for emergency communication protocol, might be merged with that. |     |     |     |
|     | [Emco](https://github.com/Emco-Project/emco)                                         |     |     |     |
|     |                                                                                      |     |     |     |
|     |                                                                                      |     |     |     |
|     |                                                                                      |     |     |     |
|     |                                                                                      |     |     |     |
|     |                                                                                      |     |     |     |
