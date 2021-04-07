# Aperio Online/Offline

Online wireless Communication over zigbee with a aes128 key for each installation (if personalized) some installations are running on factory default keys used for provisioning


## System description wireless
### 1 to 1
Each hub only communicates with one lock over wiegand interface from the hub to the access control system

### 1 to many
Each hub communicates with 8 doors and relays information over a rs485 bus where multiple hubs can live (5 bit adress space)
