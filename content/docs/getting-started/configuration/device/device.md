---
date: '2026-01-24T18:34:09-07:00'
draft: true
title: 'Device'
tags: [Settings]
---

We heavily recommend [reading more about roles on the Meshtastic blog](https://meshtastic.org/blog/choosing-the-right-device-role/)

## Options

| Name                         | Value   | Notes                                                                                                       |
| ---------------------------- | ------- | ----------------------------------------------------------------------------------------------------------- |
| Device Role                  | CLIENT  | Use CLIENT_MUTE if you have a lot of zero-hop nodes near you, or CLIENT_BASE for a higher power solar node. |
| Rebroadcast Mode             | ALL     | Don't change this, but change the Device Role to CLIENT_MUTE on pocket/low power nodes                      |
| Node Info Broadcast Interval | 3 hours | This is the fastest setting and is fine                                                                     |