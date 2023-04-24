# e-DMS
Data management system 
The software uses Python3.0 for all purposes.
Please set up the required libraries in the Python working environment before running the program
1.	flask - web framework for the webpages
2.	mysql-connector - library for connecting to sqlite database
3.	Flask-SQLAlchemy - library to access SQL from Flask framework
4.	flask-bootstrap - library for the frontend of webpage designed with Flask
5.	pandas - library for manipulating data
6.	imgkit - library for converting document to image
After the installations, please do the following step to initiate the database in the same folder as the script "main.py"
1.	Open python command prompt and import the database schema
from main import db
2.	Initiate the database file
db.create_all()
Please check the path names of the working directory according to your operating system's preferred format if any error about path names appear. 3. Exit the Python command prompt
exit()
Please refer to this video tutorial if any doubt arises in this step https://www.youtube.com/watch?v=KrRzZGcHjK8

1.	Please go to the command prompt and run
python3 main.py
2.	See the webpage on the indicated URL. For instance, if the following message is displayed
o	Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
Go to http://127.0.0.1:5000 for seeing the webapp
3.	The login details are
Username: icu Password: Maxi9! (for user)
Username: admin Password: Maxi9! (for admin)

