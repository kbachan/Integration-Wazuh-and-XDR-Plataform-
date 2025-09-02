# Integration-Wazuh-and-XDR-Platform-

This project documents the process of integrating an Extended Detection and Response (XDR) Platform with Wazuh SIEM.  
The integration enables:
- Secure forwarding of endpoint telemetry and security events.  
- Centralized monitoring and correlation inside Wazuh.  
- Improved incident detection and response capabilities.  

## Architecture
- **XDR Platform**: Provides endpoint visibility, advanced threat protection.  
- **Wazuh SIEM**: Receives, normalizes, and correlates security events.  

## Key Steps
1. Configure event forwarding from the XDR Platform.  
2. Set up the connector with secure certificates and communication over port.  
3. Validate log ingestion in Wazuh (`/var/ossec/logs/archives/archives.log`).  
4. Confirm event correlation and alert generation.  

## Results
The integration successfully improved visibility of endpoint activity and allowed faster detection of security incidents through centralized SIEM correlation.

<img width="795" height="291" alt="image" src="https://github.com/user-attachments/assets/7107c5e1-1ea3-4409-b64a-fd8a3a6f60ac" />


This lab was developed on Google Cloud.
