#  Homelab Network with Cisco Standalone AP with VLANs and WPA2 Authentication
This project documents a basic home lab network setup with a router, switch, and standalone access point, connecting multiple clients. Set up multiple SSIDs with VLANs to separate network traffic for different user groups. Configured WPA2 authentication for secure access.

## Files
- **`configuration_files/`**  
  All network device configuration files, organized by project type.

- **`configuration_files/simple_configuration/`**  
  Basic wireless setup with no VLAN segmentation — single SSID scenario.

- **`configuration_files/vlan_segmentation/`**  
  Advanced wireless setup with multiple SSIDs mapped to separate VLANs.

- **`configuration_files/vlan_segmentation/wpav2_authentication/`**  
  Configuration files for WPA2-secured wireless networks.

- **`diagrams/`**  
  Visual network diagrams showing topology, VLANs, and traffic flow.

- **`verification_commands.txt`**  
  A reference file containing useful CLI verification and troubleshooting commands for Cisco Autonomous APs and switching.

## Devices Used

- **Switch**: Cisco Catalyst WS-C3560-24PS-S
- **Access Point**: Cisco AIR-SAP2602L-E-K9
- **Router**: Cisco 1921 Integrated Services Router (CISCO1921/K9)
