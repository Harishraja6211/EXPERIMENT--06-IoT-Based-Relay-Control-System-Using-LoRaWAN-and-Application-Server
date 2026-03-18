# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
## NAME : Harish
## REG NO : 212223220031
## DEPT : INFORMATION TECHNOLOGY
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1920" height="1200" alt="Screenshot 2026-03-13 172939" src="https://github.com/user-attachments/assets/ca4a6bde-bcc7-46fa-b6a5-ed135c7dc8ce" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 173005" src="https://github.com/user-attachments/assets/997dee92-d3d8-451d-bc2b-23522688eac1" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 173013" src="https://github.com/user-attachments/assets/de7b2102-340c-4852-b302-9c69ebd9dc5d" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 173027" src="https://github.com/user-attachments/assets/267b9016-6804-40fc-9eab-6bb64167fc35" />

### 2. Network Server – Recent Events
<img width="1920" height="1200" alt="Screenshot 2026-03-13 172815" src="https://github.com/user-attachments/assets/b6d2561a-978c-401f-b379-56c19be6b6ce" />
<img width="1920" height="1200" alt="Screenshot 2026-03-13 172541" src="https://github.com/user-attachments/assets/364418e9-4b99-4949-923a-7b7a3d94f81d" />


### 3. Dashboard Command Sending
<img width="1920" height="1200" alt="Screenshot 2026-03-17 113439" src="https://github.com/user-attachments/assets/663b7ee2-bf84-450e-b0fe-924bd5bbd644" />
<img width="1920" height="1200" alt="Screenshot 2026-03-17 113456" src="https://github.com/user-attachments/assets/8c79410b-d680-4cc2-b2ed-36650bf16bad" />

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON 
<img width="1920" height="1200" alt="Screenshot 2026-03-13 172517" src="https://github.com/user-attachments/assets/d63ce02c-4f3e-4d1a-b747-f61c2f722e18" />


### Bulb OFF → Relay OFF
<img width="1920" height="1200" alt="Screenshot 2026-03-13 172857" src="https://github.com/user-attachments/assets/1b00ee87-f3d1-4c8d-a3d5-5888c1cb5323" />


## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
