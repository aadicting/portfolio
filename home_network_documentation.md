# Home Network Overview & Troubleshooting Guide

Author: Aadi
Date: [fill in]

## 1. Purpose

Short overview of your home network setup and connectivity testing performed for documentation practice.

## 2. Network Details

| Item | Value |
|---|---|
| WAN IP (public) | [check whatismyip.com or router admin page] |
| Router LAN IP | [e.g. 192.168.1.1] |
| LAN IP range | [e.g. 192.168.1.0/24] |
| DHCP range | [e.g. 192.168.1.100 - 192.168.1.200] |
| DNS server(s) | [e.g. 1.1.1.1, 192.168.1.1] |
| ISP | [fill in] |

How to find these: log into your router admin page (usually 192.168.1.1 or 192.168.0.1 in a browser), check the Status/DHCP/WAN sections.

## 3. Network Diagram

[Insert a simple diagram: Router -> Wi-Fi -> Devices (laptop, phone, etc). Can be hand-drawn, made in draw.io, or even PowerPoint/Google Slides. Take a screenshot and paste it here.]

## 4. Connectivity Testing

Run these commands and paste the output.

Windows:
```
ping google.com
tracert google.com
```

Linux/macOS:
```
ping google.com
traceroute google.com
```

Record:
- Response times
- Any packet loss
- Number of hops in traceroute

## 5. Troubleshooting Steps Performed

Example structure - fill with your own findings:

1. Issue: [e.g. slow Wi-Fi in one room]
   Diagnosis: [e.g. checked signal strength, ran speed test]
   Fix: [e.g. moved router, changed Wi-Fi channel]

2. Issue: [fill in]
   Diagnosis: [fill in]
   Fix: [fill in]

## 6. Reflection

One or two sentences on what this exercise taught you about network fundamentals (DHCP, DNS, routing) and how you'd apply it in an IT support role.

---

## How to turn this into a portfolio piece

1. Fill in the sections above (should take under an hour).
2. Export as PDF or keep as a Google Doc.
3. Add a link to it from your resume under the "Projects / Home Lab" section.
4. Take one or two screenshots (router admin page, ping output) to make it visually credible.
