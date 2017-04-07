## The challenge
---
* Create a new repo, name it by using a GUID generator
* REMOVE ALL the content in this readme, don't put any wording like "prive" or "challenge" so that other candidates cannot search your repo and copy your code.
* Do NOT fork, as other candidates would be able to see your solution easily.
* Create an application that displays information about an account.
* The code will be run on Ubuntu 14.04 for final review if needed.
* If you are using windows, find a way to code and test before submission.


## Goal
---
Create a client-server account display application with the following functional requirements:
* Server portion of the application runs in Tomcat and exposes a web service end point
* The web service end point is exposed through HTTP/SOAP
* The web service end point takes as a parameter an account ID
* The web service end point returns one Account object (see Account.java for description of account fields)
* Client portion of the application runs from command line with following parameters:
  > java clientAccountDisplay -ip 192.168.1.123 -port 80 -accountID 12345
  where ip/port is the ip/port of Tomcat, accountID is the external account ID
* client portion of the application calls the Tomcat end point, and prints the account information to the standard output.

NOTE: Server may have hard-coded list of accounts. 
NOTE: Server is not required to store and read account information from a database.

## Tools you need: a minimum list of prerequisites to install (listed in order):
---
1. install JDK, set environment variable JAVA_HOME and add to PATH
	http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
2. install Tomcat
	https://tomcat.apache.org/tomcat-7.0-doc/appdev/installation.html

Using Eclipse is optional. 


## Things that will get our attention:
---
1. How quickly you learn Web Service SOAP APIs and get the challenge done
2. How easy it is for someone else to understand the code you wrote and easily extend the functionality
3. Does your code compile, does it do the job as expected, is it bug-free, how does it handle exceptional situations?
