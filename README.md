# Bluetooth programming with BlueZ
This collection showcases various Bluetooth-related projects implemented using the Bluez stack. The primary aim is to provide examples and a reference for developers working with Bluetooth on Linux systems. The repository includes three main projects, each demonstrating different aspects of Bluetooth communication:

Projects Overview
1. L2CAP Client and Server
Files: i2cap-client.c, i2cap-server.c
Description: This project demonstrates how to create a Bluetooth connection using the Logical Link Control and Adaptation Protocol (L2CAP). L2CAP provides connection-oriented and connectionless data services to the upper layers of the Bluetooth protocol stack.
Client (i2cap-client.c): Establishes an L2CAP connection to a remote Bluetooth device and sends data.
Server (i2cap-server.c): Listens for incoming L2CAP connections and receives data from clients.
2. RFCOMM Client and Server
Files: rfcomm-client.c, rfcomm-server.c
Description: This project illustrates how to utilize the Radio Frequency Communication (RFCOMM) protocol, which emulates serial ports over the Bluetooth stack.
Client (rfcomm-client.c): Connects to a remote Bluetooth device using RFCOMM and communicates over a virtual serial port.
Server (rfcomm-server.c): Accepts incoming RFCOMM connections, facilitating serial port communication with clients.
3. Sample Bluetooth Scanner
File: samplescan.c
Description: A simple yet effective Bluetooth scanning utility that demonstrates how to discover nearby Bluetooth devices. This project provides an example of how to use the Bluez stack to scan for available Bluetooth devices and retrieve their basic information.
