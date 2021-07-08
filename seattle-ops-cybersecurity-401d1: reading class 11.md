David Armstrong 10-19-2020

The writer of this article asserts that stealing passwords via Wireshark is an impossibility. You would have to be connected to the same network and there 
would have to be no encryption for that to be the case. Starting out, it is necessary for the network adapter to be in promiscuous mode, which is the 
default case with Wireshark. If the adapter is wireless, that must be in “monitor mode” which is possible with npcap on Windows.

Next, a port mirror must be set up with the listening port so that packets are duplicated and sent to Wireshark. In order to get around that, one can use 
ARP spoofing to do a man-in-the-middle attack. With an unencrypted protocol it is then possible to intercept the packets and retrieve the data. However, 
if the data is encrypted in any way, you would have to have the private key to decrypt it. So bottom line, you’re not going to get any passwords.
