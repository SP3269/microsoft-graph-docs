---
title: "firewallPacketQueueingMethodType enum type"
description: "Possible values for firewallPacketQueueingMethod"
author: "tfitzmac"
---

# firewallPacketQueueingMethodType enum type

> **Important:** APIs under the / beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Possible values for firewallPacketQueueingMethod
## Members
|Member|Value|Description|
|:---|:---|:---|
|deviceDefault|0|No value configured by Intune, do not override the user-configured device default value|
|disabled|1|Disable packet queuing|
|queueInbound|2|Queue inbound encrypted packets|
|queueOutbound|3|Queue decrypted outbound packets for forwarding|
|queueBoth|4|Queue both inbound and outbound packets|





