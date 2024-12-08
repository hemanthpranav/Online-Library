# *Online-Library*
To Present a Online library system using Flask and Python

![Alt text](https://drive.google.com/file/d/1ynW_tyroJ-kgHqghsZBlERhkx7zKK7fw/view?usp=sharing)
---

### *Project Overview*

Online Library System creates an interface where an user can borrow and return books on a virtual interface. While doing so , the user can also look at the amount of titles available. Where as the admin's role of adding new titles and looking at the number of users who are currently borrowing the books This project's aim is to create a web application using tools such as Flask and python. 


### *Steps to follow*

-Upload the whole project folder either in VS CODE or CODESPACES.
-Ensure the right packages are available and installed in the required IDE
-On the terminal type *"python app.py"* 
-This will generate a URL that will take you to a web application as shown below.
![Alt text](https://drive.google.com/file/d/19q3rtdf113EYMiSzvWxtzQeEPN3meZsH/view?usp=sharing)

### *Prerequisites*

*TOOLS AND SOFTWARE*
-Python 3.8 or higher
-Pip: Python package installer
-SQLite
-IDE

*DEPENDENCIES*
- FLASK : pip install flask
- Flask-SQLAlchemy : pip install flask-sqlalchemy
- Flask-WTF : pip install flask-wtf


### *FOLDER STRUCTURE*

online-library/
│
├── instance/                  # Has the database file
│   └── library.db             #database file t
│
├── static/                    # Static files for CSS
│   ├── styles.css             # CSS file for styling 
│   ├── images/                
│       └── your_image.jpg     # Background image file
│
├── templates/                 # HTML templates
│   ├── base.html              # Base layout 
│   ├── index.html             # Home  page
│   ├── login.html             # Login page
│   ├── register.html          # Registration page
│   ├── admin_dashboard.html   # Admin dashboard
│   ├── user_dashboard.html    # User dashboard
│   ├── browse_books.html      # Page to browse books
│   ├── add_book.html          # Add book page for admin
│   ├── borrow_book.html       # Borrow book page
│   ├── return_book.html       # Return book page
│
├── venv/                      # Virtual environment 
│   ├── Include/
│   ├── Lib/
│   ├── Scripts/
│   └── pyvenv.cfg
│
├── app.py                     # Main  application file
├── forms.py                   # Flask-WTF forms for user input 
├── models.py                  # SQLAlchemy model
├── requirements.txt           # List of dependencies
├── README.md                  # Documentation for the project
└── .env                       # Environment variables 
