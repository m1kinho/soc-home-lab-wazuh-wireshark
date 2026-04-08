## Common Wireshark Filters

## HTTP Packets
GET
POST

### RDP Brute Force
tcp.port == 3389

### SSH Activity
tcp.port == 22

### Port Scanning
tcp.flags.syn == 1 && tcp.flags.ack == 0

### Internal Lab Traffic
ip.addr == 10.10.10.0/24
