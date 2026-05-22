# 04 - SMTP Relay Integration

## Objective

Configure scan-to-email functionality using a corporate SMTP relay.

## Problem

The printer was unable to successfully send email after SMTP configuration.

## Investigation

Possible causes investigated:

- Incorrect SMTP settings
- Authentication issues
- Network restrictions
- SMTP relay access control
- SSL/TLS issues

## Key Finding

The printer IP address was not authorized to use the corporate SMTP relay.

## Resolution

A request was submitted to authorize the printer IP. After approval, communication with the SMTP relay was successfully established.

## Technical Takeaway

Corporate SMTP relays commonly restrict access using IP allowlists.