# AirBnB Clone Project
This project is a part of the AirBnB clone project, aimed at building a web application similar to AirBnB. 
![image](web_static/images/hbnb_logo.png)

This stage implements a backend interface, or console, to manage program data. The console commands allow users to create, update, destroy objects, and manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

## Technologies
* All databases are executed with `MySQL 8.0` version `5.7.8-rc`
* All files were executed with `MySQLdb` version `2.0.x`
* All files were executed with `SQLAlchemy` version `1.4.x` 
* All Python Scripts are written with `python3` version `3.8.5`
* All files are interpreted/compiled on Ubuntu 20.04 LTS

## Command Interpreter
The command interpreter allows users to perform various operations on AirBnB objects. These operations include:
- Creating new objects (e.g., User, Place)
- Retrieving objects from files or databases
- Performing operations on objects (e.g., counting, computing stats)
- Updating attributes of objects
- Deleting objects
- How to Start the Command Interpreter

## To start the command interpreter, follow these steps:
1. Clone the repository from GitHub: [AirBnB_clone](https://github.com/Zecharii/AirBnB_clone.git)
```
$ git clone https://github.com/Zecharii/AirBnB_clone.git
```
2. Navigate to the project directory in your terminal.
3. Run the command interpreter script.
```
python3 console.py
```

## How to Use the Command Interpreter
Once the command interpreter is running, you can enter commands to interact with AirBnB objects. The general syntax of commands is as follows:

```
(command) (options)
```
Here are some example commands:
- `create User`: Create a new User object.
- `show Place`: Display details of a Place object.
- `all`: Show all objects currently loaded.
- `update User 12345 name "John Doe"`: Update the name attribute of the User object with ID 12345 to "John Doe".

## Examples
Here are a few examples of how to use the command interpreter:

```
$ python3 console.py
(hbnb) create User
f27798a2-2927-4f35-ae8f-7d30d36bc2e0
(hbnb) show User f27798a2-2927-4f35-ae8f-7d30d36bc2e0
[User] (f27798a2-2927-4f35-ae8f-7d30d36bc2e0) {'id': 'f27798a2-2927-4f35-ae8f-7d30d36bc2e0', 'created_at': '2022-02-06T10:00:00', 'updated_at': '2022-02-06T10:00:00'}
(hbnb) all
["[User] (f27798a2-2927-4f35-ae8f-7d30d36bc2e0) {'id': 'f27798a2-2927-4f35-ae8f-7d30d36bc2e0', 'created_at': '2022-02-06T10:00:00', 'updated_at': '2022-02-06T10:00:00'}"]
(hbnb) update User f27798a2-2927-4f35-ae8f-7d30d36bc2e0 name "John Doe"
(hbnb) show User f27798a2-2927-4f35-ae8f-7d30d36bc2e0
[User] (f27798a2-2927-4f35-ae8f-7d30d36bc2e0) {'id': 'f27798a2-2927-4f35-ae8f-7d30d36bc2e0', 'created_at': '2022-02-06T10:00:00', 'updated_at': '2022-02-06T10:01:00', 'name': 'John Doe'}
```

## Forking
The `AirBnB_clone` repo was forked from 
* Justin Majetich - @justinmajetich <justinmajetich@gmail.com>

## Authors
This part of the project is implemented by 
* Zechariah Gaiya - @Zecharii <abbazechariah@gmail.com>
Please refer to the AUTHORS file for a complete list of contributors.
---
