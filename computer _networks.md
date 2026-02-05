#  Computer Networks 

### 🔹 Computer Networks – Full Course by Kunal
A comprehensive YouTube lecture covering core networking concepts with clear explanations and examples. 
- [Computer Networks Full Course – Kunal (YouTube)](https://youtu.be/IPvYjXCsTg8?si=yShvdpl_XAADFTYC)
---

## Networking Models – Core Foundations 

### 🔹 OSI Model (7 Layers) – In-Depth Explanation 📖   
- [Understanding the OSI Model – All 7 Layers Explained](https://makarand-khiste.medium.com/understanding-the-osi-model-all-7-layers-explained-with-architecture-afd42c7b7483)
### 🔹 TCP/IP Model – From Novice to Pro📖  
- [Mastering the TCP/IP Model – Layers & Advanced Networking](https://medium.com/@nay1228/day-2-mastering-the-tcp-ip-model-layers-and-advanced-networking-challenges-80d4fffdc6a9)
---

## Cookies

### 🔹 Using HTTP cookies- complete basic information 📖
- [Using HTTP Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Cookies)
### 🔹 Third Party cookies- complete information 📖
- [Third Party cookies](https://developer.mozilla.org/en-US/docs/Web/Privacy/Guides/Third-party_cookies)
---

## How Does Email Work?

### 🔹network processes behind the working of email
- [How does Email Work](https://medium.com/@shunxianou/how-does-email-work-5964aec2d314)
- <img width="395" height="268" alt="image" src="https://github.com/user-attachments/assets/56ef7137-2946-465c-87d4-873c4259010b" />

## Domain Name systems

### 🔹DNS, Working of DNS,Structure of DNS, types of Domains ,DNS queries,
- [DNS](https://www.geeksforgeeks.org/computer-networks/domain-name-system-dns-in-application-layer/)
  - <img width="477" height="201" alt="image" src="https://github.com/user-attachments/assets/fd00cdb3-c405-4270-ace0-b731891e511a" />

## Transport layer
  - Main Protocols Transmission Control Protocol
    -  (TCP): A reliable, connection-oriented protocol that ensures data arrives in order and without errors using a three-way handshake (\(SYN\), \(SYN-ACK\), \(ACK\)). It is used for web browsing (HTTP), email (SMTP), and file transfer (FTP).User Datagram Protocol
    -   (UDP): A fast, connectionless protocol that does not guarantee delivery or order. It is used for real-time applications like streaming, voice over IP (VoIP), and DNS
    -   TCP uses several timers to ensure that excessive delays are not encountered during communications. Several of these timers are elegant, handling problems that are not immediately obvious at first analysis.
    -   this layer takes care of cognestion control,{explore the related algorithms}
    -   Transport layer sequence numbers (specifically in TCP) are 32-bit identifiers assigned to each byte of transmitted data to ensure ordered delivery, reliability, and error control. By numbering segments sequentially, the receiver can reassemble out-of-order packets, detect missing data, and handle packet retransmission.

