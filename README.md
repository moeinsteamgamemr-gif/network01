# Trendify Nexus TCP Relay

## Railway Variables
PORT=443
RELAY_SECRET=<secret provided by the installer>

## Setup
1. Deploy this repository to Railway.
2. Set PORT and RELAY_SECRET.
3. Create a Railway TCP Proxy targeting port 443.
4. Configure the relay host and port in the backend-managed Gateway.

Keep RELAY_SECRET private.