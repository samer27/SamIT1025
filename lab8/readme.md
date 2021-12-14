# Executive Summary:

In Lab8 Data Analytics and Ethical and Legal Implications, I studied describing various database models and practiced querying a database with SQL (structured query language.) Also, I recognized the critical ethical and legal implications of information systems. What I hope to accomplish from Lab8 is to get a clearer understanding of the ethics and laws of IT.  Also, find out more information about data analytics.

# Data, Information, and Knowledge

i. Data are the raw bits and pieces of information with no context.  Data can be quantitative or qualitative.  By itself, data is not that useful. To be valid, it needs to be given context. For example, it would be information if I told you that “15, 23, 14, and 85″ are the number of students registered for upcoming classes. I have converted data into information by adding the context – that the numbers represent the count of students registering for specific classes.  Once we have put our data into context, aggregated, and analyzed it, we can use it to make decisions for our organization. We can say that this consumption of information produces knowledge. This knowledge can be used to make decisions, set policies, and even spark innovation.

1. When creating a database for a small company, the primary key in the customers and orders table would be an assigned user ID created by me.  A primary key cannot change, so this would mean that if customers changed their name or had a similar name, I would have to remove them from the database and then re-insert them.  This key is a unique identifier for each record in the table.

2. The customers and orders table are related by paying a subscription fee to the small company that allows them discounts and free items, like a membership fee.  

3. A foreign key is a column or group of columns in a relational database table that links data in two tables. It acts as a cross-reference between tables because it references the primary key of another table, thereby establishing a link between them. For example, the foreign key in the orders table would be a CUSTOMER_ID.  A relationship between the primary and foreign keys can be created by introducing a foreign key into the order table that refers to the CUSTOMER_ID in the customer table. The CUSTOMER_ID column exists in both customer and order tables.

iii. Defining a field's data type properly for two fundamental reasons is essential.  First, a data type tells the database what functions can be performed with the data.  For example, if you wish to perform mathematical functions with one of the fields, you must tell the database that the field is a number data type. So if you have a field storing birth year, we can subtract the number stored in that field from the current year to get age.  

The second important reason to define data type is to allocate the proper storage space for your data.   For example, if the First Name field is defined as a text(50) data type, fifty characters are allocated for each first name we want to store. However, if the first name is only five characters long, fifty characters (bytes) will be distributed. While this may not seem like a big deal, if our table ends up holding 50,000 names, we are giving 50 * 50,000 = 2,500,000 bytes for storage of these values. Therefore, it may be prudent to reduce the size of the field, so we do not waste storage space. 

# Big Data

i. It can be said that the Big Data environment has to have these four primary characteristics:

Volume -  You may have heard on more than one occasion that Big Data is nothing more than business intelligence but in a substantial format. More data, however, does not necessarily mean it is Big Data.  Big Data needs a certain amount of data, but having a considerable amount of data does not necessarily mean you’re working on Big Data.  It would also be a mistake to think that all areas of Big Data are business intelligence. Big Data is not limited or defined by the objectives sought with that initiative. However, it will be by the characteristics of the data itself.

Variety - Today, we can base our decisions on the prescriptive data obtained through Big Data. Thanks to this technology, every action of customers, competitors, suppliers, etc., will generate prescriptive information that will range from structured and efficiently managed data to unstructured information that is difficult to use for decision making.  Each piece of data, or core information, will require specific treatment. In addition, each type of data will require specific storage needs (the storage of an e-mail will be much less than that of a video).
Veracity - This V will refer to both data quality and availability. When it comes to traditional business analytics, the data source is going to be much smaller in both quantity and variety. However, the organization will have more control over them, and their integrity will be greater.  When you talk about Big Data, variety will mean more significant uncertainty about the quality of that data and its availability. It will also have implications regarding the data sources you may have.

Velocity - It is possible that Variety and Veracity would not be so relevant and would not be so much pressure when facing a Big Data initiative if it were not for the high volume of information that has to be handled and, above all, for the velocity at which the information has to be generated and managed.  The data will be an input for the technology area (it will be essential to store and digest large amounts of information). And the output part will be the decisions and reactions that will later involve the corresponding departments. The important thing here is that they can react quickly to boost the business area.
 

ii. Big Data Technologies is the software that incorporates data mining, data storage, data sharing, and data visualization. The extended term embraces data and data framework, including tools and techniques to investigate and transform data.  The significant perceptions of rage in technology are widely associated with other technologies like Machine Learning, Deep Learning, Artificial Intelligence, and IoT that are augmented on large scales.

# Structured Query Language 

a. RDBMS stands for Relational Database Management System.  RDBMS is the basis for SQL and all modern database systems such as MS SQL Server, IBM DB2, Oracle, MySQL, and Microsoft Access. The data in RDBMS is stored in database objects called tables. A table is a collection of related data entries, and it consists of columns and rows.

SQL stands for Structured Query Language.  SQL lets you access and manipulate databases.  The purpose of SQL is used to communicate with a database.

b. I selected Employees and Orders from the diagram above. The primary key is the Employee ID.
The foreign key is the Order ID.  The meaning of the relationship between the two tables is that employees need to input the information from customers to facilitate a smooth transaction.   

