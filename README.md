# taxi-service

**What this application is for and what it can do**
Primitive demonstration program of services for the transport enterprise

**Technologies used**
Program based on the use of:
- WebApp architecture technology
- Java / Jackarta Server Pages
- MySQL database system
- Apache Tomcat - open source web server
- Client Authentication process

**How to run a project**
Before lunching the programm you need to install on you comp: 
MySQL Workbench (DB for datas working) and Apache Tomcat (to lunch the programm)

To lunch the project you need to copy program **taxi-service-1.0-SNAPSHOT.war** from this server
and place it in /webapps Tomcat-programm`s on your comp.
Lunch **/bin/startup.bat** Tomcat-programm/
In brouser you can see authentication data to start of the program.
To log in to the database you can use "registration" or "login" - "password"
(For example, you can input user: bob, password: 1111)
In registration data, for simplification, You can enter any username and password.
After authentication or registration you can see panel for working with DB.
So the program allows:
1.1 View a list of all drivers, delete (Display All Drivers)
    and add new ones (Create new Driver)
1.2 View a list of all cars removed (Display All Cars)
    and add new ones (Create new Car)
1.3 View a list of all car manufacturers, remove (Display All Manufacturers)
    and add new ones (Create new Manufacturer)
1.4 Attach the driver to a specific car (Add Driver to Car)
1.5 Show the authenticated driver a list of "his" cars (Get My Current Cars)

Exit from the program: logout
