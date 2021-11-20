# Executive Summary

# Internet Architecture

# Internet Protocol

a.  IP address is a shorter way of saying "Internet Protocol address."  IP addresses are the numbers assigned to computer network interfaces.  among other vital functions, they identify every device connected to the Internet, whether a web server, smartphone, mail server, or laptop.  So when you send an email, visit a website, or participate in a video conference, your computer sends data packets to the IP address of the other end of the connection and receives packets destined for its IP address.  Without the IP address asssigned to our computers, you would have to send paper letters and memos instead of emails.

After years of rapid Internet expansion, the pool of available unallocated addresses for the original Internet Protocol, known as IPv4, has been fully allocated to Internet Services and users.  That's why we need IPv6, the next generation of the Intetnet protocol that has a massively more significant address space than IPv4.

b.

![ipconfig](https://user-images.githubusercontent.com/90066230/140929909-5ab67225-5231-4c71-a90e-6d3238d6da42.png)

c. 

The numbers and names needed to reach another person on the Internet must be unique, so computers know where to find each other.  ICANN (Intetnet Corporation for Assigned Names and Numbers) aligns these unique identifiers across the world.  Without that alignment, the world wouldn't have one global Internet.  It is also a not-for-profit partnership worldwide dedicated to keeping the Internet secure, stable, and interoperable.  In addition, it promotes competition and develops policy on the Internet's unique identifiers.

ICANN doesn't control the content on the Internet.  It cannot stop spam, and it doesn't deal with access to the Internet.  However, through its coordination role of the Internet's naming system, it does have an essential impact on the expansion and evolution of the Internet.  "Universal resolvability" is a common term here.  It means that wherever you are on the network - and hence the word - you receive the same predictable results when you access the network.  Without this, you could end up with an Internet that worked entirely differently depending on your location on the globe.

# TCP/IP

a. TCP/IP means Transmission Control Protocol/Internet Protocol.  A protocol is a set of rules that govern how systems communicate.  For networking, they manage how data is transferred from one system to another.  It is a suite of communication protocols uses to interconnect network devices on the Internet.  A protocol suite is a collection of protocols that are designed to work together.  TCP/IP is also used as a communcations protocol in a private computer network.

The entire IP suite is commonly referred to as TCP/IP.  TCP and IP are the two main protocols, though others are includes in the suite.  The TCP/IP protocol suite functions as an abstraction layer between Internet applications and the routing and switching fabric.

b. TCP/IP uses the client-server model of communication.  This translates to a user or machine (a client) being provided a service, like sending a webpage, by another computer (a server) in the network.

The TCP/IP suite of protocols is categorized as stateless.  Being stateless means, each client request is deemed new because it is unrelated to previous requests.  Being stateless frees up network paths so they can be used constantly.

i. When working with changing technology, layers/tasks are essential.  This is due to the design of the overall effciency of the post office to make a delivery.  The fundamental idea is that any of the layers can be changed without altering the other layers.

ii. The "application" layer is for software types like the network.  The application layer feeds network services to end-user applications.  Network services are protocols that operate with the user's data.  For example, in a web browser application, the Application layer protocol HTTP packages the data needed to send and receive web page content.

# Internet Security

a. HyperText Transfer Protocol, or HTTP, is most likely the protocol of choice in the world.  HTTP is the protocol that is used for viewing web pages on the Internet.  For example, when typing in a web address, such as google.com, you'll see that HTTP is automatically added at the beginning of the web address.  As a result, this shows that you are now using HTTP to retrieve this web page.

b. HTTP uses specific protocols that secure data.  When data travels over the Internet, it goes through the public Internet.  It starts on your computer and must travel across the public Internet to get to a particular webserver.  As a result, hackers can easily exploit sensitive information by listening when it travels and tranfers through the public Internet.  Enter HTTPS and why it was developed.

HTTPS stands for Secure HyperText Transfer Protocol.  HTTPS is HTTP with a security feature.  Secure HTTP encrypts the data that is being retrieved by HTTP.  It ensures that all the information transferred over the Internet between computers and servers is protected by making the data impossible to read.  This is done by using encryption algorithms to scramble the data transmitted.  So by using secure HTTP, all the data, including anything you type, is no longer sent in cleartext.  So, if a hacker were to try and steal information, they would get a bunch of meaningless data because the data is encrypted.  The hacker would not be able to crack the encryption to unscramble the data.

# Securing Your Web Browser

a.  In today's world, web browsers are installed on almost every computer.  Due to web browsers' frequent use, it is essential to configure web browsers securely.  Unfortunately, the web browser with an operating system is often not set up in a secure default configuration.  Not securing your web browser can quickly lead to various computer problems.  The problems include anything from spyware being installed without your knowledge to intruders taking control of your computer.

b.  One risk described in the article that stood out to me was Java.  Java is an object-oriented programming language that can be used to develop dynamic content for websites.  A Java Virtual Machine, or JVM, is used to execute the Java code, or "applet," provided by the website.  Some operating systems come with a JVM, while others require a JVM to be installed before using Java.  Java applets are operating system independent.

Java applets usually execute within a "sandbox" where the communication with the rest of the system is reduced.  However, various applications of the JVM contain vulnerabilities that allow an applet to bypass these constraints.  Signed Java applets can also bypass sandbox restrictions, but they generally prompt the user before executing.

# Internet Programming

a.  Tim Berners-Lee was responsible for the invention of the World Wide Web in 1989.  Tim Berners-Lee also founded the World Wide Web Consortium (W3C) in 1994.  The W3C mission is to lead the World Wide Web to its fullest potential by developing protocols and guidelines that ensure the long-term growth of the Web.

b.  An essential "standard" that stood out to me was Browsers and Authoring Tools.  It appeared vital because the web's usefulness and growth depend on its universality.  Web users should publish regardless of the software used, the computer owned, the language spoken, whether wired or wireless, regardless of our sensory or interactions modes.  Users should access the web from any hardware that can connect to the Internet - stationary or mobile, small or large.  W3C enables this listening and blending via international web standards.  These standards ensure that all the ridiculous talent continues to improve a web open to all of us.

# WebPage

![WebPage](https://user-images.githubusercontent.com/90066230/142643552-68c4d33e-3b3f-442a-a560-9c4112f1008f.jpg)

# WebPageWithCSS

![WebPageWithCSS](https://user-images.githubusercontent.com/90066230/142643793-59ae3374-03c4-4703-8cb6-8fe58d3df378.jpg)

# HTML5 and CSS

HTML5, or HyperText Markup Language, is a simple data format used to create hypertext documents that are portable from one platform to another.  HTML has been in use by the World-Wide Web global information initiative since 1990.  Previously, informal documentation on HTML has been available from several sources on the Intetnet.  This specification brings together, clarifies, and formalizes a set of features that roughly corresponds to the capabilities of HTML in everyday use before June 1994.  In addition, many new features to HTML are being proposed and experimented with within the Internet community.  My approach here was to follow the guidelines outlined by w3schools.com and follow what was said.  

CSS, or Cascading Style Sheets, is the language used to style an HTML document.  CSS describes how HTML elements should be displayed on a screen, paper, or in other media.  CSS saves a lot of work.  It can control the layout of multiple web pages all at once.  In addition, external stylesheets are stored in CSS files.  My approach includes keeping things as clean and straightforward as possible.

# HTML and XML

XML stands for eXtensible Markup Language.  XML was designed to store, transport, and carry data - focusing on what data is.  Also, XML tags are not predefined like HTML tags are.  
HTML works with predefined tags like <p>, <h1>, <table>, etc.  With XML, the author must define both the tags and the document structure.  Most XML applications will work as expected even if new data is added (or removed).

  
# Components of a URL
  
Scheme =
Domain = 
Top level domain =
Default page =
Parameters = 
Anchor = 


  
# WebStructure
  
![WebStructure](https://user-images.githubusercontent.com/90066230/142728303-251ab1f2-187b-4043-a594-79dde9229a63.jpg)
  

# ImageProperties
  

![ImageProperties](https://user-images.githubusercontent.com/90066230/142728347-2989aa95-c4cc-481c-91bd-424d4367ff2f.jpg)


# WebPageWithImage
  

  
# Conclusion
  

