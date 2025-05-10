---
sidebar_position: 5
---
# Choosing parts
Choosing parts can be very difficult! Here's a general guide on how to choose between them:


## General tips
**Look at what existing projects use and try to reuse as much as possible**. It save you a ton of time.

Look for existing projects

Example: (game console example from pi tin)

Always, ALWAYS try googling questions first. Almost always someone has already asked the question and recieved an answer.

## Microcontroller Chips:
- Need WiFi? ESP32 or Esp8266
- Otherwise, go for an RP2040 based chip - the atmega series in Arduino boards nowadays are more expensive, weaker, and more finnicky to get running generally speaking
- Need BLE? nrf52840

### SBC vs MCU (Raspberry Pi vs Arduino, etc)


### Specific Models:
- The XIAO Series all have built-in battery management! Make sure to read on the specific implementation since they vary from board to board
-