# SQLSuppliers

![SQLSuppliers](https://user-images.githubusercontent.com/90066230/146021577-3a003f5a-53a0-4b83-af1b-9bcd0bed905d.jpeg)

# SQLProducts

![SQLProducts](https://user-images.githubusercontent.com/90066230/146021733-7157c2d4-3a0c-4f56-9264-3159078e6a14.jpeg)

# SQL Injections

SQL injection is a code injection technique that might destroy your database. Unfortunately, SQL injection is one of the most common web hacking techniques.  SQL injection is the placement of malicious code in SQL statements via web page input.  SQL injection usually occurs when you ask a user for input, like their username/user id. However, instead of a name/id, the user gives you an SQL statement that you will unknowingly run on your database.  To avoid SQL injection flaws is simple. Developers need to either: a) stop writing dynamic queries; and b) prevent user-supplied input which contains malicious SQL from affecting the logic of the executed query.  

# Ethical and Legal Implications

i. One method for navigating new ethical waters is a code of ethics. An excellent example of a code of ethics is the Code of Ethics and Professional Conduct of the Association for Computing Machinery, an organization of computing professionals including academics, researchers, and practitioners.  One of the significant advantages of creating a code of ethics is that it clarifies a professional group's acceptable standards of behavior.  The varied backgrounds and experiences of the group members lead to various ideas regarding what is good behavior. While the guidelines may seem obvious to many, detailed items, provide clarity and consistency. Explicitly stating standards communicates the common policies to everyone in a transparent manner.

ii. A code of ethics is a document that outlines a set of acceptable behaviors for a professional or social group.  Typically, it is agreed to by all members of the group. In addition, the document details different actions that are considered appropriate and inappropriate.

Similar to a code of ethics, this policy outlines what is allowed and not allowed while using the organization’s services.  An everyday example of this is the terms of service that must be agreed to before using the public Wi-Fi at Starbucks, McDonald’s, or even a university. Again, as with a code of ethics, these acceptable use policies specify what is allowed and what is not allowed.  Also, as with codes of ethics, violations of these policies have various consequences.

iii. I selected Alaphabet Inc. or Google.  To ensure that users have a safe and positive experience when using Google Communication Services, their policies guidelines prohibit content and practices. In addition, I examined Privacy and Security.   Google wants users to trust that information about them will be respected and handled with appropriate care. Therefore, all businesses using Google Communication Services must be transparent in handling user data (e.g., the information provided by a user or collected about a user or user's device).

Link:
https://developers.google.com/business-communications/support/aup

# Intellectual Property 

i. WIPO is the global forum for intellectual property (IP) services, policy, information, and cooperation. They are a self-funding agency of the United Nations, with 193 member states.  Its mission is to lead the development of a balanced and effective international IP system that enables innovation and creativity for the benefit of all.

ii. Copyright exists automatically in an original work of authorship once it is fixed in a tangible medium. Still, a copyright owner can enhance copyright protection, the most important of which is registering the work. Although registering a work is not mandatory, for U.S. works, registration (or refusal) is necessary to enforce the exclusive rights of copyright through litigation.
Copyright is the protection given to songs, computer programs, books, and other creative works; any work that has an “author” can be copyrighted.  Under copyright terms, the author controls what can be done with the work, including making copies of the work. Who can do derivative works from the original work.  Who can perform the work publicly.  Who can display the work publicly.  Who can distribute the work.  

iii. The Microsoft svg image I created identifies both a good and service.  The role of a trademark in defining intellectual property is that a trademark is a type of intellectual property protection.  Intellectual property is defined as “property (as an idea, invention, or process) that derives from the work of the mind or intellect.”  A trademark is a word, phrase, logo, shape, or sound that identifies a source of goods or services.  For example, the Nike “Swoosh,” the Facebook “f”, and Apple’s apple (with a bite taken out of it) are all trademarked.

# Information Collection

To comply with COPPA (Children’s Online Privacy Protection Act), organizations must make a good-faith effort to determine the age of those accessing their websites. If users are under thirteen years old, they must obtain parental consent before collecting any information.

The Family Educational Rights and Privacy Act (FERPA) is a US law that protects the privacy of student education records.  This law specifies that parents have a right to their child’s educational information until they reach the age of eighteen or begin attending school beyond the high school level. At that point, control of the information is given to the child. While this law is not specifically about the digital collection of information on the Internet, the educational institutions collecting student information are at a higher risk for disclosing it improperly because of digital technologies.

The Health Insurance Portability and Accountability Act of 1996 (HIPAA) singles explicitly out records related to health care as a particular class of personally identifiable information.  This law gives patients specific rights to control their medical records, requires health care providers and others who maintain this information to get explicit permission to share it, and imposes penalties on the institutions that breach this trust. Since much of this information is now shared via electronic medical records, the protection of those systems becomes paramount.

# Conclusion:

In Lab8 Data Analytics and Ethical and Legal Implications, I studied describing various database models and practiced querying a database with SQL (structured query language.) Also, I recognized the critical ethical and legal implications of information systems.  What I’ve accomplished in this lab is discovering why a code of ethics is required to practice in IT.  In addition, I now know the four big V’s of big data.
