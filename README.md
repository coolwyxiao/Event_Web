# Event_Web
**Link to the website: http://ec2-18-220-195-142.us-east-2.compute.amazonaws.com:8080/Jupiter3/#**
## Develop an event searching and recommending website
### Project Description
This web is divided into 3 parts: search, favorite, recommendation
* "search" can show events based on users' current location
* "favorite" stores users' favorite things here
* "recommendation" used content-based algorithm to recommend relevant events to users based on their locations and favorites

### Package Division
**FrontEnd:** under WebContent directory
* index.html functions as the framework of the frontend page
* main.css under style directory defines the style of the HTML page.
* main.js contains the code of javascript that connects backend with frontend.

**BackEnd:** under src directory
* algorithm: This is the package to implement my event recommendation algorithm.
* db: This stores the java class used for mySql communication purposes.
* entity: This is the place to store code for item class, which wraps the data obtained from API and can be directly used by any other components in the project.
* external: This is basically some helper function provided by the API website
* rpc: this is the servlet I wrote down for different purposes. Including searching, recommendation, and helper function.

### Configuration
* Eclipse Oxygen
* Java EE
* Tomcat v9.0
