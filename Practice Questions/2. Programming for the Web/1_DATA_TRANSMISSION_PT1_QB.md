# **Practice Questions: Data Transmission Using the Web (Part 1)**

## **Multiple Choice Questions**

**1.** *(1 mark)* What is the primary function of the **Domain Name System (DNS)**?  
   - A) Encrypting web traffic between clients and servers  
   - B) Converting domain names into IP addresses  
   - C) Controlling data transmission speeds  
   - D) Managing firewall security rules  

**2.** *(1 mark)* Which of the following correctly describes **Progressive Web Apps (PWAs)**?  
   - A) They require installation from an app store  
   - B) They function like native apps but run in a browser  
   - C) They do not work offline  
   - D) They do not support push notifications  

**3.** *(1 mark)* What is the purpose of **HTTPS** compared to HTTP?  
   - A) It reduces website loading time  
   - B) It compresses website data  
   - C) It secures data transmission using encryption  
   - D) It prevents all cyber threats  

---

## **Short Answer Questions**

**4.** *(3 marks)* Describe the three main components of a **data packet** and their functions in internet communication.  

**5.** *(3 marks)* Explain the difference between **IPv4 and IPv6**, and why IPv6 is needed.  

**6.** *(3 marks)* Compare **FTP and SFTP** in terms of security and functionality.  
> FTP (File transfer protocol) and SFTP (secure file transfer protocol) are protocols that facilitate the transmission of files over a connection. SFTP transmits data that's secured using SSH (secure shell), unlike FTP which transmits in plaintext. This ensures that in transit, data remains secure.

---

## **Extended Response Questions**

**7.** *(4 marks)* Discuss the importance of **secure email transmission** and how protocols such as **SMTP, POP3, and IMAP** function to manage email communication.  
> Emails can potentially contain PII and other confidential and sensitive information. This means that emails need to remail confidential, retain their integrity as a single source of truth, and remain available. SMTP (simple main transfer protocol) is a protocol used to send emails from the client to the email server. Then, the intended recipient fetches the email addressed to them using either POP3 or IMAP. Historically, the cost of server storage outstripped demand, and hence, once the recipient recieves the email, the email is deleted from the server, and the email is only stored on the recipient's device. This compromises the integrity of the email, as now the recipient and sender have two different points of truth. Instead, IMAP enables the server to be the single point of truth of which all emails are held and can be retrieved on demand via a server. While SMTP doesn't have security, newer SMPTS employs secure email transmission through implementing TLS security.




**8.** *(4 marks)* Explain how **SSL/TLS encryption** protects sensitive data during online transactions and give a real-world example of its use.  
> SSL encryption, now replaced with TLS encryption, refers to a method of encryption of data during transit. During online transactions, packets are secured in a layer of security to ensure that the contents of the packets remain encrypted. For example, a HTTPS connection is established between a user and an ecommerce site. During the serverhello and clienthello, SSL/TLS protocols are exchanged and a method of encryption is established for data packets between the server and client. When a transaction is made, the packets are secured through HTTPS due to the added ssl/tls encryption.





**9.** *(4 marks)* How do **data transmission protocols (such as TCP/IP, FTP, and DNS)** work together to enable the functioning of the internet? Provide examples.  
> 








