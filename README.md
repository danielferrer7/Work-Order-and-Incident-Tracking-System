# Work-Order-and-Incident-Tracking-System

<br />
<p align="center">  
<br />
Dashboard:  <br/>
<img src="https://imgur.com/6tryqXk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  <br />
  <br />
<br />
<br />
<p align="center">  
<br />
New Work Order:  <br/>
<img src="https://imgur.com/6D5K38f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  <br />
  <br />
<br />

<h2>Description</h2>
This project is a web-based application built with Flask and SQLite. It allows users to create, view, and manage work orders efficiently. The system features a streamlined interface for adding work orders, viewing a detailed table of tasks, and deleting completed or irrelevant entries. It is designed for simplicity, extensibility, and ease of use, making it ideal for small teams or organizations.



<h2>Languages and Utilities Used</h2>


- **Flask**: Python web framework for developing the web application.
- **SQLite**: Database for storing work order information.
- **Bootstrap**: Open-source front-end framework for creating the web interface.
- **SQLAlchemy**: ORM for database interaction.




<h2>How They Worked Together</h2>

1. Flask managed the application’s structure, routing, and template rendering.
2. SQLite provided a simple, persistent database for storing work orders.
3. SQLAlchemy abstracted database operations, allowing Python code to manipulate SQLite data easily.
4. Bootstrap (if used) enhanced the front-end design, making the interface responsive and professional.





<h3>Step 1: Set Up Your Project Folder</h3>

1. Create a new folder called WorkOrderSystem.
2. Inside this folder:
  - Create a Python file: work_order.py.
  - Create a subfolder named templates.



<h3>Step 2: Install Required Libraries</h3>

1. Open Command Prompt.
2. Navigate to the project folder:
      bash

      >cd path\to\WorkOrderSystem

3. Install Flask and SQLAlchemy:
    bash

    >pip install flask flask-sqlalchemy



<h3>Step 3: Write the Python Code</h3>
<br />
<p align="center">  
<br />
Open work_order.py and paste the Python code:  <br/>
<img src="https://imgur.com/uIu2AMh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  <br />
  <br />
<br />

<h3>Step 4: Create the HTML Templates</h3>
1. index.html (Main Page)
<br />
<p align="center">  
<br />
In the templates folder, create a file named index.html and add the HTML code:  <br/>
<img src="https://imgur.com/M8aqDyP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  <br />
  <br />
<br />
  
2. add.html (Add Work Order Page)

<br />
<p align="center">  
<br />
In the templates folder, create a file named add.html and add the following code:  <br/>
<img src="https://imgur.com/tXWVPph.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  <br />
  <br />
<br />
  
<h3>Step 5: Run the Application</h3>

1. Open Command Prompt.
2. Navigate to the project folder:
    bash

    >cd path\to\WorkOrderSystem

3. Run the Flask app:
    bash

    >python work_order.py


<h3>Step 6: Test the Application</h3>
1. Open your browser and visit:


    >http://127.0.0.1:5000/

2. Use the Add New Work Order button to add work orders.
3. Use the Delete button to remove work orders.

<h2>Features Recap</h2>

- **Main Page (index.html)**: Displays all work orders in a styled, responsive table.
- **Add Work Order Page (add.html)**: A form to create new work orders.
- **Delete Functionality**: Allows users to remove work orders.
