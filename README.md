🏷️ Title & Description

# 🔐 SSH Traffic Capture & Analysis Using tcpdump and Wireshark

A hands‑on cybersecurity lab demonstrating how SSH traffic behaves on the network, how the SSH handshake works, and why SSH sessions cannot be decrypted even with private keys. This project captures SSH traffic between Kali Linux and Ubuntu using tcpdump, analyzes the handshake in Wireshark, and documents the cryptographic properties that protect SSHv2.

🚀 Project Introduction

Secure Shell (SSH) is one of the most widely used protocols for remote administration, file transfer, and secure communication. Understanding how SSH behaves at the packet level is essential for SOC analysts, blue teamers, and cybersecurity professionals.

This project captures and analyzes SSH traffic between a Kali Linux client and an Ubuntu server in a controlled VirtualBox homelab. Using tcpdump and Wireshark, the analysis focuses on:

- The SSHv2 handshake  
- Key exchange negotiation  
- Public key authentication  
- Encrypted session behavior  
- Why SSH traffic cannot be decrypted  

This lab demonstrates practical packet‑level analysis skills and reinforces core concepts in encryption, confidentiality, and secure protocol design.

📚 Table of Contents

1. Project Introduction  
2. Lab Environment  
3. Architecture Diagram  
4. Tools Used  
5. Packet Capture with tcpdump  
6. SSH Traffic Analysis in Wireshark  
7. Why SSH Cannot Be Decrypted  
8. Screenshots  
9. Conclusion & Key Takeaways  
10. Future Improvements  

🖼️ Screenshots Section


## 📸 Screenshots

Below are the key screenshots included in this project.

![SSH Handshake](screenshots/ssh_handshake.png)

🧠 Final Summary

This project demonstrates a complete end‑to‑end analysis of SSH traffic in a controlled cybersecurity lab. By capturing packets with tcpdump and analyzing them in Wireshark, the lab highlights:

- How SSHv2 establishes a secure channel  
- How key exchange algorithms are negotiated  
- How public key authentication works  
- Why SSH traffic becomes unreadable after the handshake  
- Why SSH cannot be decrypted due to ephemeral Diffie–Hellman keys  

This lab reinforces critical SOC analyst skills, including packet analysis, protocol understanding, encryption fundamentals, and documentation. It also provides a strong portfolio piece showcasing hands‑on cybersecurity experience.
