# Organisation Network Security

A Cisco Packet Tracer project completed as part of the **NIIT Foundation + Cisco Cybersecurity Internship**.

## Project Overview

This project demonstrates the configuration and security of an organization's wireless network using **Cisco Packet Tracer**.

The objective was to secure the wireless network, restrict access to authorized devices, protect router administration, and verify network connectivity.

## Scenario

An organization needs a secure wireless network to protect sensitive data and prevent unauthorized access.

As the network administrator, the task was to configure the organization's wireless router and implement appropriate network security measures.

## Objectives

* Configure WAN settings
* Secure the wireless network
* Configure WPA2-Personal security
* Enable AES encryption
* Configure MAC address filtering
* Allow authorized employee devices to access the wireless network
* Prevent unauthorized wireless access
* Change the default router management password
* Verify network connectivity

## Network Topology

<img src="./packet-tracer-topology.png" width="720" alt="Organisation Network Security - Cisco Packet Tracer Topology">

## WAN Configuration

| Parameter       | Value       |
| --------------- | ----------- |
| IP Address      | `10.0.0.2`  |
| Subnet Mask     | `255.0.0.0` |
| Default Gateway | `10.0.0.1`  |
| DNS Server      | `195.0.0.1` |

## Wireless Security

| Parameter     | Configuration |
| ------------- | ------------- |
| Wireless Band | `2.4 GHz`     |
| SSID          | `IT_Dept`     |
| Security Type | WPA2-Personal |
| Encryption    | AES           |

The wireless network was secured using WPA2-Personal with AES encryption.

> **Security:** The wireless password is intentionally not included in this public repository.

## MAC Address Filtering

MAC address filtering was enabled on the wireless router to control which devices could access the wireless network.

The router was configured to:

* Permit authorized employee devices
* Restrict unauthorized devices
* Prevent the intruder's laptop from accessing the wireless network

This provided an additional access-control layer for the wireless network.

## Router Administration

The default router management password was changed as required by the activity to improve administrative security.

> **Security:** The router administrator password is intentionally not included in this public repository.

## Connectivity Verification

The completed configuration was tested by:

* Connecting authorized employee devices to the wireless network
* Verifying connectivity for authorized devices
* Confirming that the unauthorized device could not access the wireless network
* Testing access to `www.cisco.com` from an employee workstation

The Packet Tracer activity was successfully completed with **100% completion**.

## Technologies & Concepts

* **Cisco Packet Tracer**
* WAN Configuration
* IP Addressing
* Default Gateway
* DNS
* Wireless Networking
* WPA2-Personal
* AES Encryption
* MAC Address Filtering
* Network Access Control
* Router Administration
* Connectivity Testing

## Project File

The complete Cisco Packet Tracer activity is provided as:

`Organisation-Network-Security.pka`

Open the `.pka` file using **Cisco Packet Tracer** to view the network topology and configurations.

## Repository Contents

```text
Organisation-Network-Security/
│
├── README.md
├── Organisation-Network-Security.pka
└── packet-tracer-topology.png
```

## Internship

**Program:** NIIT Foundation + Cisco Cybersecurity Internship
**Project:** Organisation Network Security
**Platform:** Cisco Packet Tracer
**Status:** Completed
