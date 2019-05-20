![Diagram](https://github.com/rickijen/hl7-vpn-fw/blob/master/VRFs/CSR%20with%20VRFs.jpg)

This sample config demonstrates the use of **one VFR per customer VPN branch**. This will handle spoke-spoke IP overlaps. For hub-spoke IP overlaps, need to handle NAT at customer branch VPN appliance.

Refer to https://github.com/jwrightazure/lab/tree/master/csr-vpn-to-csr-ikev2-overlappingAdress
