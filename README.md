<h1 align="center">- - - - - 🚕TAXI-SERVICE🚕 - - - - -</h1>

# Arrive on time

``` python
    Now it is very important to be able to change your location quickly and comfortably. This need can be solved by taxi services.
But in order for these services to work productively, it is necessary to have a suitable and high-quality web service. 
A simple web application was developed in this project.
```
# Functionality of the service:
__You can do the following:__
 - Authenticate as a driver
 - Get a list of all drivers, cars and manufacturers
 - Register a new driver
 - Add a new car and manufacturer
 - Add a driver to the car
 - Get a list of your own cars
 - Log out of your account
# Project structure
![img_5.png](img_5.png)

__The project includes the following elements:__
- _controllers:_ Controllers for login/logout, displaying and adding drivers, cars and manufacturers
- _dao:_ Classes for accessing database tables
- _exceptions:_ There are custom exceptions
- _lib:_ Additional libraries are included here
- _model:_ Includes Driver, Manufacturer and Machine models
- _service:_ Provides multi-tiered architecture
- _util:_ Provides a connection to the database
- _web.filter:_ Includes existing filters


  __The webapp folder contains jsp pages__

![img_6.png](img_6.png)
# Business logic:
```python
    First, the user gets to the authentication page. 
There he must enter a login and password. Without authentication, the user can add a driver only. 
After logging in to the entire account, the user can view lists of all drivers, cars and manufacturers. 
It is possible to add these items to the database, and it is also possible to add a driver to a specific car and get
a list of the authorized driver's cars. 
Also user can return to the main menu and logout.
```
# Technologies:
- __Servlets:__ This is the basic API for Java backend development. 
It allows developers to create web servlets that can be used to process requests from clients and transmit responses.

- __JavaServer Pages (JSP):__ This is a technology that allows Java code to be embedded in HTML pages. 
JSP allows for dynamic web pages and extends the capabilities of the Servlet API.

# How to start a project
To do this, select the appropriate Tomcat configuration and click __"Run"__ or use a combination __Shift + F10__

![img_3.png](img_3.png)