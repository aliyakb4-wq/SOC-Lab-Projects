# Protocol Analysis

## Objective

Analyze common network protocols using Wireshark and understand how different protocols communicate over a network.

---

# DNS

### Observation

- Captured DNS queries and responses.
- Observed A and AAAA record lookups.
- Verified successful domain name resolution for google.com and example.com.

### Finding

DNS translates domain names into IP addresses before communication begins.

---

# TCP

### Observation

- Observed the TCP three-way handshake.
- Identified SYN, SYN-ACK and ACK packets.

### Finding

TCP establishes a reliable connection before transferring data.

---

# UDP

### Observation

- Captured UDP packets used for DNS and NTP communication.
- No connection establishment was required.

### Finding

UDP is a connectionless protocol used for fast communication.

---

# TLS

### Observation

- Observed TLS 1.3 Client Hello.
- Observed Server Hello.
- Captured encrypted Application Data.

### Finding

TLS encrypts network communication and protects transmitted data.

---

# HTTP

### Observation

- HTTP filter returned no packets.

### Finding

The website used HTTPS instead of HTTP, so traffic was encrypted using TLS.

---

# ICMP

### Observation

- Captured Echo Request and Echo Reply packets.
- Verified successful ping communication.

### Finding

ICMP is commonly used for network testing and troubleshooting.

---

# Conclusion

This lab demonstrated how Wireshark can be used to inspect network traffic, identify common protocols, observe packet exchanges, and understand communication between hosts.
