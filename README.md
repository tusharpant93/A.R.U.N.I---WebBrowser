# A.R.U.N.I. Name Aruni in the Sanskrit, Indian origin, means 
## Dawn; 
## Rising Sun; 
## Morning; 
## One of many names of Sun God; 
## A Feminine form of the name Arun. 




   
   
   
   
   ## Web-Browser

#### Browser: A web browser is an application that allows you to access information on the Internet. Web browser helps to assist users in having an interactive online session on the World Wide Web/Internet. Example: Chrome, Firefox, etc.

#### Search Engine: It is a program that is used to locate specific websites on the Internet. It basically aids the user in obtaining knowledge about anything available on the internet.

#### Example: Google, Bing, etc.

### Browser Features:
#### Home Button: This button must-have capability to take the user directly to the home page.
#### Forward Button: This button will take the user to the next site.
#### Back Button: This button will take the user to previously visited websites.
#### Refresh Button: It will have the capability to refresh the content of the site.

### Step 1: About Libraries & Its Installtion:
#### PyQTt5: PyQt5 is one of the most popular Python modules for creating graphical user interfaces as it is very easy to use for beginners. The PyQt5 designer makes it so easy to construct complex GUI programs in a short amount of time, and it is also another wonderful feature that motivates developers to choose PyQt5.
#### PyQtWebEngine: The framework is built on the Chrome browser and allows users to embed online content in their apps. The bindings are built on top of PyQt5 and are divided into three modules that match the framework’s various libraries.

### Step 2: Importing required modules:
#### import sys: So, this command will import the sys module. The sys module contains methods and variables for modifying many aspects of the Python runtime environment. The python interpreter provides access to a number of variables, constants, functions, and methods.
#### import os: This module is imported in order to perform operations on directories, edit its contents etc.
#### QtCore: The sys module contains methods and variables for modifying many aspects of the Python runtime environment. The python interpreter provides access to a number of variables, constants, functions, and methods.
#### Qtwidgets: Qtwidgets are used to generate the user interface in Qt. and it also includes classes for constructing traditional desktop-style user interfaces but these widgets are more useful when developing large-scale applications.
#### QtWebEngineWidgets: The QtWebEngineWidgets package contains both a web browser engine and C++ classes for rendering and interacting with web content. The web content is embedded in the application using this framework.

### Step 3: Functions definition and creation of classes:
#### QMainWindow(): The user interface of an application is built using a primary window. QMainWindow and its related classes in Qt are used to handle the main window. QToolBars, QDockWidgets, a QMenuBar, and a QStatusBar can all be added to QMainWindow’s layout.
#### QWebEngineView(): The QWebEngineView class implements a widget for viewing and editing web pages. The core widget component of the Qt WebEngine web browsing module is a web view. It can be used to display live online material from the Internet in various different applications.
#### setUrl(): This is used to set the default URL of our choice.
#### setCentralWidget(): For our applications we can also use custom widgets.
#### setCentralWidget() is used to set the central widget.
#### showMaximized(): This helps to set the window size to maximum.
#### QToolBar(): This will add a toolbar and can be set to movable, immovable using setMovable(), isMovable() etc.

### Step 4: Coding for buttons and their functionalities:
#### QAction(): An icon, menu text, a shortcut, status text, and a tooltip can all be found in a QAction. Actions can be applied to menus and toolbars. SetIcon(), setText(), setIconText(), setShortut(), setStatusTip(), and setToolTip() can be used to add above actions.
#### connect(): This is used to connect the actions to the browser.
#### triggered(): Buttons are used to perform actions. These actions can only be performed if the button is functioning well. So whenever an action is required, a button is clicked and it will trigger an action. triggered() is used to trigger an action.
#### forward, back and reload, etc are the actions provided by Qt.

### Explanation:

Here, we have defined three functions navigate_home(), navigate_to_url() and update_url()
navigate_home(): This function handles the functionality of taking the user to the home page. Here we have set the home page to http://google.com using the setUrl() method.
navigate_to_url(): This function is responsible for the navigation of the URL.
update_url(): This function updates the URL to user-entered URL.
QLineEdit(): The most widely used input field is the QLineEdit object and it has a text box where you can type one line of text. The QTextEdit object is required to enter multi-line text. A line edit is used to add and edit a single line of plain text.
setApplicationName(): This takes in the name of the application that the user wants to display. The name of the app should be written in between the double or single quotations.
QLineEdit(): This is used to take the input through the keyboard from the user.

### Cheers to our code! So finally we have successfully completed our code Web Browser Using Python. We can add as many functionalities as we want. PyQt5 is a vast GUI toolkit that consists of a large set of classes, methods, etc, use them to make your browser GUI better.




