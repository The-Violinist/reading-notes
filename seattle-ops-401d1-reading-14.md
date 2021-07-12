David Armstrong 10-22-2020

Traffic mirroring is the procedure of copying certain transmissions to or from an endpoint, and sending 
it to another computer, known as a sniffer box. This is done by creating a connection for a source 
and target, setting up filters, and then starting a session. The AWS terms are:

Target: This is the box that will be sniffing packets
Source: any instance which will be directed to the target
Traffic Mirror Filter: the rules which will initiate the mirroring of data to the target
Traffic Mirror Session: This is the actual connection which is created between the Source and the Target.

Traffic mirroring can be done within a subnet, a VPC or even between VPCs (and account owners) by means 
of a peering connection. Mirrored transmissions are encapsulated with a VXLAN header and sent via port 
4789. From an administrative standpoint, authorization to create mirroring is set up, and permission 
given, using IAM policies.
