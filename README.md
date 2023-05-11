# Furniture Inventory Website

This is a furniture inventory website built using Flask, HTML, and CSS.

## Features

- Display a list of furniture items with their details such as name, description, price, and quantity.
- Add new furniture items to the inventory.
- Edit existing furniture item details.
- Delete furniture items from the inventory.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ankit-Ransh/Test-2.git/

2. Navigate to the project directory:
   ```bash
   cd Test-2

3. Create a virtual environment:
   ```bash
   python3 -m venv venv
   
4. Activate the virtual environment:

   ```bash
   source venv/bin/activate
   
5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   
6. Run the application:
   ```bash
   python app.py
   
 7. Open your web browser and visit http://localhost:5000 to access the furniture inventory website.
 
 
## Dependencies
The following dependencies are used in this project:

1. Flask: A micro web framework for Python.
2. SQLAlchemy: A Python SQL toolkit and Object-Relational Mapping (ORM) library.
3. Bootstrap: A popular CSS framework for building responsive websites.

## Add the command
The following command should be executed in the python terminal to create the instance.
1. from app import app,db
2. app.app_context().push()
3. db.create_all()

   Delete any existing pycache and instance directory if exists. Then run the command.
   
## Update the path
Update the path in data_man.py 

1. Replace cnx = sqlite3.connect('/Users/ankitanand/Desktop/Test 2/instance/db.sqlite3') with your db.sqlite3 path
<img width="661" alt="Screenshot 2023-05-11 at 7 00 11 PM" src="https://github.com/Ankit-Ransh/Test-2/assets/98517507/4599b4a5-6851-4150-8a0e-1cb05c8567a6">
<img width="759" alt="Screenshot 2023-05-11 at 7 00 17 PM" src="https://github.com/Ankit-Ransh/Test-2/assets/98517507/092bc086-f7bf-4297-a693-32f52806005c">


## Usage
1. Upon accessing the website, you will see a list of furniture items in the inventory.
2. To add a new furniture item, click on the "Add Furniture" button and fill out the form.
3. To edit an existing furniture item, click on the "Edit" button next to the item and modify the details in the form.
4. To delete a furniture item, click on the "Delete" button next to the item.
5. You can search for specific furniture items using the search bar at the top of the page.

## Contributing
Contributions to this project are welcome! If you find any issues or would like to suggest new features, please open an issue or submit a pull request.

## Demo

 ![Screenshot (40)](https://github.com/Ankit-Ransh/Test-2/assets/101007097/3c130fb3-5570-4789-ae4d-521e4a4fa457)
![Screenshot (41)](https://github.com/Ankit-Ransh/Test-2/assets/101007097/ccf91d81-b630-4b03-9642-1e97f8fba7ab)
![Screenshot (42)](https://github.com/Ankit-Ransh/Test-2/assets/101007097/20ea0a30-836f-4d9a-9d6c-c6642be6ddd9)
![Screenshot (39)](https://github.com/Ankit-Ransh/Test-2/assets/101007097/583c74ce-704f-4dec-a15d-d1b73c1d3444)

   
