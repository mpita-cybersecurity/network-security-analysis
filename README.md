# Network Security Analysis

## Project Overview

This is a beginner-level network security analysis project created to practise identifying IP addresses, network ports, services and potential security risks.

The project uses a simulated network environment for educational purposes.

## Objective

The objective of this project is to understand how network services are exposed through ports and how a cybersecurity analyst can assess whether those services require further investigation or security controls.

## Simulated Target

**IP Address:** `192.168.1.10`

The IP address used in this project is fictional and represents a simulated internal server.

## Discovered Ports

| Port | Protocol | Common Service | Security Consideration                                              |
| ---: | -------- | -------------- | ------------------------------------------------------------------- |
|   22 | TCP      | SSH            | Remote access should be restricted and securely configured          |
|   80 | TCP      | HTTP           | Unencrypted HTTP traffic may expose information                     |
|  443 | TCP      | HTTPS          | Encrypted web communication; configuration should still be reviewed |

## Initial Analysis

Port 22 indicates that SSH may be available for remote administration.

Port 80 indicates that an HTTP web service may be available.

Port 443 indicates that an HTTPS web service may be available.

Open ports are not automatically evidence of a security incident. They represent services that should be reviewed to determine whether they are necessary, securely configured and appropriately restricted.

## Security Considerations

An organisation should:

* Disable unnecessary services.
* Restrict administrative services such as SSH.
* Use strong authentication.
* Keep network services patched.
* Use firewalls and access controls.
* Monitor network activity and security logs.
* Prefer HTTPS for web communication.
* Regularly review exposed services.

## Skills Demonstrated

* Basic networking concepts
* IP address identification
* Port identification
* TCP concepts
* Network-service identification
* Basic security-risk assessment
* Security documentation

## Disclaimer

This is a simulated educational project.

No external systems or unauthorised networks were scanned or tested.
