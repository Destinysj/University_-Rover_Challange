# Prototype Rover Design

Team ARES a team of 25 members were working together to build a prototype of rover for URC.
- Accessed live location using GPS module. Integrated hardware and interfacing sensors with 
  Arduino. Master-Slave communication between various modules and Raspberry Pi.
- Fetching data from MPU9250- Accelerometer, Gyroscope, Magnetometer values to get real 
  world data Yaw, Pitch, Roll angles.....
- Using Lora 1276 v2.0 RF Module to transmits onboard sensor data to base station.
  For Wireless long range communication LoRa v2.0 using as it has long range low 
  power and less bandwidth (cannot be used for trasmitting     videos) data associated 
  with (modules-DHT-22, sensors-MPUs communication-SPI   protocol) with 32 bit header 
  can be trasmitted over the air
# Testing DRAGINO Lora Shield v1.4
-WM- BUS, A wireless M-Bus network is based on star topology network with master
and slave device described in the EN13757 standard which comprises a number of different 
operating modes.
- Open source Liabrary 
- Lora Shild based on SX127/SX128 targets professional wireless sensor network application 
- Sensitive -148dBm
- Highly sensitive combined with Integrated +20 dBm power amplifier.
- IEE802.15.4g
- Exceptional phase, noise immunity, selectivity, linearity.
- # Bullet Proof - IIP3
Specifications that bends our thoughts to use it.
- 168dB max link budget
- +20 dBm - 100mW contant RF output vs
- +14 dBm highly sensitive down to -148 dBm
- Excellent blocking immunity
- Low rx current of 10.3mA, 200nA register extension.
