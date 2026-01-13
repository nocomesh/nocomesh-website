---
date: 2026-01-13T09:15:40-07:00
description: Everyone started somewhere! Let's start you here
draft: true
title: Getting Started
tags: [New User]
---

{{% pageinfo color="secondary" %}}
Please check out the [Offical Meshtastic Getting Started Guide](https://meshtastic.org/docs/getting-started/) first.
{{% /pageinfo %}}

## TL;DR

1. Buy a [recommended Meshtastic node]({{< ref "recommended-hardware">}})
2. Flash your node
3. Configure your device
5. Send a message

## Buying a Meshtastic Node

There are a lot of devices that you can buy to get started with Meshtastic. The Meshtastic hardware documentation [has a few community-recommended boards](https://meshtastic.org/docs/hardware/devices/#which-board-should-i-choose), but we have our own [hardware suggestions]({{< ref "recommended-hardware">}})

## Flashing your node

Depending on the device, flashing is done one of two ways

### ESP32 Devices

ESP32-based devices can utilize the [Meshtastic Flasher website](https://flasher.meshtastic.org) to install and update firmware, making it a breeze to stay up to date. Simply plug your device into your computer and follow the instructions on the website.

More information and other methods are available through the [official Meshtastic documentation](https://meshtastic.org/docs/getting-started/flashing-firmware/esp32/)

### nRF52/RP2040 Devices

nRF52 and RP2040-based devices can be bit more complicated, but most are supported via the [Mestastic Flasher website](https://flasher.meshtastic.org). Simply follow the ESP32 instructions above and update your device.

For more information, as well other methods to flash your device, visit the [official Meshtastic documentation](https://meshtastic.org/docs/getting-started/flashing-firmware/nrf52/)

## Configuration

For more information on configuring your device, please visit our [configuration guide]({{< ref "configuration" >}})

## Send a message

Once the above steps are followed, you're ready to send a message! Open the Meshtastic app on your phone (or use the [Web Client](https://client.meshtastic.org) if on a computer), connect to your node, and send a message to the default channel! If you've set everything up correctly, others should be able to see your message, and your message will show up in the [public MeshView chat logs](https://map.nocomesh.org/chat)! Enjoy meshing with your neighbors in Northern Colorado