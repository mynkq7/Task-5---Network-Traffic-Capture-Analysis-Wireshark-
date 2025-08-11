# Task-5---Network-Traffic-Capture-Analysis-Wireshark
**Date:** 11 August 2025  
**Platform:** Kali Linux  
**Tool Used:** Wireshark  

## Objective
Capture live network packets and identify basic protocols and traffic types.

## Steps Performed
- Opened Wireshark on Kali Linux.
- Selected the active interface (`wlan0`) and started capture.

### DNS Capture
- Visited websites such as `notion.com` and `github.com`.
- Captured DNS queries and responses.
- Saved as `dns.pcapng`.

### HTTP/TCP Capture
- Visited `http://httpforever.com/` to capture HTTP packets.
- Saved as `http-tcp.pcapng`.

## Protocols Identified
- **DNS** – Resolving domain names into IP addresses.
- **HTTP** – Unencrypted web requests and responses.
- **TCP** – Reliable transport protocol used by HTTP/HTTPS.

## Observations
- DNS packets show the computer asking for the IP addresses of websites before connecting to them.
- HTTP packets show the actual website data being sent and received after the DNS step.
- TCP packets were used to carry the HTTP data between my computer and the web servers.

## Files Included
- `dns.pcapng` – Contains captured DNS queries/responses.
- `http-tcp.pcapng` – Contains captured HTTP and TCP packets.
