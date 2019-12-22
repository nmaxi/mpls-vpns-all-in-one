Cisco MPLS VPNs (All-in-One!)
EVPN, VPLS, VPWS, L3VPN
Segment-Routing (IOS-XR, IOS-XE)
• EVPN: Multi-homed (using Port-Channel between CE and 2PEs), Single-homed, p2p (VPWS)
• VPLS: BGP Signaling and Label Distribution
• VPWS: xConnect AToM
• L3VPN: BGP, OSPF, EIGRP, Static-Route, also included some Inter-VRF route-leaking
• IGP: IS-IS (Segment-Routing for MPLS Label Distribution)
• BGP Address-families: L2VPN EVPN, L2VPN VPLS (BGP Signaling), VPNv4 Unicast
• 6 PE-Routers (XRv, CSR1000v)
• 25 CE-Devices (IOL L3, IOL L2)
Images: XRv 6.1.3, CSR1000v 17.1.1, IOL L3 15.7(3)M2, IOL L2 15.2
• Because XRv9000 still does not support full L2VPN Forwarding (it prevents Bridge-Domain creation) I did not use it as L2VPN PEs
• It took me 16 hours to design/build and configure this lab!
• The next Lab would be a Multicast one
• Using the awesome emulator EVE-NG Pro
☆ Lab Screenshots: https://lnkd.in/dcjqYsM

* MPLS VPN Labs, Created by Navid Yahyapour (NMAXi)
Lab file URL:
  https://drive.google.com/open?id=1OMsHLT3YrZSjk-uAQjpqcA9Uh319tDpE
! You can only import it into EVE-NG Pro (not the Community edition)  

You can also find configuration files on my GitHub page:
  https://github.com/nmaxi
  
*** My LinkedIn profile: https://www.linkedin.com/in/navid-yahyapour/ ***