# E_Gas_Booking_System
E GAS BOOKING SYSTEM




Dissertation Submitted in Partial fulfillment
of the Minor Project

Master of Computer Applications

     Semester IV
Jan - May, 2019


  Under the guidance of 					    Submitted By
  Mr. Shantilal Dawar					    Abhishek Mishra (1710903)
  Lecturer							    Manan Sharma (1710924)



 
School of Computer Science & IT
Devi Ahilya Vishwavidyalaya, Indore, M.P.
2019
 School of Computer Science & IT
Devi Ahilya Vishwavidyalaya, Indore, M.P.

DECLARATION 

We hereby declare that the project titled “E Gas Booking System” submitted by me for the partial fulfillment of  the minor project of Master of Computer Applications to School of Computer Science & IT, Devi Ahilya Vishwavidyalaya, Indore, comprises my own work and due acknowledgement has been made in text to all other material used.



Signature of Student: 
Date: 01/07/2019
Place: Indore








School of Computer Science & IT
Devi Ahilya Vishwavidyalaya, Indore, M.P.


CERTIFICATE FROM GUIDE

It is to certify that dissertation on “E Gas Booking System”, submitted by Mr. Abhishek Mishra and Mr. Manan Sharma to the School of Computer Science & IT, DAVV, Indore has been completed under my supervision and the work is carried out and presented in a manner required for its acceptance in partial fulfillment of the minor project of Master of Computer Applications.



Project Guide 
Signature:

Name: Mr. Shantilal Dawar
Date: 01/07/2019






 


School of Computer Science & IT
Devi Ahilya Vishwavidyalaya, Indore, M.P.


CERTIFICATE

It is to certify that we have examined the dissertation on E Gas Booking System submitted by Abhishek Mishra and Manan Sharma to the School of Computer Science & IT, DAVV, Indore and hereby accords our approval of it as a study carried out and presented in a manner required for its acceptance in partial fulfillment of the minor project of Master of Computer Applications.


Internal Examiner				External Examiner
Signature: 	_____________			Signature: 	______________

Name	     :	_____________			Name	     :	______________

Date	     : 	_____________			Date	     :	______________






ACKNOWLEDGEMENT

      Our study at the school of computer science has equipped us with the necessary skills and competence to face this challenging world with pride and confidence, especially this project has given us a sense of achievement.
       It is our privilege to express our sincere gratitude to our project coordinator Mr. Shantilal Dawar lecture of SCSIT, DAVV for his valuable inputs, able guidance, encouragement, wholehearted cooperation and constructive criticism throughout the duration of our project. His guidance and all hearted inspiration have been of greatest help to us in bringing out the work in its present shape. The direction, advice, discussion and constant encouragement given by him has been so helpful that it enabled us to complete the work successfully.
      Our sincere and heartfelt gratitude goes to Dr. Sanjay Tanwani, HOD of  SCSIT department for providing us the opportunity, necessary support and motivation throughout the project.
      Lastly, we express our thanks to our colleague for their cooperation in developing the project and people who have willingly helped us out with their abilities.









ABSTRACT

To ensure a simple and secure environment for the consumer as well as for the agency we have developed the “Online Gas Booking System”. Through this system, we are solving the customers as well as agency. In old system, customer need to travel to the agency and fill a form and submit the address proof and identity proof to the agency. It also helps the agency to move from a manual/excel sheet system to registering data into centralize database. It prevents any error while registering the agency. Dealer can manage the system by accessing the data about customers. It can approve the request of customer, change the status of booking of a customer. The determination of system is to provide the user with a simple and secure software which is understandable, easier to store and search the information.













CONTENT

CHAPTER1:  INTRODUCTION
                    1.1 Aim
                    1.2 Objective
                    1.3 Motivation

CHAPTER 2: SYSTEM ANALYSIS
                   2.1 Existing System 
                   2.2 Proposed System
	      2.3 Problem Statement

CHAPTER 3: PROJECT PLANNING
                 3.1 Project Goals
                 3.2 Resource Planning
                 3.3 Security planning
                3.4 Scope
                3.5 Approach
                3.6 Project Deliverables 

CHAPTER 4: SYSTEM ENVIRONMENT
                  4.1 Hardware configuration
                  4.2 Software configuration

    
CHAPTER 5: SYSTEM DESIGN
                   5.1 Table Design
                   5.2 E-R Diagram 
                   5.3 Data Flow Diagram 
                   5.4 Screen Shots

