# UPI_Without_Internet
A Spring Boot backend for offline UPI payments over a Bluetooth-style mesh network, enabling transactions without internet connectivity. Payment packets are encrypted and relayed device-to-device until a connected device reaches the internet and uploads them to the backend, where they are decrypted, deduplicated, validated, and settled. This project also includes a software-based mesh simulator to demonstrate the complete offline payment flow on a single laptop without Bluetooth hardware.

This repo is the server side of that system, plus a software simulator of the mesh so you can demo the whole flow on a single laptop without any real Bluetooth hardware.
