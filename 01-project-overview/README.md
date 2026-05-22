# 01 - Project Overview

## Business Need

The hotel needed a reliable method to scan documents and send them through email directly from an enterprise multifunction printer.

## Initial Problem

Scan-to-email functionality was not working despite the printer being reachable on the network.

## Initial Assumptions

- SMTP configuration issue
- Network connectivity issue
- Printer configuration issue
- Authentication issue

## Final Root Causes

1. Administrator access was required and controlled by corporate IT.
2. The printer IP was not authorized to use the corporate SMTP relay.
3. SSL/TLS certificate validation failed due to an internal certificate chain.

## Outcome

The printer was successfully integrated with the corporate SMTP relay and scan-to-email functionality was restored.