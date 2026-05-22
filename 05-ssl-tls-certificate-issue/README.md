# 05 - SSL/TLS Certificate Issue

## Problem

After SMTP access was approved, the printer still generated errors when SSL/TLS encryption was enabled.

## Root Cause

The SMTP relay used an internal certificate chain that the printer could not validate.

## Technical Explanation

The printer attempted to establish an encrypted connection and validate the certificate presented by the SMTP server. Because the certificate chain was not trusted by the device, SSL/TLS negotiation failed.

## Resolution

SMTP encryption settings were adjusted according to the approved internal relay configuration.

## Lesson Learned

Certificate trust issues are common when enterprise services use internally managed certificate authorities.