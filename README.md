# FastAPI Rest API with MySql

## Description
Welcome to the project! This is a Blog Applicaton App made in Python and the FastAPI framework. 
It allows users to quickly and easily add, delete,  and view user Details and Blog Details. With this App, 
users can effortlessly manage the Details. hope you enjoy and we look forward to your contributions!

### Prerequisites
1. install python
2. a IDE (Depend on you)

### Running the project
1. Ensure that you are in the project home directory. Create the virtual environment by running the below command from the command prompt -
```
python -m venv .env
```
And activate virtual environment by running the below command from the command prompt
```
.env\Scripts\activate
```
and install FastAPI and requirements using
```
pip install fastapi uvicorn sqlalchemy pymysql
```
2. Run the below command from the command prompt
```
uvicorn main:app --reload
```
By default, App will run on port 5000.

Navigate to URL http://127.0.0.1:5000/ (or) http://localhost:5000

and add ==/docs== after the url or type http://127.0.0.1:5000/docs on Your Address Bar You should be able to view the homepage.

### resources
1. https://fastapi.tiangolo.com/tutorial/sql-databases/
2. https://blog.logrocket.com/server-side-rendering-with-fastapi-and-mysql/
3. https://pypi.org/

### Contributing
Pull requests are welcomed. For major changes, please open an issue first to discuss what you would like to change. Thanks!

Happy Coding!!!

### Copyright
© KAVINDU™ | 2023
