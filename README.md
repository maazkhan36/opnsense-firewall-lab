# opnsense-firewall-lab
# OPNsense Firewall Policy & Packet Analysis Lab

Hands-on implementation and analysis of top-down firewall rules  and an Ubuntu client.

## Lab Overview
* **Baseline Verification:** Confirmed initial L3/L4 connectivity and DNS resolution.
* **ICMP Filtering:** Created a rule blocking ICMP requests to `1.1.1.1/32` while keeping web traffic open.
* **HTTP Filtering:** Blocked unencrypted HTTP (TCP port 80) while leaving HTTPS (TCP port 443) operational.
* **Traffic Analysis:** Evaluated firewall actions across OPNsense Live View logs, Wireshark captures, and the state table.
* **Restoration:** Re-enabled standard network access by disabling temporary test policies.

