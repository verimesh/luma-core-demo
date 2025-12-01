# Adaptive Communications Layer (ACL) — Overview

The **Adaptive Communications Layer (ACL)** is the subsystem that ensures Luma Core
continues functioning under any network condition — including low-signal, offline,
or disconnected environments.

ACL provides dynamic, multi-path routing for audit receipts and state updates across:

- Local Offline Mode (device queue)
- Mesh Mode (WiFi-Direct / BLE Mesh)
- Satellite Relay (DTN)
- Standard Internet / Ledger Sync

It automatically chooses the best available path and gracefully fails over when networks
change or become unavailable.

---

## Key Features

- Offline-first operation  
- Multi-path routing and failover  
- Mesh discovery and reconciliation  
- Satellite DTN support for remote regions  
- End-to-end encryption and packet signing  
- Blockchain-agnostic integrity layer  

ACL enables Luma Core to operate in:

- rural and remote regions  
- disaster or emergency conditions  
- conflict zones  
- low-trust or censorship environments  

For deeper technical details, refer to:

➡️ **adaptive-comms-deep.md**
