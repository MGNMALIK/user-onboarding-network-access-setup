#  User Onboarding: Network Access Setup

This project simulates a real-world task where an IT support technician sets up network access for three new employees.

Each PC was assigned a static IP and tested to ensure it could reach:
- The local gateway
- A shared network printer
- A central file server

---

## Setup Details

| Device | IP Address     | Subnet Mask     | Gateway       | Purpose         |
|--------|----------------|------------------|----------------|------------------|
| PC5    | 192.168.10.9   | 255.255.255.0    | 192.168.10.1   | New user         |
| PC6    | 192.168.10.10  | 255.255.255.0    | 192.168.10.1   | New user         |
| PC7    | 192.168.10.11  | 255.255.255.0    | 192.168.10.1   | New user         |
| Printer| 192.168.10.7   | 255.255.255.0    | 192.168.10.1   | Shared printing  |
| Server | 192.168.10.8   | 255.255.255.0    | 192.168.10.1   | File sharing     |

---

##  Tests Completed

- All new PCs successfully pinged the router
- All new PCs confirmed connectivity to the printer and server
- Static IP configuration was used instead of DHCP

---

##  Skills Practiced

- Static IP setup
- Device-to-device testing using ping
- End-user setup and documentation
