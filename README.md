
# 🔌 Basic\_Networking Simulation

This repository features beginner-friendly networking simulations built with **Cisco Packet Tracer**. It’s designed for anyone learning core networking concepts through hands-on practice.

---

## 🧱 Project Summary

This project illustrates a simple network layout using:

* 1 Router
* 2 Switches
* 4 End Devices

It’s a great example of how devices communicate within and between networks, applying fundamental ideas like **IP addressing**, **subnetting**, and **routing**.

---

## 🖧 Network Topology

* Each switch connects to two end devices.
* Both switches link to a single router.

### What this setup enables:

* Devices on the same switch (and subnet) can communicate directly.
* Devices on different subnets communicate through the router.

---

## ✅ Key Features

* Subnetting is used to divide the network logically.
* Switches handle local device traffic.
* The router enables communication across subnets.
* Ping tests verify both local and routed connections.

---

## 🧰 Tools Used

* **Cisco Packet Tracer** (you can also try it with GNS3)
* Networking principles covered:

  * IP addressing & subnetting
  * Layer 2 switching
  * Basic Layer 3 routing

---

## 🚀 How to Run

1. Open the provided `.pkt` file in Cisco Packet Tracer.
2. Check that all devices are properly connected and configured.
3. Use the **Ping** tool to test:

   * Device-to-device connections on the same switch (local subnet)
   * Communication between devices on different switches (via router)

---

Let me know if you’d like to expand the project with DHCP, VLANs, or routing protocols!
