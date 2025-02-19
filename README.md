# AFC

## About
This is my place to gather and organize information about Automated Frequency Coordination implementations by various Wireless Networking vendors.

Pull requests are welcome, but any information that you wish to add needs to be well documented using publicly available information, or in other words [[Citation Needed]]. If I know you and you have information to contribute without public documentation, please reach out via social media or any method you prefer.

The formatting of this repo will likely change as I have time to orginize it better, so I'd recommend you link only to the main URL.

For now, here is a table that I've been working on. All of the info below is either publicly sourced or is information that I've verified.

|Vendor          |Model        |6 / 6E / 7|AFC?|L1                |L5 |GPS|Galileo|Glonass|Beidou|GNSS Chipset                                                                          |GNSS Antenna Gain|
|----------------|-------------|----------|----|------------------|---|---|-------|-------|------|--------------------------------------------------------------------------------------|-----------------|
|Arista          |O-435        |7         |Yes |Yes               |Yes|   |       |       |      |Airoha AG3335M                                                                        |                 |
|Arista          |O-435E       |7         |Yes |Yes               |Yes|   |       |       |      |Airoha AG3335M                                                                        |                 |
|Cisco           |All?         |6,6E,7    |Yes |Yes               |Yes|Yes|Yes    |No     |No    |Broadcomm                                                                             |                 |
|CommScope/Ruckus|             |          |    |                  |   |   |       |       |      |                                                                                      |                 |
|Extreme         |AP5050 (?)   |6E        |Yes |Yes               |No |   |       |       |      |                                                                                      |                 |
|Fortinet        |FAP-441K     |7         |    |Yes               |No |   |       |       |      |Quectel LC76GABMD (FCC Filing - Internal Photos Part 1)                               |2.2dBi           |
|Fortinet        |FAP-443K     |7         |    |Yes               |No |   |       |       |      |Quectel LC76GABMD (FCC Filing - Internal Photos Part 1)                               |2.2dBi           |
|Fortinet        |FAP-433G     |6E        |    |Yes               |No |   |       |       |      |Data sheet says it has one, nothing on internal photos                                |                 |
|Fortinet        |FAP-432G     |6E        |    |Yes               |No |   |       |       |      |Almost certainly LC76G                                                                |3.0dBi           |
|Fortinet        |FAP-431G     |6E        |    |Yes               |No |   |       |       |      |Data sheet says it has one, nothing on internal photos                                |                 |
|Fortinet        |FAP-234G     |6E        |    |Yes               |No |   |       |       |      |Quectel LC76GABMD                                                                     |5.0dBi           |
|HPE Aruba       |APEX585      |6         |    |Yes               |No |   |       |       |      |ublox M9140-KB                                                                        |                 |
|HPE Aruba       |AP605        |6E        |    |Yes               |No |   |       |       |      |ublox M9140-KB                                                                        |                 |
|HPE Aruba       |AP615        |6E        |    |Yes               |No |   |       |       |      |ublox M9140-KB                                                                        |                 |
|HPE Aruba       |AP635        |6E        |    |Yes               |No |   |       |       |      |ublox M9140-KB                                                                        |                 |
|HPE Aruba       |AP634        |6E        |    |Yes               |No |   |       |       |      |ublox M9140-KB                                                                        |                 |
|HPE Aruba       |AP655        |6E        |    |Yes               |No |   |       |       |      |ublox M9140-KB                                                                        |                 |
|HPE Aruba       |APEX675      |          |    |                  |   |   |       |       |      |(can't make it out in FCC filings)                                                    |                 |
|HPE Aruba       |AP734        |7         |Yes |Yes               |Yes|Yes|Yes    |No     |No    |ublox NEO-F10T                                                                        |2.8dBi           |
|HPE Aruba       |AP735        |7         |Yes |Yes               |Yes|Yes|Yes    |No     |No    |ublox NEO-F10T                                                                        |4.4dBi           |
|HPE Aruba       |750 Series   |7         |    |Yes               |Yes|   |       |       |      |                                                                                      |                 |
|HPE Aruba       |USB LTE Modem|N/A       |N/A |Yes               |No |   |       |       |      |                                                                                      |                 |
|Juniper Mist    |AP47         |7         |    |Yes               |Yes|   |       |       |      |                                                                                      |                 |
|Juniper Mist    |AP64 Outdoor |6E        |    |Yes               |Yes|   |       |       |      |Airoha AG3335M                                                                        |                 |
|Ubiquiti        |All          |          |    |No GNSS, RSSI Only|   |   |       |       |      |https://help.ui.com/hc/en-us/articles/25707346939927-6-GHz-Extended-Range-AFC-in-UniFi|                 |
