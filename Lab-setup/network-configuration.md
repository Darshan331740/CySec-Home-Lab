# Network Configuration

Both Kali Linux and Metasploitable virtual machines were connected
to the same Host-Only network in VirtualBox.

Configuration steps:

1. Open VirtualBox settings
2. Select Network
3. Set Adapter 1 to Host-Only Adapter

Purpose:

This allows the attacker machine (Kali) to communicate with the
target machine (Metasploitable) while keeping the lab isolated
from the main network.
