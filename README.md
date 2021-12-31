# Learning Management System

Updated: January 2022

## Authors
* Jay Gurjar
* Kai Wang
* Kundai Dziwa
* Ali Siddiqi

# Introduction

The learning management system is a lightweight web application which assists in student learning. 
This web application allows multiple user end points such as student, teacher and admin. Each student can enroll in multiple courses,
view class list, upload files for grading and download files uploaded by the teacher. A teacher can track the progression 
of each student in specific classes that they are teaching, view assignments and give feedback. An admin has the privilege to modify student/teacher profiles, add or remove courses to students/teachers and 
send student-teacher evaluation forms to see who is the best and worst teachers for each class.


# Installation

Steps to compile and run this application

1. Clone The Repository on your local device.
2. If your local device already has a mysql table that is named "lmsdb", drop it.
3. Source the sql file on the MySQL Command Line(make sure to include your full path in the command)
  
  For example:
  ```C:\Users\---Your path---\Learning-Management-System\database\lmsdb.sql```
  
4. Navigate back to Learning-Management-System folder and in a terminal, enter the following commands

```npm install```

```npm install file-saver```

```npm start```

5. Now we create a virtual environment in python

```python -m venv env```

```.\env\bin\activate```

```pip install flask```

6. A mysqlclient wheel file must be installed to install flask mysql connector. A wheel file which connects
Python 3.9 flask to MySQL is included in the wheel folder of this repository. If you are using a different version of python then 
you will need to download the connector from the website https://www.lfd.uci.edu/~gohlke/pythonlibs/.

```pip install C:\Users\---Your Path---\mysqlclient-1.4.6-cp39-cp39-win_amd64.whl```

7. After the wheel file is installed, you will now be able to install the actual flask MySQL connector using the command below.

```pip install flask-mysqldb```






```pip install flask-MYSQL```

```pip install --upgrade setuptools```

```pip install --only-binary :all: flask-mysqldb```