CHAPTER 6: SYSTEM IMPLEMENTATION
                6.1 JAVA Technology
               6.2 MYSQL as a Database
               6.3 Architecture Used
               6.4 HTML & CSS
  
CHAPTER 7: LIMITATIONS
   
CHAPTER 8: CONCLUSION

CHAPTER 9: BIBLIOGRAPHY




CHAPTER-1
INTRODUCTION
1.1	Aim: 
The main aim for developing this Project E Gas Booking System is to manage the details of Payments, Bookings, Connections, Delivery, Gas. It manages all the information about Payments, Customers, Gas. The project Online Gas Booking System is very helpful for customers that allows them to order gas cylinders whenever required as well as the agency’s call center can also use this software for the booking of cylinders on customers phone call.  The project is totally built at administrative end and thus only the administrator is guaranteed the access.

1.1	 Objective:
The main objectives of these projects are following:
•	This will reduce the manual work of gas agency.
•	This will reduce the long process of application for new connection registration.
•	Online cylinder booking.
•	Control the stock and booking status.
•	It can manage the customers information.

1.3 Motivation:
The spark of motivation for this project was ignite during a discussion with our guide Mr. Shantilal Dawar regarding the need of a separate E Gas Booking System, which can help to handle the cylinder booking activities at one place. The scope was clear that it could only be possible with a E Gas Booking System. Hence, we started our mission to provide our people a convenient mode.  Where all people are hoped for, but could just kept waiting for. Therefore, we planned to implement this E Gas Booking System.

CHAPTER-2
SYSTEM ANALYSIS
2.1 EXISTING SYSTEM:
	The existing system is manual based and need lot of effort and consume enough time. Hence, there is a lot of strain on the person who are managing the bookings and stock. It may lead to corruption in the booking process as well as in delivery of cylinder. We can improve the efficiency of the system, thus overcome the following drawbacks of the existing system.
•	Difficult to handle the records
•	Data redundancy
•	Repetition of the same procedure
•	Low security
•	Difficult to update data
•	Difficult to retrieve data from records
•	Difficult to handle the whole system manually
•	Data may get destroyed
•	Time consuming
 
2.2 PROPOSED SYSTEM:
	The proposed system is very easy to operate. Speed and accuracy are the main advantages of proposed system. There is no redundancy of data. Data can be easily retrieve and used at any time. The proposed system eliminates the drawbacks of the existing system largely and it provides tight security of data.
2.3 PROBLEM STAEMENT: 
The purpose of the project is to build an application program to reduce the manual work for managing the Payments, Bookings, Customers and Connections. It tracks all the details about the connections, delivery, stock, gas price.
CHAPTER-3
PROJECT PLANNING

 	Project planning is a pre-defined strategy to develop any project. Where required documentation is created to ensure successful project completion. In project planning we define what is our goal and scope of project, how can we implement, what problems may occur, how can we overcome to those problems and after developing project how it will work and how much it is suitable for an organization. There are some key points of our project listed below:

3.1 Project Goals:
The central goal of this project is to design E GAS BOOKING SYSTEM using internet, which can replace the manual paper work. Further, our focus is to provide accommodation online as well as to save the time, which require a lesser amount of maintenance. We build up system where gas cylinders can be booked in less spam of time.

3.2 Resource Planning: 
	Resource planning is a state in which we choose right source for developing a project or what skill is needed for efficient project development. Our project E Gas Booking System is developed using JAVA technology and MYSQL database.  
 
3.4 Security Planning:
Security is major phase of any administrative project planning. If the project is not secure then it will not successful. For reliability, security is must for an organization and for security, secure connection is most important it means connection between authorized peripherals and team members too. In our project, we have provided an id and password. Using   id and password only admin can login on admin module, can allot rooms to students and can manage other activities. 

3.5 Scope:
	The scope of the E Gas Booking System lies on whole city. It will provide a computerized solution for handling all the gas cylinder booking activities. This website is very user friendly and it is designed using HTML, CSS and developed using JAVA technology and MYSQL database. 

3.6 Approach:
 3.6.1 Project Development Methodology:
 We choose iterative waterfall model for this project.             
3.6.2 Introduction
The design and implementation of this project will be carried out in a completely step-by-step manner. Because project is unique undertakings, they involve a degree of uncertainty. Organization performing projects will usually divide each project into several project phases to provide better management organization. Collectively, the project life cycle serves to define the beginning and the end of a project the entire project is divided in the following phases.

