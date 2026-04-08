# Network Traffic Analysis – Wireshark

This section documents packet-level analysis performed
to validate and support SIEM alerts.

---

## Purpose
- Confirm suspicious activity detected by Wazuh
- Find suspicous network activity not detected by Wazuh
- Understand attack patterns at network level
- Establish baseline vs malicious traffic

---

## Tools Used
- tcpdump (packet capture)
- Wireshark (analysis)

---

## SOC Value
Packet analysis is used as a secondary validation step
during alert investigation.
