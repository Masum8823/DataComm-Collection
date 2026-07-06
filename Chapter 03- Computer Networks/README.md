## 🌐 What is a Network?
 
> A **network** is a group of connected devices or people.
 
In a computer network, computers and other devices are connected to share data, hardware, software, and communicate with each other.
 
---
 
## 🎯 Purpose of a Network
 
- 📤 Share data and information
- 🖨️ Share hardware and software resources
- 💬 Enable communication between users
- 🎥 Provide different services (text, audio, video, images, etc.)
---

## 🧩 Components of a Network
 
<details>
<summary><b>🔹 Node</b></summary>

- A **node** is any device connected to a network.
- **Examples:** Computer, printer, server.
</details>
<details>
<summary><b>🔹 Link</b></summary>

- A **link** is the communication path between nodes.
- **Examples:** Cable, optical fiber, air (wireless).
</details>

---

## 🗂️ Categories of Networks
 
### 1️⃣ Local Area Network (LAN)
 
- Covers a small area (home, school, office, or one building)
- Smallest type of network
- High-speed network (about 100 Mbps or more)
- Used for local communication
- **Example:** School or office network

---

### 2️⃣ Metropolitan Area Network (MAN)
 
- Covers a larger area than LAN, usually a city
- Connects multiple LANs
- Speed is lower than LAN but higher than WAN
- **Example:** A bank connecting its branches within Dhaka city

---

### 3️⃣ Wide Area Network (WAN)
 
- Covers very large areas such as countries or continents
- Largest type of network
- Connects multiple LANs and MANs
- The Internet is the largest WAN
- **Example:** Banking network across different countries
---

## ⚖️ LAN vs MAN vs WAN
 
| Feature | LAN | MAN | WAN |
|---|---|---|---|
| **Coverage** | Small area | A city | Countries or continents |
| **Speed** | Fastest | Medium speed | Slower than LAN |
| **Connects** | Devices in one building | Multiple LANs | LANs and MANs |
| **Example** | School, Office | City Bank Network | Internet |
 
---

## 🔌 Physical Structures
 
### Types of Connection
 
<details>
<summary><b>1. Point-to-Point Connection</b></summary>

- Connects one sender to one receiver.
- Used for direct communication between two devices.
</details>
<details>
<summary><b>2. Multipoint Connection</b></summary>

- One transmission is shared by multiple devices.
- One sender can communicate with many receivers.
</details>

---

### Physical Topology
 
- **Physical topology** is the physical arrangement of devices in a network.
- It shows how devices and communication links are connected.
---
 
## 📡 Types of Transmission
 
| Type | Description |
|---|---|
| **Unicast** | One sender → One receiver |
| **Broadcast** | One sender → All devices |
| **Multicast** | One sender → A selected group of devices |
 
---

## 🕸️ Network Topology
 
### 1. Mesh Topology
 
Every node is connected to multiple other nodes, providing alternate paths for data. Used in large and reliable networks.
 
<details>
<summary><b>✅ Advantages</b></summary>

- Supports multiple data transmissions at the same time
- Failure of one node does not stop the network
- Handles heavy network traffic
- Easy to find faults
</details>
<details>
<summary><b>❌ Disadvantages</b></summary>

- Requires many cable connections
- Expensive and complex
- Creates redundant (extra) connections
- Number of links = **n(n−1)/2**
</details>

---

### 2. Star Topology
 
All devices are connected to a central hub or switch. Commonly used in LANs.
 
<details>
<summary><b>✅ Advantages</b></summary>

- Easy to install and maintain
- Easy to detect problems
- One cable per device
- Centralized control
</details>
<details>
<summary><b>❌ Disadvantages</b></summary>

- Uses more cable
- Difficult to expand
- If the central device fails, the whole network stops
</details>

---

### 3. Bus Topology
 
All devices share a single communication cable (bus). Terminators are placed at both ends to stop signal reflection. Usually uses a coaxial cable.
 
<details>
<summary><b>✅ Advantages</b></summary>

- Simple wiring
- Uses less cable
- Easy to extend
</details>
<details>
<summary><b>❌ Disadvantages</b></summary>

- Difficult to find faults
- Difficult to isolate problems
- Main cable failure affects the whole network
- Requires intelligent nodes
</details>

---
 