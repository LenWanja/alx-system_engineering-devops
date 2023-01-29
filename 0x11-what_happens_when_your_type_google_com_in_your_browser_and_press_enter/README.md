DNS request: the computer sends a request to the Domain Name System to resolve the domain name 'google.com' to an IP address. This is because computers communicate through IP addresses.
TCP/IP: once it has received the IP address, it establishes a secure Transmission Control Protocol connection with the server using the Internet Protocol. TCP/IP is a protocol governing how data is transmitted.
Firewall; it checks incoming requests against a set of rules to determine whether they should be allowed. It protects the server against malicious attacks.
HTTPS/SSL: once the connection has been established, the browser sends a request to the server to access the webpage. Google uses Hypertext Transfer Protocol Secure, an additional layer of security added to form the Secure Sockets Layer certificate. This encrypts the communication between the browser and the server to protect sensitive information.
Load balancer: once the information is received it is passed to a load balancer which will then redistribute the workload to the respective server using an algorithm. It improves the scalability, reliability, and performance of the servers.
Web Server: it receives the Get request and returns the requested web server that will then generate the HTML and CSS, images, and JavaScript.
Application Server: some requests may also be routed to an application server, which runs the backend code that powers more dynamic features of the website, such as functionality.
Database: the application server may need to obtain/ retrieve the requested information that is contained in the database.
Response: once information has been received by the web server or the application server, the response is sent back to the browser via TCP/IP protocol. The browser then renders the webpage and displays it on your screen.
This process is complex and gives a lot of protocol. It should give you a good sense of the process that takes place behind the scenes of #ALX #security #database #google
