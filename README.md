# STM32 CAN Bus Communication Protocol
This project implements a CAN (Controller Area Network) protocol for STM32 microcontrollers using the HAL (Hardware Abstraction Layer) library. The code initially runs in loopback mode for self-testing but can be modified for real multi-MCU communication over a CAN bus.

# Features
 Loopback Mode for Debugging (Self-communication within one MCU).

 Supports Normal Mode for Multi-MCU Communication.

 Interrupt-Based Reception for efficient message handling.

 Multiple Message Transmission using CAN hardware mailboxes.

 Configurable Filtering for selective message reception.

# How It Works
The default mode is loopback for testing CAN transmission and reception within a single MCU.

To enable communication between multiple STM32 MCUs,we can switch to normal mode (CAN_MODE_NORMAL).

The CAN interrupt handles incoming messages for real-time data processing

