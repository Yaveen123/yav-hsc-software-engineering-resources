# **Practice Questions: Data Transmission Using the Web (Part 2)**

## **Multiple Choice Questions**

**1.** *(1 mark)* What is the primary function of **SSL/TLS certificates**?  
   - A) Converting IP addresses into domain names  
   - B) ➡️ Encrypting data between a client and a server  
   - C) Speeding up web page loading times  
   - D) Storing password hashes on a server  

**2.** *(1 mark)* How does **asymmetric encryption** differ from symmetric encryption?  
   - A) It uses a single key for encryption and decryption  
   - B) ➡️ It requires both public and private keys for encryption and decryption  
   - C) It does not involve encryption keys  
   - D) It only encrypts file names, not data  

**3.** *(1 mark)* What is the purpose of a **hash function** in secure communication?  
   - A) It compresses data before transmission  
   - B) ➡️ It verifies data integrity by generating a fixed-length output  
   - C) It encrypts user passwords for transmission  
   - D) It speeds up internet browsing by caching web pages  

---

## **Short Answer Questions**

**4.** *(3 marks)* Explain the difference between **plain text and cipher text**, and why encryption is necessary for secure communication.  
> Plain text refers to transmitted data that is unencrypted, whereas cipher text refers to encrypted data that can only be seen by unencrypting the data using a specific key. Data encryption enables the confidentiality, as the only person who can read the data is the person who has the correct key. This is fundamental is secure communication, as data needs to be encrypted during transit.

**5.** *(3 marks)* Describe the steps involved in an **encryption handshake** when establishing a secure HTTPS connection.  
> A ClientHello sends a list of SSL/TLS protocols that it supports to the server. The server chooses a synonymously supported protocol, and uses that send a public key to the client. The client is able to generate a shared secret based on the sent public key, which is then sent back to the server. The server uses the shared secret, and swaps the asymmetric encryption into symmetric encryption using the shared secret.


**6.** *(3 marks)* What is the role of **digital signatures** in verifying the authenticity of transmitted data?  
> Digital signatures refer to hashes generated on a piece of data prior to transmission, which can be checked against a regenerated hash post-transmission to verify the authenticity of the data. By generating a unique, fixed-length digest as a signature, the recipient can ensure that the data in transmission has not been tampered with.

---

## **Extended Response Questions**

**7.** *(4 marks)* Discuss the impact of **big data on web architecture**, including the role of **data mining, metadata, and streaming service management**.  
> Big data refers to data of significantly high velocity, variety, and volume. Each three pillars require significant changes to the way web architecture operates. Data mining, the process of deriving trends from datasets, requires more advanced tools outside of basic statistical modelling, which can come in the form of ML tools or other advanced systems to analyse data and derive insights. Metadata refers to data about data. In the light of big data, metadata needs to be designed with granularity and completeness to ensure that the data is as accurate as possible. 


**8.** *(4 marks)* Explain how **encryption algorithms** such as AES, RSA, and ECC enhance data security, and provide examples of their real-world applications.  
> Encryption algorithms, like AES, RSA, and ECC facilitate secure data transmission by enabling the encryption of data in transit. For example, when a customer logs onto their bank, a HTTPS connection is established, and data is encrypted using encryption algorithms, like AES, RSA, and ECC. 

**9.** *(4 marks)* How does the **TLS encryption handshake process** work, and why is it crucial for securing online transactions?  














