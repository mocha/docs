<!--<meta>
{
    "title":"Packet Connect: Overview",
}
</meta>-->

Packet Connect is a low latency, a highly reliable direct connection from Packet to other networks and cloud providers.

This Layer 2 service is built from the ground up to be a cloud-native network service focused on developers and their needs. The service is fully automated via native APIs to create virtual connections at various speeds from 100 Mbps to 10 Gbps.

The Packet Connect service is currently offered at EWR1 and SJC1 data centers, with plans to support additional Packet facilities in the near future. Packet Connect currently supports Microsoft Azure ExpressRoute, with Google Cloud Platform Interconnect and Amazon Web Services Direct Connect, and many others coming soon. Physical cross-connects in our Packet Connect markets are also supported.

Packet customers can create a virtual interconnect between the Packet Data center and cloud provider through the self-serving portal or via the APIs. Each virtual interconnect corresponds to a VLAN subnet the customer has created in both the Packet data center and in the hyperscale data centers.  Each virtual interconnect is capped at a CIR of anywhere from 100Mbps to 10Gbps. 

With Packet listed as a partner on Azure direct connect portals, once an interconnect is purchased, Azure generates a pairing key. The pairing key generated by Azure is then used by Packet to enable the interconnect to the Azure endpoint. Users can then create the interconnect for that VLAN with the desired port speed. Packet limits this service to 12 Interconnects per customer.s

Packet Connect is billed per location, per circuit (virtual or physical) on total port capacity,  and usage (per GB).  Full Pricing information is available [here](https://www.packet.com/cloud/all-features/packet-connect/).

  

### How do I setup Packet Connect?

You can find quick start guides for our partners here:

[Microsoft Azure](https://support.packet.com/kb/articles/packet-connect-azure)

Additional guides will become available as providers are added.