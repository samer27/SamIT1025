# Executive Summary


# Lucidchart

![DecisionFlowchart](https://user-images.githubusercontent.com/90066230/139426872-427a9268-f530-40a0-ab68-4ac0771a4374.jpeg)

Summary of Experience with Lucidchart

# Introduction to Networking

i. Terms:

Packet = Unit of data.

Packet-Switching = Technology that allows packets of data to be routed based on destination address.

Internet Protocol (IP) Address = Unique identifying number.

Domain Name Server (DNS) = Directory of IP address common names.

Protocol = Set of rules to allow devices to communicate.

![image](https://user-images.githubusercontent.com/90066230/139249003-5c15f8f1-6408-4d52-bf47-d76c164f7e2e.png)

# Networking Hardware

a. The benefit of a switch over a hub includes a switch does what a hub does, but more efficiently.  A hub is the least expensive, least intelligent, and least complicated of the three.  Its job is straightforward: anything that comes in one port is sent out to the others.  That's all.  Meanwhile, a switch pays attention to the traffic that comes across it, and it learns which computers are connected to which port.

![image](https://user-images.githubusercontent.com/90066230/139257844-ad4e101e-549f-4aaf-94ae-52ecc5b2f8c4.png)

1. Initially, a switch knows nothing, and simply sends incoming messages to all ports.

![image](https://user-images.githubusercontent.com/90066230/139258050-c28e3444-0f83-473c-a14f-ea67b427eaea.png)

2. By accepting that first message, however, the switch has learned something: it knows on which connection the sender of the message is located.  Thus, when machine "A" responds to the message, the switch only needs to send that message out to one connection.    

![image](https://user-images.githubusercontent.com/90066230/139258558-170b5a45-3268-454a-8d1c-8bf1a54a34b6.png)

3. By processing the response, the switch has learned something else: it now knows on which connection machine "A" is located.  That means subsequent messages destined for machine "A" need only be sent to that one port.

![image](https://user-images.githubusercontent.com/90066230/139259036-d1d67334-d7fd-463c-a71e-a61a4f22c4f5.png)
   

b. The benefit of a router over hubs and switches is that a router is the smartest and most complicated of the three.  One way to view a router is as a computer that can be programmed to understand, manipulate, and act on the data it handles.  A router operates as a switch for basic routing: it learns the computer's location sending traffic, and routes information only to the neccessary connections.

![image](https://user-images.githubusercontent.com/90066230/139259619-3315d005-4386-4203-86a9-a9a23934ae80.png)

# Network Topologies

a. A SPOF or Single Point of Failure is any non-redundant part of a system that, if dysfunctional, would cause the entire system to fail.  For example, a single point of failure opposes the goal of high availability in a computing system of network, a software application, a business practice, or any other industrial system.   

![image](https://user-images.githubusercontent.com/90066230/139531738-e057851b-81ea-4dbb-9b4b-7f8bb11cfce2.png)

b. An infrastructure topology is used to extend a wired LAN to include wireless devices.  In this topology, the devices communicate with the wired LAN via base stations called an AP, which acts as a bridge between wired and wireless LANs (WLANs). 

Wireless mesh networks (WMNs) are communication networks that comprise radio nodes in which nodes are arranged in a mesh topology.  Mesh topology is interconnectd of all nodes connected with all other nodes on the network.

*** The better choice here would be

![image](https://user-images.githubusercontent.com/90066230/139531744-6dbd5351-b051-4ca8-9253-4a576cafc2e0.png)

# Network Design

![Network Design](https://user-images.githubusercontent.com/90066230/139531771-d4eeae0c-ba0c-4bda-9e0a-8df31f1bdfbe.jpeg)

*** I choose a hybrid topology 

# NSA/CSS

The NSA's role in U.S. cybersecurity is to prevent and eradicate threats to U.S. national security systems, focusing on the Defense Industrial Base and improving U.S. weapons security.  It also strives to promote cybersecurity education, research, and career-building.  

# Cybersecurity and Encryption

a. As part of the Amazon.com online chat, the security triad includes Confidentiality, Integrity, Availablity (CIA) would impact my job as follows:
According to Chapter 6, Information Systems Security, the security triad includes confidentiality, integrity, and availability.  Confidentiality means you want to be able to restrict access to those who are allowed to see it.  This is sometimes referred to as Need To Know (NTK).  Everyone else should be disallowed from learning anything about its contents.  This is the principle of confidentiality.  For example, federal law requires that universities restrict access to private student information.  Therefore, access to grade records should be limited to those who have authorized access.  For example, in an online chat through Amazon.com, I would have to confirm the customer information by asking for their full name, address, and phone number of record.

Integrity is the assurance that the information accessed has not beed altered and truly represents what is intended.  Similarly, as a person with integrity means what they say and can be trusted to represent the truth consistently, information integrity means information truly represents its intended meaning.  However, information can lose its integirty through malicious intent, such as when someone who is not authorized makes a change to misrepresent something intentionally.  An example of this would be when a hacker is hired to go into the university's system and change a student's grade.  In addition, integrity can be lost unintentionally, such as when a computer power surge corrupts a file or someone authorized to make a change accidently deletes a file or enters incorrect information.  Through Amazon.com chat, I could also ask the customer to verify their identity through two-factor authentication.

Availability means information can be accessed and modified by anyone authorized to do so in an appropriate timeframe.  Depending on the type of information, a suitable timeframe can mean different things.  For example, a stock trader needs data to be available immediately, while a salesperson may be happy to get sales numbers for the day in a report the following day.  Online retailers require their servers to be available twenty-four hours a day, seven days a week.  Other companies may not suffer if their web servers are down for a few minutes once in a while.  However, for an enormous-sized company like Amazon.com, the servers need to accessible twenty-four hours a day, seven days a week, to accurately do my job and report to customers what is and is not available.

![image](https://user-images.githubusercontent.com/90066230/139684046-42fdc154-0bef-4103-80c1-2651941c1a14.png)

b. Tools for authentication are used to ensure that the person accessing the information is, indeed, who they present themselves to be.  Authentication can be accomplished by identifying someone through one or more factors: something they know, something they have, or something they are.  For example, the most common form of authentication today is the user ID and pasword.  In this case, the authentication is done by confirming something that the user knows (their ID and password).  However, the user ID and password form of authentication are easy to compromise.  As a result, more robust forms of authentication are sometimes needed.

A more secure way to authenticate a user is through multi-factor authentication.  An example of this would be the use of an RSA SecurID toke.  The RSA device is something you have, and it generates a new access code every sixty seconds.

The final factor, something you are, is much harder to compromise.  This factor identifies a user by using a physical characteristic, such as a retinal scan, fingerprint, or facial geometry.  Identifying someone through their physical charactertistics is called biometrics.

![image](https://user-images.githubusercontent.com/90066230/139725963-d3124169-9251-4d82-b00f-7ae5763aaabd.png)

c.  Once a user has been authenticated, the next step is to ensure that they can only access the appropriate information resources.  This is done through the use of access control.  Access control determines which users are authenticated to read, modify, add, or delete information.  Several different access control models exists.  Two of the more common are: the Access Control List (ACL) and Role-Based Access Control (RBAC).

An information security employee can produce an ACL that identifies a list of users who can take specific actions with an information resources such as data files.  Individual permissions are assigned to each user, such as read, write, delete, or add.  Only users with those permissions are allowed to perform those functions.

ACLs are simple to understand and maintain, but there are several drawbacks.  The primary disadvantage is that each information resource is managed seperately, so it would be pretty tricky if a security adminstrator wanted to add or remove a user to a large set of information resources.  And as the number of users and resources increases, ACLs become harder to maintain.  This has led to an improved method of access control, called role-based access control, or RBAC.  With RBAC, users are assigned roles and access instead of giving specific users access rights to an information resource.  This allows the administrators to manage users and roles seperately, simplifying administration and, by extension, improving security.

![image](https://user-images.githubusercontent.com/90066230/139727292-d295fc95-3425-4fac-9259-43ce92e35546.png)

a. Encryption is a process of encoding data upon its transmission or storage so that onlh authorized individuals can read it.  This encoding is accomplished by software that encodes the plain text that must be transmitted (encryption).  Then the recipient receives the ciphertext and decodes it (decryption).  For this to work, the sender and receiver need to agree on the encoding method so that both parties have the same message.  Known as symmetric key encryption, both parties share the encryption key, enabling them to encode and decode each other's messages.

An alternative to symmetric key encryption is public key encryption.  In public-key encryption, two keys are used: a public key and a private key.  To send an encrypted message, you obtain the public keys, encode the message, and send it.  The recipient then uses their private key to decode it.  The public key can be given to anyone who wishes to send the recipient a message.  Each user needs one private key and one public key to secure messages.  The private key is necessary to decrypt a message sent with the public key.

![image](https://user-images.githubusercontent.com/90066230/139728308-e7a96da1-0870-4c75-b6fb-3e4b8965d378.png)

c. Sometimes referred to as asymmetric cryptography, public-key cryptography is a class of cryptographic protocols based on algorithms.  This cryptography method requires two seperate keys, one that is private or secret and one that is public.  Public key crytography uses a pair of keys to encrypt and decrypt data to protect it against unauthorized access or use.  Network users receive public and private key pairs from certification authorities.  If other users want to encrypt data, they get the intended recipient's key from a shared directory.  This key is used to encrypt the message and send it to the recipient.  When the message arrives, the recipient decrypts it using a private key to which no one else has access.

The increased data security provided by public-key cryptography is its main benefit.  Public-key cryptography remains the most secure protocol (over private key crytpography) because users never need to transmit or reveal their private keys to anyone, which lesses the chances of cybercriminals discovering an individual's secret key during the transmission.
