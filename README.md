# hub-and-spoke-network

I designed a hub-and-spoke Azure network where the hub hosts centralized security services like Azure Firewall, and spoke VNets host work vms. All  inter-spoke traffic is forced through the firewall using UDRs, with DNAT for admin access and application rules for outbound control.
The configuration part and the architecture diagrams are attached in the PDF.
