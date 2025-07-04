# -PENETRATION-TESTING-TOOLKIT

*COMPANY* : CODETECH IT SOLUTIONS

*NAME* : N.REEMA OPHIR GEORGE

*INTERN ID* : CT04DL106

*DOMAIN* : CYBER SECURITY

*DURATION* : 4WEEKS

*MENTOR* : NEELA SANTOSH

*DESCRIPTION* : This task involved developing a Penetration Testing Toolkit in Python to demonstrate basic security assessment techniques on web applications and networks. The toolkit integrates four main modules — a Port Scanner, Brute Force Login tester, WHOIS Lookup utility, and SQL Injection Tester — into a single menu-driven console application. The project was written and tested using Python’s IDLE (Integrated Development and Learning Environment), which provided an easy-to-use editor and interactive shell for coding and debugging. The toolkit leverages two important Python libraries: socket, which allows low-level network connections and port scanning by attempting TCP connections to common ports, and requests, which simplifies making HTTP GET and POST requests to interact with web servers and applications. The Port Scanner module takes a domain or IP address and checks whether a set of common ports (like 80, 443, 22) are open or closed by attempting to establish a connection on each port. 
The Brute Force Login tester automates dictionary attacks against web login forms by reading a list of passwords from a user-provided wordlist file and submitting each password with a given username to the specified login URL, reporting success if valid credentials are found. The WHOIS Lookup module queries domain registration details using the RDAP API (at rdap.org), sending HTTP requests and parsing the JSON response to extract registrar, status, nameservers, and registration dates.
The SQL Injection Tester module checks a user-provided URL with a vulnerable parameter by appending common SQLi payloads (such as ' OR '1'='1 or ' --) and observing whether the server’s response contains typical SQL error messages, indicating a potential vulnerability. The toolkit handles user input at each step, provides clear feedback on successes and failures, and includes error handling for network issues or invalid inputs. Using IDLE helped to develop and test each module interactively and verify their output step by step. This project effectively showcases how Python’s networking and HTTP libraries can be combined to build practical cybersecurity tools that assist in penetration testing by automating routine tasks, and demonstrates the ability to assess both web and network security systematically.

*OUTPUT*: ![Image](https://github.com/user-attachments/assets/b7c26be9-bc27-4886-bad7-41a4f687756a)
