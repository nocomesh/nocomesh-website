---
date: '2026-01-24T18:32:56-07:00'
draft: false
title: 'LoRa'
tags: [Settings]
---

## Options

| Name       | Value                    | Notes                                                     |
| ---------- | ------------------------ | --------------------------------------------------------- |
| Region     | US                       |                                                           |
| Use Preset | True                     |                                                           |
| Presets    | LONG_FAST or MEDIUM_SLOW | We are slowly transitioning to MEDIUM_SLOW over LONG_FAST |

## Advanced

| Name                | Value   | Notes                                                                   |
| ------------------- | ------- | ----------------------------------------------------------------------- |
| Ignore MQTT         | False   |                                                                         |
| OK to MQTT          | True    |                                                                         |
| Transmit Enabled    | True    |                                                                         |
| Override Duty Cycle | False   |                                                                         |
| Number of Hops      | 3       | You can increase this for testing, but change it back when you're done! |
| Frequency Slot      | 20      |                                                                         |
| RX Boosted Gain     | True    |                                                                         |
| Frequency Override  | 906.875 | Don't adjust this manually                                              |
| Transmit Power      | 0       | Maximum transmit power. 0 will set this to the legal maximum            |