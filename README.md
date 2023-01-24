# CS322: Project 1

Simon Zhao: simonz@uoregon.edu

This project is meant to help us familiarize with creating and handling a simple webpage server.

- Our goal is to learn how the existing webpages work and to implement a file checking feature. In addition, we must handle requests such as illegal characters. 
    - For example, implementing a file checking feature must check to see if any files exist in the directory `pages/`. If so, the server will transmit a `200 OK` header, including the file. If not, then it will transmit `404 Not Found` with a message explaining the problem.  
    - The webpage will also handle requests including the illegal characters `..` or `~`, resulting in a `403 forbidden error` with a message explaining the problem. 
