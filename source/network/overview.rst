Network Overview & Topology
===========================

ISP → ONT → Franky (OPNsense) → TP-Link AXE75 + Omada Switch

.. code-block:: text

   ISP
    └── ONT
         └── Franky (OPNsense - HP ProDesk 600 G6)
              ├── TP-Link Archer AXE75
              │    ├── WLAN Family (2.4/5GHz)
              │    ├── WLAN Guest (isolated)
              │    └── WLAN IoT (isolated)
              ├── Omada Managed PoE Switch (8-port)
              │    ├── Raspberry Pi 5
              │    └── Tony (Proxmox)
              └── Gaming PC
