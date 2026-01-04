# AD + PKI + mTLS Secure API Lab
Enterprise-style lab integrating Active Directory, PKI, and mutual TLS for secure internal APIs

## Overview
This project demonstrates an enterprise-style security architecture combining:
- Active Directory for identity management
- Public Key Infrastructure (PKI) for trust establishment
- Mutual TLS (mTLS) for strong client and server authentication

The lab simulates how internal services are secured in corporate environments.

## Architecture
- Windows Server Domain Controller (corp.local)
- Enterprise Certificate Authority
- Domain-joined Windows client
- Internal API secured with HTTPS and mTLS
- Flask application behind Nginx

## Key Features
- Certificate-based authentication
- SAN-based hostname validation
- Mutual TLS (client + server certificates)
- Certificate revocation testing
- Trust chain validation via local CA

## Technologies Used
- Windows Server (AD, PKI)
- OpenSSL
- Nginx
- Flask (Python)
- VMware Workstation

## Security Concepts Demonstrated
- Identity before encryption
- Chain of trust
- Enterprise PKI vs standalone certificates
- Certificate revocation impact on access
- Internal service authentication with mTLS

## Disclaimer
This project is for educational purposes only. No private keys or sensitive material are included.