Phase 1- Study and Analysis phase
In this phase, the data, facts and figures gathered by knowing problem of different user. The problems in the current system will be identified and necessary improvements will be recommended. Thus, a new system, as a solution will be proposed. The emphasis is on the way of information retrieval. The new system should provide, the required frequency and accuracy of and result.

Phase 2- Design phase
The design of a system produces the details that state how a system will meet the Requirement identified during system analysis. In this phase, the detailed specifications for the new system will be formulated. They will describe its feature- the outputs, inputs, files and database and procedures- all in a manner that meets project requirement.
After the E-R we prepared all the tables and procedure in computer storage with the help of MySQL database management system this is also called a relational database.

Phase 3- Coding and Implementation Phase
The activity following logical design, which produces program software, files and working system, will be carried out. This process will be initiated by identifying the key factors responsible for the layout for the layout of the software. The many suggestions received at previous stage are analysed and categorized. Then the solutions of these problems will be designed and developed.
In coding phase we implemented the logics from which we can access the database and can solve and problem. The physical model will cover all the physical the organization issues leading to the accrual relation that will be implemented on the system. In this phase we made a user friendly interface through which we can interact with the system.
Phase 4- Testing Phase
Testing is the process of executing with explicit intention of finding error that is, making the functioning fall. In this process, the booking of procedural details will be done. During this phase, the input, the output and external data will be tested. It checks weather the input data is correct and that the desired output is obtained or not. The entire step above will lead to an application that will suitable demonstrate the objectives already described. In the phase we will perform certain operation on each module by using the real data and observe the how much it is accurate. After finding some error we will again modify the system and again test it.

3.6.3 Summary:
It explains System Development Life Cycle as the Chosen Project Development Methodology.










CHAPTER-4
SYSTEM ENVIRONMENT
	
4.1 Software Configuration:
1.	Operating System: Windows 10
2.	Front end:  HTML, CSS
3.	Backend:  Servlet, JSP
4.	Database: My-SQL 5.5
5.	IDE: Netbeans8.2

4.2 Hardware Configuration:
1.	Processor: Intel(R)
2.	Processor speed: 250Mhz to 833MHz
3.	RAM: 512 MB
4.	Hard Disk: 40 GB








CHAPTER 5
SYSTEM DESIGN
5.1 Table design
The following are tables that are involved in the proposed system:
1.Customer_details:
  

2.Booking_details:
 

3.Price_details:
 

4.Stock_deatils:
 

5.Transaction_details:	
 




5.2 E-R Diagram:

 

  





5.3 Data Flow Diagrams: 


 
Context diagram (Level 0 DFD) for E Gas Booking System







 

Level 1 DFD for E Gas Booking System


 

 

Level 2 DFD for booking in E Gas Booking System





 
Level 2 DFD for visit and update profile


 
Level 2 DFD for checking booking status of E Gas Booking System


5.4 Screen Shots
Customer_sign_in:
 

Customer_sign_up:
 
Customer_new_connection:
 


 

Booking:
 


 

 
Profile:
 


Dealer_approval:
 
Stock_details:
 

Price_details:
 









CHAPTER - 6
SYSTEM IMPLEMENTATION

System Implementation is a process of implementing the idea that we analyze for the proposed system. The system we proposed needs a technology through which we can design and develop it efficiently. However, in order to achieve this we implemented JAVA technology to create dynamic web pages, MYSQL for database and HTTML, CSS for designing web pages.

6.1 Java Technology:
JAVA as the programming language: There are a number of different reasons for which we have chosen JAVA as the programming language for our project.
•	Java is powered by Oracle - one of the leaders in the industry. Java also gets enormous support from big technology companies like IBM, Google, Red hat, so it has been always evolving over the years.
•	There are a lot of open source libraries which you can choose for building your applications.
•	There are many superior tools and IDEs that makes your Java development easier.
•	There are many frameworks that help you build highly reliable applications quickly.
•	The community around Java technology is very big and mature, so that you can get support easily.
•	Java encourages error-free programming by being strictly typed and performing run-time checks.
•	Java programs carry with them substantial amounts of run-time type information that is used to verify and resolve accesses to objects at run time.
•	Java is a robust, reliable, portable has built in exception handling and is much more standardized and has a much richer collection of core functions than any other general-purpose computer language.
•	The core Java API is rich and includes standard packages for serial I/O, Ethernet      and internet access, security, graphics, sound, and other typical functions.
•	Java code can be checked, tested and debugged on a platform such as a PC, then moved with little or no changes to an embedded system.

