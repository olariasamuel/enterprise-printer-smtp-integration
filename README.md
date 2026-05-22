# Enterprise Printer SMTP Integration and Network Troubleshooting

## Project Summary

This project documents the deployment and troubleshooting of an enterprise multifunction printer in a hotel environment. The goal was to connect an HP Color LaserJet Enterprise MFP M480 to the appropriate network and configure scan-to-email using a corporate SMTP relay.

The project involved network validation, printer administration, vendor coordination, SMTP relay access control, SSL/TLS troubleshooting, and final scan-to-email validation.

## Objective

Configure an enterprise printer to send scanned documents via email using the corporate SMTP relay while connected to the correct hotel network.

## Environment

- Printer: HP Color LaserJet Enterprise MFP M480
- Network: Hotel-managed segmented network infrastructure
- Network provider/vendor: Third-party managed network provider
- Email service: Corporate SMTP relay
- Management interface: HP Embedded Web Server (EWS)

## Skills Demonstrated

- Network troubleshooting
- Printer administration
- Embedded Web Server configuration
- SMTP relay configuration
- IP allowlisting and access control
- SSL/TLS certificate troubleshooting
- Vendor coordination
- Root cause analysis
- Technical documentation

## High-Level Workflow

1. Connected the printer to the appropriate hotel network.
2. Accessed the printer through the HP Embedded Web Server.
3. Identified that printer configuration pages required administrator access.
4. Obtained approved administrator credentials through the proper support channel.
5. Performed a factory reset and reconfigured the printer.
6. Configured the corporate SMTP relay.
7. Identified that the printer IP was not authorized to use the SMTP server.
8. Submitted a request to allowlist the printer IP.
9. Troubleshot SSL/TLS certificate validation errors.
10. Validated successful scan-to-email functionality.

## Final Result

The printer was successfully configured to send scanned documents through the corporate SMTP relay after the printer IP was approved and SMTP settings were corrected.

## Repository Structure

```text
enterprise-printer-smtp-integration/
├── README.md
├── 01-project-overview/
├── 02-network-deployment/
├── 03-printer-admin-access/
├── 04-smtp-relay-integration/
├── 05-ssl-tls-certificate-issue/
├── 06-final-resolution/
├── screenshots/
└── lessons-learned/
```

## Security and Privacy Notice

This repository is a sanitized technical documentation project. It does not include passwords, real IP addresses, MAC addresses, serial numbers, internal hostnames, real email addresses, ticket numbers, or sensitive corporate information.
