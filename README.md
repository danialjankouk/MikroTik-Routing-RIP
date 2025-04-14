# 🌐 MikroTik RIP Routing Lab (VMware-Based)

> A virtual lab project demonstrating dynamic routing with the RIP protocol using MikroTik routers on VMware.

---

## 🧠 Overview

This project showcases the implementation of **Routing Information Protocol (RIP)** between multiple virtual MikroTik routers. The entire network is built and simulated using **VMware Workstation**, providing a practical, isolated environment to understand and test dynamic routing concepts.

---

## 🧱 Lab Topology

- 6 virtual MikroTik routers (CHR) deployed on VMware  
- Each router is configured with:
  - IP addressing
  - RIP v2 dynamic routing
  - Static routes for initial reachability (optional)
- Point-to-point and Ethernet interfaces used for interconnection

📌 The setup demonstrates how RIP shares routing information across routers and enables communication between separate networks without manual static routes.

---

## 🛠 Requirements

- VMware Workstation or VMware Player  
- MikroTik CHR (Cloud Hosted Router) images  
- Basic knowledge of MikroTik CLI / Winbox  
- Understanding of RIP (Routing Information Protocol)  

---

## 🚀 How to Use

1. Download the OVA file  

2. Import it into VMware (File > Open > Select OVA)

3. Start the VM

4. Login to all MikroTik routers with:
   - **Username:** `admin`
   - **Password:** `1`

All RIP configurations are already applied.


---

## 🧪 Features Demonstrated

✅ RIP v2 configuration on MikroTik  
✅ Route advertisement and convergence  
✅ IP addressing and subnetting  
✅ Interface and routing diagnostics  

---

## 📂 Project Files

```bash
📁 mikrotik-rip-lab/
├── vm-configs/               # VMware VMX files and networking setup
├── router-configs/           # Exported MikroTik config scripts
├── rip-setup.txt             # Step-by-step setup guide
├── topology.png              # Network diagram of the lab
└── README.md
