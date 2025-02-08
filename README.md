# Week 1: Networking Challenge
Welcome to Week 1 of the 90 Days of DevOps

## Tasks

### 1. **Understand OSI & TCP/IP Models**

## What is the OSI Model?
- The OSI (Open Systems Interconnection)was developed by the International Organization for Standardization (ISO).
- It is a set of rules that explains how different computer systems communicate with each other over a network. 
- The OSI Model consists of 7 layers and each layer has specific functions and responsibilities.

## Layers of OSI Model:

**Application Layer (Layer 7)**
  - Interface for end-user applications to communicate over a network. This is the only layer that directly interacts with data from the user.
  - **Example:**
    - HTTP: When you browse a website (opening Google.com).
    - SMTP: Sending an email using Gmail.

**Presentation Layer (Layer 6)**
  - This layer is primarily responsible for preparing data so that it can be used by the application layer.
  - The presentation layer is responsible for translation, encryption, and compression of data.
  - The presentation layer is also called the Translation layer.
  - **Example:**
    - SSL/TLS: Secure data transfer in HTTPS.
    - JPEG, MP3: Compressing images and audio files before sending.

**Session Layer (Layer 5)**
  - This is the layer that Manages and controls connections between applications (opening and closing communication between the two devices).
  - The time between when the communication is opened and closed is known as the session.
  - **Example:**
    - OAuth Authentication: Logging into a website using Google/Facebook.
    - Calls: Maintaining an active call session.
   
**Transport Layer (Layer 4)**
  - Layer 4 ensures reliable data transmission. This includes taking data from the session layer and breaking it up into chunks called segments before sending it to Layer 3.
  - The data in the transport layer is referred to as Segments.
  - The transport layer is also responsible for flow control and error control.
  - **Example:**
    - TCP (Transmission Control Protocol): Ensures file downloads are complete and error-free.
    - UDP (User Datagram Protocol): Live video streaming, where some data loss is acceptable.

**Network Layer (Layer 3)**
  - The network layer provides transmission of data from one host to the other located in different networks.
  -  The network layer breaks up segments from the transport layer into smaller units, called packets.
  -  It also determines the best route for data transfer.
  - **Example:**
    - IP (Internet Protocol): Assigns unique addresses (e.g., 192.168.1.1).
    - Routers: Direct data between networks.

**Data Link Layer (Layer 2)**
  -  The data link layer handles data transfer between two devices on the same network. (data transfer between directly connected devices.)
  - The data link layer takes packets from the network layer and breaks them into smaller pieces called frames.
  - **Example:**
    - MAC Addresses: Identifying devices in a local network.
    - Ethernet & Wi-Fi: Connecting a laptop to a router.

**Physical Layer (Layer 1)**
  - It includes the actual physical connection between the devices.
  - The physical layer contains information in the form of bits and then transmits individual bits from one node to the next.
  - When receiving data, this layer will get the signal received and convert it into 0s and 1s and send them to the Data Link layer,
  - **Example:**
    - Fiber Optic Cables: Used for high-speed internet.
    - Wi-Fi Signals: Wireless connectivity.
