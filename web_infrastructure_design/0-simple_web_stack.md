#  0-simple_web_stack

![alt text](<0-simple_web_stack.png>)

-   **What is a server**


Serves can be physical or virtual, running an operating system, and housed in DataCenter 


-   **What is the role of the domain name**

The role of the domain name is to replace complex IP addresses numbers into easily understandable names so humans can remember and communicate them in a better way.

-   **What type of DNS record www is in** [**www.foobar.com**](http://www.foobar.com/)

DNS record of www belongs to a subdomain of the  [www.foobar.com](http://www.foobar.com/)

-   **What is the role of the web server**

Web servers are what make Web hosting possible, that is, the possibility of renting a space on a server to store the files of our site.

-   **What is the role of the application server**

The application server is the intermediary between browser-based databases and back-end databases and legacy systems. In many uses, the application server combines or works with a web server (Hypertext Transfer Protocol) and is called a web application server.

-   **What is the role of the database**

The role of the database is to make the information gathered organized so it can be easily accessed, managed and updated. However, not all database management systems work the same, and the mechanisms they use to organize data can vary, ranging from relational database to object-oriented database, distributed database or cloud database. Next, some of its main differences:

-   **-   What is the server using to communicate with the computer of the user requesting the website**

The web server typically employs the HTTP protocol (or HTTPS for secure communication) to communicate with the user's computer requesting the website. HTTP is the standard protocol for data transfer on the web, enabling the web server to respond to requests from users' web browsers and provide the requested files.


## Issues with the simple web infrastructure

-   One of the issues of having a simple web infrastructure, has to do with the SPOF (Single Point of Failure) where if component of the system fails, there is no backup that can support the continuity of the functionality of the system, bringing the whole system to a collapse by being unable to operate.

-   Also, whenever some structure or node in the system needs to be repaired, the whole system has to be shut down, while the maintenance is done. Then, client requests cannot be attended during this period of time.

-   Overload of traffic can be a risk to the server capacity. This, because there is no possibility to scale the service with additional servers as backup. Leading to a possible breakdown of the web page and client requests, as traffic surpasess servers capacity.


