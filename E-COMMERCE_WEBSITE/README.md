# E-COMMERCE_WEBSITE
 *SOFTWARE
REQUIREMENTS
SPECIFICATION*
For
E-commerce website
Prepared by:-
Lokeshkumar V
Harish N
Kaviyarasu V
Santhaprasanth sah V
Academic Year: 2023-2024
Department of Computer Science and Engineering
1. Introduction
1.1 Purpose
The purpose of this document is to define the requirements and specifications for the
developmentof an Ecommerce website. This website aims to provide an online platform 
for users to browse, search for, and purchase a wide range of products and services. The 
website will offer a user- friendly shopping experience, facilitate secure transactions, and
ensure seamless ordermanagement.
1.2 Document Conventions
➢ Entire document should be justified.
➢ Convention for Main title
Font face: Times New Roman
Font style: Bold
Font Size: 14
➢ Convention for Sub title
Font face: Times New Roman
Font style: Bold
Font Size: 12
➢ Convention for body
Font face: Times New Roman
Font Size: 12
1.3 Scope of Development Project
The Ecommerce website project is defined by a comprehensive set of key features that 
collectively contribute to its functionality and user experience. These features encompass 
user registration and authentication, facilitating the seamless onboarding of users and 
ensuring secure access to the platform. Additionally, the website will include a robust product 
catalog and search functionality, enabling users to easily browse and locate products of
interest. A shopping cart and checkout processwill streamline the purchasing journey, while 
secure payment processing mechanisms will guarantee the safe handling of financial 
transactions. To enhance post-purchase satisfaction, the website will offer order tracking and 
management capabilities, allowing users to monitor the progress of their orders. Furthermore,
user reviews and ratings will enable customers to share feedback and make informed 
decisions. An administrative panel for product and user management will empower site
administrators with the tools to maintain and curate the platform's content. Finally, the
implementation of reporting and analytics features will provide valuable insights into user 
behavior and website performance, supporting data-driven decision-making and continuous 
improvement efforts.
Department of Computer Science and Engineering
1.4 Definitions, Acronyms and Abbreviations
HTML: Hyper Text Markup Language
CSS: Cascading Style Sheets
JavaScript: A scripting language for web development
UI: User Interface
UX: User Experience
API: Application Programming Interface
CMS: Content Management System
SSL: Secure Sockets Layer
PCI DSS: Payment Card Industry Data Security Standard
RDBMS: Relational Database Management System
1.5 References
➢ Books
 Software Requirements and Specifications: A Lexicon of Practice, Principles