6.2 MYSQL as database:
There are many reasons for choosing MYSQL as the database.
Data Security: MySQL is globally renowned for being the most secure and reliable database management system used in popular web applications like Word Press, Drupal, Joomla, Facebook and Twitter. The data security and support for transactional processing that accompany the recent version of MySQL, can greatly benefit any business especially if it is an ecommerce business that involves frequent money transfers.
Scalability and High Performance: MySQL offers unmatched scalability to facilitate the management of deeply embedded apps using a smaller footprint even in massive warehouses that stack terabytes of data. On-demand flexibility is the star feature of MySQL. This open source solution allows complete customization to ecommerce businesses with unique database server requirements.
MySQL features a distinct storage-engine framework that facilitates system administrators to configure the MySQL database server for a flawless performance. Whether it is an ecommerce website that receives a million queries every single day or a high-speed transactional processing system, MySQL is designed to meet even the most demanding applications while ensuring optimum speed, full-text indexes and unique memory caches for enhanced performance.
High Availability: With its distributed, shared-nothing architecture, MySQL Cluster has been carefully designed to deliver 99.999% availability ensuring resilience to failures and the ability to perform scheduled maintenance without downtime.


6.3 Architecture Used
Client Server Architecture:
Client/server architecture works when the client computer sends a resource or process request to the server over the network connection, which is then processed and delivered to the client. A server computer can manage several clients simultaneously, whereas one client can be connected to several servers at a time, each providing a different set of services. In its simplest form, the Internet is also based on client/server architecture where the Web server serves many simultaneous users with Web page and or website data.
Advantages:
•	All the files are stored at the same place. In this way, management of files becomes easy. Also it becomes easier to find files. As all the data is stored on server it’s easy to make a back-up of it. Also, in case of some break-down if data is lost, it can be recovered easily and efficiently. While in peer computing we have to take back-up at every workstation.
•	Changes can be made easily by just upgrading the server. Also new resources and systems can be added by making necessary changes in server.   
•	As new information is uploaded in database, each workstation need not have its own storage capacities increased (as may be the case in peer-to-peer systems). All the changes are made only in central computer on which server database exists.
Rules defining security and access rights can be defined at the time of set-up of server.

6.4 HTML and CSS:
•	 HTML (Hypertext Markup Language) is used to create the actual content of the page, such as written text, and CSS (Cascade Styling Sheets) is responsible for the design or style of the website, including the layout, visual effects and background color.


CHAPTER – 7
LIMITATIONS

The Project although fulfills all his objectives and scenario and has reached its aims, there are some limitations of the project which can be accomplished and effectuall in the future and can also be reshaped and reoriented with complete ease and effectiveness.
Some of the limitations which we encountered and came into contact with are:
•	People also cannot book cylinder without registration.
•	This system is designed only for booking gas cylinders.














CHAPTER - 8
CONCLUSION

The aim of E Gas Booking System is to cultivate the method which is utilized to automate several methods present under registering the service application by diverse users and creating it very responsible and simply permitted. This can enable finish costumers to apply for assistances without wasting their time.
•	Duplication of work is avoided.
•	Paper work is drastically diminished.
•	Fetching and access of complete details of data is trouble-free.
•	Better administration and co-ordination which leads to the improvement in efficiency of organization.















CHAPTER - 9
BIBLIOGRAPHY

10.1 Reference Books
1.	Bayross, Ivan. SQL, PL/SQL: The Programming Language of Oracle. Tech Publications Pte Limited, 2000.
2.	System Analysis and Design: EM Awad, Galgotia publications Pvt. Ltd.
3.	Database System Concepts, A. Silberschatz , H.F. Korth and S. Sudershan, 5th edition McGrawhill
4.	Menon, R. M. Expert Oracle JDBC Programming. Apress, 2006.
5.	Database Design and Implementation: A practical introduction using Oracle SQL
10.2 Websites
1.	www.tutorialspoint.com
2.	www.w3schools.com
3.	www.youtube.com
4.	www.oracle.com
5.	www.technopedia.com
6.	www.computaholics.in
7.	www.lovelycoding.org





