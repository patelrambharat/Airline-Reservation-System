# **Airline-Reservation-System**

* The project includes a UI, also known as GUI (Graphical User Interface), which consists of buttons, text fields, and other graphical elements used to interact with the user.
The GUI will be built using the Java Swing library.
* Java Swing is a library similar to Java util, which provides various features and functionality.
* Libraries are essential for utilizing the properties and functionalities they offer.
* Including the Java Swing library is necessary to use its functionality for building the project's front end.
* Java developers need to learn different libraries to leverage their functionality.
* Java Swing includes components such as JFrame, JButton, and JPanel, which will be used to build the project's front end.

# **Airline reservation system Frontend**
* Task division: Front end and back end.
* Mainframe creation: Start with the mainframe and then move to other frames.
* Features in the mainframe: Add customer, search customer, add flights, book flight, generate ticket.
* Menu bar and menu items: Hovering over menu items displays options.
* Internal frame: Different from a normal frame, related to the mainframe.
* Virtual desktop screen: Blue color region represents a virtual desktop screen.
* Internal frame and J frame: Both have similar properties, but internal frame stays within the mainframe.
* Importance of internal frame for authentication and realism.
* Creating the mainframe: Start by creating a folder named "Airline project" in Intel J.

 # **Airline reservation system Add customer and flight frontend**

* Completed main window and login window
* create add customer, add flight, and admin only window
* Start by right-clicking and selecting "JInternalFrame"
* Use JInternalFrame instead of a regular frame to keep it within the main window
* Create the add customer window using JInternalFrame
* Add a label for "Welcome to the customer panel"
* Customize the font size and make it bold
* Change the background color to blue
* Change text color to white
* Align the panel in the middle

# **Airline reservation system Admin and customer search**

* Start building the add admin internal frame.
* Required fields for admin: name, username, and password.
* Create a label for "Welcome to the admin panel" with white color and bold font.
* Set the background color of the panel to blue.
* Add labels for first name, last name, and admin ID with appropriate fonts and colors.
* Add text fields for admin ID, username, and password.
* Adjust the length of the admin ID field.
* Copy and paste the fields for username and password.

# **Airline reservation system Book ticket**
* Completed admin panel, customer add flight login, mainframe, and search customer
* Rename frame to "Book Ticket"
* Run the project and log in
* Design book ticket panel with flight search options and table
* Enter customer ID to search for specific customer
* Create ticket ID label
* Start building the panel by adding a search panel with arrival and departure options
* Customize labels and panel colors
* Include message for searching flights based on arrival and departure
* No X field present in the current section

# **Airline reservation system Designing of tables**
* Importance of data structuring and creating a database
* Introduction to MySQL Workbench
* Creating the Airline project database
* Refreshing the schema to verify the database creation
* Planning to create admin, customer, flight, and ticket tables
* Creating the customer table with nine columns: customer ID, first name, last name, passport number, national ID, address, contact number, gender, and date of birth
* Explanation of using varchar for variable character size
* Setting the size of the customer ID column as varchar(5)

# **Airline reservation system AutoID feature and DB connection**
* Database tables created: admin, customer, flight, ticket.
* GUI needs to be connected with the database.
* Different logic required for various operations with the database.
* Data needs to be stored in the database for adding customers and booking tickets.
* Bridge (driver) required to connect frontend and backend of the project.
* JDBC driver used to connect Java with MySQL for the project.
* Auto-generated customer IDs with the prefix "CS" and flight IDs with the prefix "FL" in the database.

* most important four line to set the connection with sql
   Connection con;   //Connection is a functionality called connection 
            PreparedStatement pre; //prepare some queries
            //connect with the database
            Class.forName("com.mysql.jdbc.Driver");
            con = DriverManager.getConnection("jdbc:mysql://localhost/airline_project","root","admin");

  
     

  
