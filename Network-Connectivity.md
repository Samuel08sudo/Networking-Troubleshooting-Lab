# No Network Connectivity

## Problem
User unable to connect to network

## Diagnosis
- Ran ipconfig → no IP assigned (169.x.x.x)

## Root Cause
DHCP failure

## Resolution
- Restarted router
- Ran: ipconfig /release
- Ran: ipconfig /renew

## Result
Valid IP assigned and connection restored
