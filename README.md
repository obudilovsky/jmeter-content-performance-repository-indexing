# jmeter-content-performance-repository-indexing
Created automated full test scenarios to measurement indexing time of internal and external storages in implemented content system using JMeter

Task:
- Create automated tests to measurement indexing time of connected repositories to content portal based on the requirements:
    - Full test scenario must include the next steps: Registration of new user, Login of created user, Adding of external storage (FileNet, Microsoft Exchange, Microsoft SharePoint, Gmail, FTP(s), SMB), Set up of internal storage, Data generation in internal storage, Adding of internal storage, Checking of indexed time for all repositories.  
    - Variables must be transferred from CI system such as: Threads number, Duration, Storage parameters, keys to turn on/off separated tests.
    - User and generated document names must be unique
    - RESTfull requests transmitted over "https" 
    - Enabling MTOM for JAX-WS web services

General stack of technologies: 
- JMeter

Preconditions:
- Installed Java JDK 1.8
- Downloaded JMeter (apache-jmeter-3.2, link: http://jmeter.apache.org/download_jmeter.cgi )

Instructions:
- Run "jmeter.bat" in "\bin" directory
- Open downloaded "jmx" project
- Start tests
