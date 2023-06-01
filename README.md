# Socket_C_language

### Description:

This project aims to develop an authentication and authorization system using a socket server. The system allows a client to connect to the server by providing a username and password. If the password is incorrect, the client can retry up to three times. After three unsuccessful attempts, the system will temporarily shut down.

Once the password is correct, the server retrieves the user's profile from a text file containing the stored credentials on the server side. The profile can be either "Admin" or "Guest".

Depending on the user's profile type, certain functionalities will be available. The details of these functionalities and their implementation can be found in the PDF file titled "mini_project_C".

### Project Objectives:

Implement a socket server to allow client connections.
Establish an authentication system by requesting a username and password from the client.
Limit the number of incorrect password attempts to three before temporarily blocking the system.
Retrieve the user's profile from a text file containing the credentials.
Grant access to specific functionalities based on the user's profile type (Admin or Guest).

### Technologies Used:

Programming Language: C
Socket Programming: Utilize sockets for client-server communication.
File Handling: Read and write credential information from a text file.
