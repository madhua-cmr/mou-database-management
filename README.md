# mou-database-management
PROBLEM STATEMENT: 

Create a system to efficiently organize and maintain a database of Memorandums of Understanding (MOUs). This system should allow users to easily input, update, search, and retrieve MOU information. It should also ensure data security and integrity, with permissions set to control access. The goal is to streamline the management of MOUs, making it simpler for users to find and reference relevant documents while ensuring confidentiality and accuracy.
PROJECT-FLOW: 
Purpose: 
A Memorandum of Understanding (MOU) is a legal bond that connects two or more parties where each party binds itself to do the agreed upon. The use of technology in processing an MOU is able to provide information in the form of accuracy in information about the course of a cooperation process. In addition, the security of the data from this process is guaranteed. Therefore, the process of MOU negotiations, data storage of MOU, and reports on the MOU process can be more effective if done with computers
Scope: 
The system development is carried out by exchanging data online using a mobile application integrated with the existing MOU system. The Agreement may be between a Company and college  or NGO and college or MNC and college . The partners will be directed to have a mobile application that functions to exchange data. Then the entire negotiation process regarding the contents of the MOU will be carried out online until an agreement between the two parties is reached. 


2. System Overview:
2.1. Users:
1. General Users:

They can only view the moc’s and can view the moc in detail ,They cannot edit or delete or add new MOC’s,They can search the moc based on the purpose of the moc and also filter the moc from the list based on dates and more specifications.

2. Admins:

Admins can give the user access and also give the edit ,delete,add, view access based on the user’s role, admins only can assign the role to the users,and also admin can edit ,delete,view, add moc.they can also renew the moc’s.

2.2. Features:

1. Login and registration:

Users can register for an account or login with their existing
Account and view the mou’s list.

2.User’s role assignment:

              Admin can assign the role of the user and they can also give access for view,edit,delete and add mou’s based on their role . 

3.Download and Print:
             Users can view the detailed view of mou’s and also they can download and print the mou’s document using download and print options.



4. Filtration and Sorting:
                  Based on the date we can sort the mou’s list and also renew mou and  filter mou’s based on categories and parties.

5. Admin Access:

        Admin can view all the users and update the user ,add ,delete,edit the user.
They can assign the role of the user ,they can add, edit,delete and view mou’s.

6. Admin’s Analytical Dashboard:

       Admin can view the number of mou’s by category, no of users and also see the latest mou’s.


 Functional Requirements :


Data Management: Create, read, update, and delete (CRUD) operations for MOU documents.
Search Functionality: Implement robust search capabilities for easy retrieval of documents based on various criteria (e.g., date, keywords, parties involved).
Version Control: Maintain a history of document revisions and ensure users can access previous versions when needed.
Access Control: Define user roles and permissions to control who can view, edit, and delete documents.
Notification System: Implement alerts for upcoming document expirations or revisions.
Reporting: Generate reports on document status, usage statistics, and other relevant metrics.



            

                Non-Functional Requirements:

Performance: Ensure the system can handle concurrent users and large volumes of data efficiently.
Scalability: Design the system to accommodate future growth in data and user base.
Security: Implement measures to protect sensitive information, including encryption, user authentication, and authorization controls.
Reliability: Minimize downtime and data loss through backup and disaster recovery procedures.
Usability: Design an intuitive user interface with features like document previews, filtering options, and user-friendly navigation.
              


    
