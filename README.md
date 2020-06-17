# jmeter-contacts-module

PRE REQUISITE:

- Download Jmeter ( https://jmeter.apache.org/download_jmeter.cgi )
- Java

STEPS:
- Unzip the jmeter tool
- Go to the folder:  apache-jmeter-5.1\lib\ext
- Copy the plugin library: jmeter-plugins-manager-1.3.jar
- Open the project on Jmeter tool
- If you want to change the environment change the value for "environment variable" on "User Defined Variables"
- If you want to change the version of the services change the value for "version" on "User Defined Variables"
    - For v1: left in blank the "value" field
    - For v2: write "v2" 
- If you want to create more than 1 record change the "Number of Threads (users)" in the Thread Group:"Thread Contacts Module Group"
- Click on the run button

NOTE: 
The project creates a new record and edit and deletes the same record that was created. So, not fills or damage other records that were on the database.