and Prejudices (ACM Press) by Michael Jackson
Software Requirements (Microsoft) Second Edition By Karl E. Wiegers
Software Engineering: A Practitioner’s Approach Fifth Edition By Roger S. Pressman
Department of Computer Science and Engineering
2. Overall Descriptions
2.1 Product Perspective
Use Case Diagram of Ecommerce website
This is a high-level diagram of the Ecommerce project providing a basic overview. The users 
can be either customers or administrators. The system will offer search functionality to
facilitate the search forproducts and services. This search will be based on various criteria such 
as product name, category, or keyword. Additionally, administrators can manage and update 
product listings and user accounts withinthe system.
The users of the system can browse products, add them to their shopping carts, and proceed 
to checkout. They can also leave reviews and ratings for products they have purchased.
Customers canmake payments for their orders using various payment methods provided by
the system.
Administrators have the capability to manage the product catalog, handle user accounts, and 
generate reports and analytics to monitor website performance. The system also handles user
authentication and secure payment processing to ensure a safe and seamless shopping 
experience for customers
Department of Computer Science and Engineering
2.2 Product Function
Entity Relationship Diagram of Ecommerce Website
The Ecommerce Website System offers real-time online access to a comprehensive catalog of
productsavailable on the platform, along with user account information. The primary objective
of this project isto streamline and automate various processes, reducing the need for manual
intervention. This software empowers the system to efficiently manage product orders, 
processing returns, calculating and handling payments, and generating a variety of reports for
data tracking and analysis, all in
alignment with the requirements of the end users.
The system's administrators, equivalent to site administrators in an Ecommerce context, 
exercise control over user accounts and product listings. The system maintains an up-todate record of userinteractions, such as product orders and returns, within the database.
The administrators can easily
retrieve user account details from the database when necessary. Valid users, in this context,
would be equivalent to registered customers on the Ecommerce website, who can access their
account information and view transaction history.
Department of Computer Science and Engineering
2.3 User Classes and Characteristics
The Ecommerce Website System caters to administrators and customers. Administrators wield 
full control, while customers, including staff members, enjoy online shopping and may have
specializedaccess based on their roles.
The features that are available to the Administrator are :-
• Manage Product Categories : Create and oversee different product categories.
• View Product Listings : Access a list of products available in each category.
• Process Returns : Handle product returns from customers.
• Add New Products : Add new products and their details to the system database.
• Edit Product Information : Modify information for existing products in the catalog.
• Generate Product Reports : Generate reports detailing the current product listings.
• Review Order Reports : Access reports related to customer orders.
• Access User Accounts : Retrieve information and manage user accounts on the
website.
The features that are available to the Customers are:-
• Browse Product Categories: View different product categories available on
thewebsite.
• Explore Product Listings: Access lists of products available within each category.
• Create User Account: Register and own a user account on the website.
• View Purchase History: See a history of previously purchased products.
• Request New Products: Place requests for new products to be added to the catalog.
• View Issued Product History: Review the history of products previously
purchased orordered.
• Search for Specific Products: Utilize search functionality to find particular
productsof interest.
2.4 Operating Environment
The Ecommerce website will operate in a web-based environment accessible through common 
web browsers such as Google Chrome, Mozilla Firefox, and Microsoft Edge. While it is
primarily designed for modern browsers, compatibility with older versions, such as Internet 
Explorer 11 and above, will also be ensured. Users will only need an internet connection to 
access the online platform, and there are no specific hardware requirements as it will be 
accessible from various devices, including desktops, laptops, and mobile devices
Department of Computer Science and Engineering
2.5 Assumptions and Dependencies
The assumptions are:-
• Error-Free Code: The development team will strive to produce error-free code
throughrigorous testing and quality assurance processes.
• User-Friendly Interface: The website will be designed with a user-friendly
interfaceto ensure ease of use for customers.
• Database Storage: All user, product, and transaction information will be
storedsecurely in a database accessible by the website.
• Database Performance: The system will have ample storage capacity and
optimizeddatabase performance to ensure fast data access.
• Search Functionality: The system will provide robust search functionality and
supportquick and efficient transactions.
• 24/7 Availability: The Ecommerce website will be operational 24 hours a
day toaccommodate users from different time zones.
• Accessibility: Users will be able to access the website from any computer with
internetbrowsing capabilities and an internet connection.
• Authentication : User access to online accounts and actions will require
correctusernames and passwords for security purposes.
The dependencies are:-
• Hardware and Software Infrastructure: The system's functionality depends
on specific hardware and software components, including web servers, 
databases, and hosting environments
• Requirements and Specifications: The project development and successful 
operation rely on clear and accurate requirements and specifications, which
serve as the foundation for design and implementation.
• User Training: End users, including administrators, should receive proper 
training to understand and efficiently use the product.
• Reporting System: The system's functionality depends on having a robust 
reporting system in place to store and retrieve general reports.
• Database Access: The availability and accessibility of user data in the database 
are critical for the system's operation, especially in terms of user account 
management andorder processing.
• Data Accuracy: The system depends on accurate data entry and updates, 
particularly when it comes to tracking product information and inventory.
.
Department of Computer Science and Engineering
2.6 Requirement
Software Configuration:-
Front-End Development:
Language: HTML, CSS, JavaScript
IDE: Visual Studio Code, Sublime Text
Back-End Development:
Language: Node.js (JavaScript)
Database: PostgreSQL
Operating System: Windows, macOS, Linux
Hardware Configuration:-
Processor: A modern dual-core or higher processor, such as an Intel Core i3, AMD Ryzen, or
equivalent.
Hard Disk: Sufficient storage capacity for the operating system, web server, and project files.
Aminimum of 40GB is recommended, but actual requirements may vary based on the 
project's complexity and data storage needs.
RAM: At least 4GB or more for smooth performance. Additional RAM can 
provide better performance, especially if the website experiences heavy traffic or
uses resource-intensivetechnologies.
2.7 Data Requirement
The inputs consist of the query to the database and the output consists of the solutions
for thequery. The output also includes the user receiving the details of their accounts. In 
this project the inputs will be the queries as fired by the users like create an account, 
selecting books and putting into account. Now the output will be visible when the user
requests the server to get details of theiraccount in the form of time, date and which books
are currently in the account.
Department of Computer Science and Engineering
3. External Interface Requirement
3.1 GUI
The Ecommerce website offers an intuitive graphical interface for both customers and
administrators. Administrators have the ability to manage the system efficiently, 
including tasks like creating, updating, and viewing product details.
• Quick Reports: Users can access quick reports, like order history within specific
timeframes.
• Advanced Search: Users have access to advanced search options based on various
criteria.
• Customizable Interface: The website's user interface can be customized
byadministrators.
• Seamless Integration: All modules fit seamlessly into the graphical user
interface,adhering to established standards.
• Simplicity in Design: The design prioritizes simplicity for enhanced user experience.
• Consistent Template: Different interfaces follow a standardized template.
• User Management Integration: The user interface interacts with the user
managementmodule, including a dedicated section for login/logout functionality.
Login Interface:-
If a user is not yet registered, they have the option to enter their details and complete the
registrationprocess to create an account. Once the account is successfully created, they can
proceed to 'Login,'where they are prompted to enter their username and password. In the
event of incorrect usernameor password entry, an error message will be displayed.
Search:-
In the Ecommerce website, customers and administrators have the capability to search for
specificproducts by entering product types or titles of interest, facilitating the retrieval of
desired items.
Product Categories:-
In the Ecommerce website, the 'Categories' view displays product categories, allowing 
administratorsto add, edit, or delete categories from the list
Admin Control Panel:-
This control panel enables administrators to add or remove users, manage product listings 
(add, edit, or remove products), and oversee lending options for a seamless Ecommerce
websiteexperience..
Department of Computer Science and Engineering
4. System Features
The users of the system should be provided the surety that their account is secure. This is possible
by providing:-
• User Authentication: Secure user authentication, including validation of users using their
unique credentials (e.g., username and password).
• Administrator Monitoring: Comprehensive monitoring capabilities for administrators,
encompassing account status updates, warning notifications when users exceed predefined
limits (e.g., maximum number of products in a cart), and managing fines for late returns.
• Accountability: Strict accountability measures to protect user privacy, ensuring that users can
only access and manage their own accounts. Administrators retain access to all user accounts
for oversight and management purposes.
5. Other Non-functional Requirements
5.1 Performance Requirement
The Ecommerce website we are developing will serve as the primary performance system across
multiple branches of our organization, catering to interactions between customers, staff, and
administrators. Consequently, the database is expected to fulfill all the functional requirements
specified for our Ecommerce platform
• High Performance: The system should deliver fast and accurate performance.
• Robust Error Handling: The platform should effectively manage both expected and
unexpected errors to prevent data loss and minimize downtime. It should include built-in error
testing to detect issues like invalid credentials.
• Scalability: The system must be capable of handling large volumes of data, accommodating a
substantial number of products and users without any operational disruptions
5.2 Safety Requirement
To ensure data integrity, the system should have provisions for database backup to safeguard against
potential crashes caused by factors like viruses or operating system failures. Additionally, a reliable
power backup solution, such as UPS or an inverter, should be in place to address power supply
interruptions.
5.3 Security Requirement
• Secure Database: The system will employ a secured database.
• User Permissions: Regular users are limited to reading information, with no editing or
modification access except for their personal data.
• Role-Based Access: Different user types will have specific access constraints based on their
roles.
• Robust Authentication: Strong user authentication mechanisms will be implemented to ensure
secure access.
• Password Security: Robust measures will prevent password hacking.
• Admin Control: Separate admin and member accounts will be established, ensuring that
members cannot access the database, and only administrators have database update privileges
Department of Computer Science and Engineering
5.4 Requirement attributes
• Multiple Administrators: Multiple administrators can collaboratively make 
changes to thesystem, while regular members and users have limited modification 
rights.
• Open Source: The project will be open source, encouraging collaboration and
transparency.
• User-Friendly Database: Ensuring the database's quality for a user-friendly
experience for allplatform users.
• Easy Download and Installation: Users will have a straightforward process for
downloadingand installing the system
5.5 Business Rules
Business rules encompass the policies and practices governing the platform's operation. These 
rules enforce business policies, facilitate decision-making, and derive new insights from 
available data. Thisincludes guidelines for user conduct, project pricing, and discount offers. 
Users are expected to adhereto legal rules and protocols, with both administrators and 
members required to respect and comply with the established rules and regulations
5.6 User Requirement
In the Ecommerce website system, users are categorized as customers and administrators.
Customers are presumed to possess basic computer and internet browsing skills, while
administrators are expected to have a deeper understanding of system internals to 
troubleshoot potential issues. To facilitate seamless user interaction, the system will 
provide extensive support resources, including an intuitive user interface, a 
comprehensive user manual, online help, and installation and maintenance guides, 
ensuring that all users can utilize the system effectively without encountering challenges.
The admin provides certain facilities to the users in the form of :-
• Backup and Recovery: Ensuring data backup and recovery mechanisms are in place.
• Forgot Password: Implementing a password recovery feature.
• Data Migration: Storing user data on the server during initial registration.
• Data Replication: Enabling data redundancy to prevent loss in case of branch failures.
• Auto Recovery: Implementing automatic data saving at regular intervals.
• File Organization: Maintaining proper file organization.
• Server Maintenance: Regular server upkeep and timely updates
Department of Computer Science and Engineering
6. Other Requirements
6.1 Data and Category Requirement
Various user categories, including teaching staff, administrators, librarians, and students, have
distinctaccess rights based on their roles. Administrators possess full data management 
privileges, including modification, deletion, and appending. All other users, except librarians,
have read-only access to
database information.
Similarly, the system accommodates diverse book categories, and the relevant data associated
witheach category is displayed in a standardized format, ensuring consistency and ease of 
access
6.2 Appendix
A: Admin (Administrator), Abbreviation, Acronym,
AssumptionsB: Books, Business Rules
C: Class, Client, Conventions
D: Data Requirements,
DependenciesG: GUI (Graphical
User Interface) K: Key
L: Library,
LibrarianM:
Member
N: Non-functional
RequirementO: Operating
Environment
P: Performance, Perspective,
Purpose R: Requirement,
Requirement Attributes
S: Safety, Scope, Security, System Features
U: User, User Class and Characteristics, User Requirement
Department of Computer Science and Engineering
6.3 Glossary
The following are the list of conventions and acronyms used in this document and the project
as well:
• Administrator: A user with software user administration privileges.
• User: General user login.
• Client: Intended software users.
• SQL: Structured Query Language for database information retrieval.
• SQL Server: Server for organized data storage.
• Layer: Represents a project section.
• User Interface Layer: Direct user interaction section.
• Application Logic Layer: Web server for computations.
• Data Storage Layer: Section for data storage.
• Use Case: Broad-level project overview diagram.
• Class Diagram: Static structure diagram describing system structure.
• Interface: Communication medium.
• Unique Key: Distinguishing database entries
6.4 Class Diagram
A class is an abstract, user-defined description of a data type, specifying its attributes and allowable
operations on its instances or objects. Each data class is characterized by a name, a set of attributes
describing its properties, and a set of operations applicable to its objects. The project incorporates key
classes, interconnected with other classes essential for their functionality. Various types of class
relationships, such as normal association, aggregation, and generalization, are depicted in the diagram,
featuring role names and multiplicities. The primary classes of significance in this context are
'Librarian,' 'Member,' and 'Books,' each establishing relationships with other classe
