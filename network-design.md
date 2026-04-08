## Network Architecture

This lab uses full network isolation to ensure secure testing.

### Networks Used

Internal Network (lab-net):
- 10.10.10.0/24
- Communication only between lab machines

Host-Only Network (vboxnet0):
- 192.168.56.0/24
- Allows management access from host machine only

No NAT or Internet access is configured on lab machines.

---

## Security Design Principles
- Prevent lateral movement to home network
- Ensure full attack containment
- Simulate enterprise network segmentation

---

## Internet Access Policy
- Internet access enabled temporarily only for updates
- Adapter removed after updates are completed
``
