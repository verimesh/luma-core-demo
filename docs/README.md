# 📚 Luma Core — Documentation Index

This directory contains the high-level technical documentation for **Luma Core**, the sovereign, offline-first digital infrastructure framework.

It provides a complete overview of the architecture, protocol layers, communications model, and hub design.

---

# 🧱 Core Architectural Documents

### **1. Overview**  
`overview.md`  
High-level explanation of Luma Core’s purpose, multi-hub model, and design philosophy.

### **2. System Architecture**  
`architecture.md`  
Describes the full system stack, data flow, audit model, and sovereign deployment architecture.

---

# 🔐 Integrity & Verification Layer

### **3. Audit Receipts**  
`audit-receipts.md`  
Explains hash-linked receipts, chain integrity, and policy embedding.

### **4. Audit Receipt Engine — Deep Spec**  
`audit-engine.md`  
Technical breakdown of receipt creation, hashing, signing, CRDT merging, and multi-layer verification.

---

# 🔗 Cross-Integrity Protocol (XIP)

### **5. XIP Protocol — Standard**  
`xip-standard.md`  
Lightweight introduction to the Cross-Integrity Protocol used across all hubs.

### **6. XIP Protocol — Detailed Specification**  
`xip-detailed-spec.md`  
Full packet structure, verification rules, transport modes, and cross-border interoperability.

---

# 📡 Adaptive Communications Layer

### **7. ACL — Overview**  
`adaptive-comms.md`  
Introduction to the offline-first communications model: mesh, satellite, DTN, and fallback logic.

### **8. ACL — Deep Technical Spec**  
`adaptive-comms-deep.md`  
Detailed analysis of multi-path routing, device identity persistence, DTN behaviour, and resilience design.

---

# 🧩 Hub Documentation

Each hub represents a sovereign-ready module:

### **Finance Hub**  
`../src/hubs/finance/README.md`  
ISO workflows, invoices, settlement, VAT, reconciliation, and CBDC readiness.

### **Cannabis / Health Compliance Hub**  
`../src/hubs/cannabis/README.md`  
Prescriptions, dispensing, supply chain, policy rules, and medical compliance.

### **Government Hub**  
`../src/hubs/government/README.md`  
Case management, evidence chains, identity services, policy enforcement, emergency ops.

---

# 🧭 Purpose of This Documentation Set

This index is designed for:

- reviewers and evaluators  
- universities and research partners  
- government departments  
- funding bodies (TechStart, Invest NI, councils)  
- industry or enterprise adopters  

It provides a clear entry point into the Luma Core architecture and demonstrates deployment readiness.

---

# ✔ Status

This documentation set is complete and actively updated as Luma Core evolves.

▶ Live Demo

You can view the hosted offline-first browser demo here:
👉 https://luma-core-demo.netlify.app/

This demo runs entirely client-side and demonstrates:

Offline-first behaviour

Local audit receipts

Sync and reconciliation

Installable PWA support

It is preserved as a reference implementation of how Luma Core hubs operate without servers or continuous connectivity.

Note: Production deployments run on secure device builds and the Luma OPS Command Centre rather than the public browser demo.
