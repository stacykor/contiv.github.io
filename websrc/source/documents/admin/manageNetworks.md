---
layout: "documents"
page_title: "Network Defaults"
sidebar_current: "admin-setting-network-defaults"
description: |-
  Setting Network Defaults
---

# Setting Network Defaults

As the administrator of your Contiv project, you can limit the VXLAN and VLAN ranges for any networks your tenants create, enable ACI, and choose the forwarding mode for your container networks based on your network architecture. 


To set the network defaults.

1. Select *Settings > Network Defaults*.
2. Choose your network infrastructure type.<br>
 If you are using Cisco ACI, you must choose ACI, otherwise leave as default.<br>
3. Enter a VLAN range.
4. Enter a VXLAN range. 
5. Select your forwarding mode *bridge* or *routing*.
6. Click Update Network Settings. 
   You recieve a confirmation message confirming the update to your global settings.  
