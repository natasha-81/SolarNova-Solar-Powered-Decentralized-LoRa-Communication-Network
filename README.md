# SolarNova : Solar-Powered-Decentralized-LoRa-Communication-Network

📖 Overview

SolarNova is a self-sustaining, decentralized communication system designed to operate without internet or cellular infrastructure. It leverages LoRa (Long Range) wireless communication and solar energy to enable reliable messaging in remote, disaster-affected, or infrastructure-deficient environments.
The system integrates embedded hardware, wireless networking, renewable energy, and web technologies into a unified platform that supports real-time communication through a browser interface.

❗ Problem Statement

Modern communication systems depend heavily on centralized infrastructure such as cellular towers and internet connectivity. These systems often fail in:
Natural disasters (earthquakes, floods, cyclones)
Remote or rural areas with no network coverage
Emergency rescue operations
High-density events with network congestion
This creates a critical need for a reliable, independent communication solution that can function under such conditions.

💡 Proposed Solution

SolarNova addresses this gap by providing a:
1. LoRa-based wireless communication network (long-range, low-power)
2. Solar-powered autonomous system with battery backup
3. Browser-based messaging interface (no mobile app required)
4. Multi-hop mesh communication capability
5. GPS-enabled location tracking and SOS alerts
The system operates as a decentralized network of nodes, each capable of transmitting, receiving, and forwarding messages.

🚀 Key Features

1. Private Messaging
   Secure, user-specific communication
   Messages routed through LoRa network
   No internet dependency
2. Web-Based Interface
   Accessible via browser (192.168.4.1)
   Built using WebSockets for real-time communication
   No installation required
3. GPS Location Sharing
   Real-time location tracking
   Displays positions of connected nodes
4. SOS Emergency Alerts
   One-tap broadcast message
   Includes GPS location
   Sent to entire network
5. Multi-Hop Communication
   Store-and-forward routing
   Supports communication across multiple nodes
   Tested up to 5 hops
6. Solar-Powered Operation
   Renewable energy source
   Battery backup for continuous operation
7. Self-Cleaning Solar Panel (Advanced)
   Automated cleaning mechanism
   Maintains efficiency in dusty environments
   Scheduled operation using motorized system

🏗️ System Architecture

1. Hardware Components: 
ESP32-based LoRa Module (Heltec LoRa32 V3)
Solar Panel
Li-ion Battery
TP4056 Charging Module
LM7805 Voltage Regulator
NEO-6M GPS Module
2. Software Stack
Embedded C++ (Arduino IDE)
FreeRTOS (task scheduling)
AsyncWebServer (web hosting)
WebSockets (real-time communication)
TinyGPS++ (GPS parsing)

🧪 Implementation & Results

✅ Successfully Achieved
1. LoRa-based communication between nodes
2. Reliable message transmission without internet
3. Functional web interface for messaging
4. Solar-powered energy system
5. Battery backup operation
6. The system demonstrated stable performance over short and medium distances, validating its feasibility as an infrastructure-independent communication solution.

🏁 Conclusion

SolarNova demonstrates that a low-cost, energy-efficient, and decentralized communication network can be built using commercially available components. The system successfully enables communication in environments where traditional infrastructure is unavailable or unreliable.
It provides a strong foundation for future development in emergency communication systems, smart networks, and sustainable IoT solutions.
