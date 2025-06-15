---
title: Meshtastic
subtitle: Short range off grid messaging
layout: page
show_sidebar: false
menubar: docs_menu
toc: true
---


## Introduction

Meshtastic is an implementation of LORA radios for messaging and other telemetry.

Meshtastic does not require a license and so is available to many more people in our local neighbourhoods.

I have had no experience with meshtastic but have some devices on the way so will update this page with my experiences.

The Comms Channel have developed a BBS for meshtastic. 

![meshtastic](/assets/lora-topology-2-c80684f1eafdf2a71fbaf26e494fb26d.png)

## Frequencies

Meshtastic devices are available in a selection of frequencies and you ensure your device works on the 915Mhz band for use in Australia

## References

- [Meshtastic.au](https://meshtastic.au/wp/) A very good place to start with meshtastic in Australia
- [meshtastic.org](https://meshtastic.org) The official Meshtastic project
- [meshmap.net](https://meshmap.net) A map showing online nodes.

[![Image Alt Text](https://img.youtube.com/vi/ZsIWyVzqJPM/0.jpg)](https://youtube.com/watch?v=ZsIWyVzqJPM) 

## Meachcore and Meshtastic

Meshtastic and MeshCore are both LoRa-based mesh networking platforms, but they differ significantly in design philosophy, architecture, and use cases. Here's a breakdown of the key differences:

### Meshtastic

Purpose: Primarily designed for off-grid communication using LoRa radios.

Architecture: Decentralized, peer-to-peer mesh network.

Flooding Protocol: Uses message flooding, where messages are rebroadcast by all nodes to ensure delivery.

Ease of Use: Very user-friendly with mobile apps (iOS/Android) and desktop tools.

Encryption: Supports encryption, but all nodes in a channel share the same key.

Use Case: Ideal for hikers, emergency comms, and hobbyists needing simple, resilient messaging.

Hardware: Compatible with a wide range of ESP32-based LoRa boards (e.g., T-Beam, Heltec).

### MeshCore

Purpose: A more advanced and structured mesh network with routing and server support.

Architecture: Supports repeaters, room servers, and client nodes with more intelligent routing.

Routing Protocol: Uses path discovery and caching, avoiding flooding for efficiency.

Security: Uses public/private key encryption and signed "adverts" to prevent spoofing.

Customization: Highly configurable, supports integration with tools like ATAK, Home Assistant, and MQTT.

Use Case: Better suited for tactical, emergency, or smart home applications where scalability and control are important.

Open Source: Yes, with active development and community support.
