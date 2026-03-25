# No Internet Connection (DNS Issue)

## Problem
User connected to WiFi but unable to access internet.

## Diagnosis
- Ran ipconfig → valid IP assigned
- Ping 8.8.8.8 → success
- Ping google.com → failed

## Root Cause
DNS server not resolving domain names

## Resolution
- Changed DNS to 8.8.8.8
- Ran: ipconfig /flushdns

## Result
Internet restored

## Commands Used
ipconfig, ping, ipconfig /flushdns
