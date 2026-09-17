# Security Analysis

## Introduction

The Nmap scan was performed against my local computer (`127.0.0.1`) for cybersecurity learning purposes.

The scan helps identify network services that may be accessible through open ports.

## Understanding Open Ports

An open port means that a network service is listening for connections.

Open ports are not automatically a security vulnerability. However, unnecessary or poorly secured services can increase the attack surface of a computer or network.

## Common Network Services

| Port | Service | Common Purpose | Security Consideration |
|------|---------|----------------|------------------------|
| 22 | SSH | Secure remote access | Use strong authentication and restrict access |
| 80 | HTTP | Web traffic | Use HTTPS where possible |
| 443 | HTTPS | Secure web traffic | Keep the web service updated |
| 3389 | RDP | Remote desktop access | Restrict access and use strong authentication |

## Potential Security Risks

Some common risks associated with network services include:

- Unnecessary services being left enabled
- Weak passwords
- Outdated software
- Unrestricted remote access
- Poor firewall configuration
- Unauthorized access attempts

## Security Recommendations

To improve network security:

1. Disable services that are not required.
2. Keep operating systems and applications updated.
3. Use strong passwords and authentication methods.
4. Configure a firewall to restrict unnecessary connections.
5. Monitor network activity for unusual behaviour.
6. Limit remote access to trusted users and networks.

## Conclusion

Network scanning is an important part of cybersecurity because it helps identify services that are exposed on a system.

Nmap can be used by security professionals to understand the network attack surface and identify areas that require further investigation.

This project was conducted against my own local computer for educational purposes.
