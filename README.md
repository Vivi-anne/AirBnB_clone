# AirBnB clone - The console
![airbnb](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230514%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230514T214125Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=12e9c4b746d0d9bc8e469ef8bacadfcee50ffe5edf0b13ccbe034546f568f9b8)

## Project Description
This is the first part of the AirBnB clone project. 
The HolbertonBnB is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB.

## Console💻
The console is a command line interpreter that permits management of the backend of hbnb. It can be used to handle and manipulate all classes utilized by the application (achieved by calls on the `storage` object defined below).

## Using the console
It can work in two different modes:

**Interactive** and **Non-interactive**.
To run the console in non-interactive mode, pipe any command(s) into an execution file `console.py` at the commandd line.

```
$ echo "help" | ./console.py
(hbnb)
Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(hbnb)
$
```
Alternatively, to use the HolbertonBnB console in interactive mode, run the file console.py by itself:
```
$ ./console.py
```
While running in interactive mode, the console displays a prompt for input:
```
$ ./console.py
(hbnb)
```
To quit the console, enter the command `quit`, or input an EOF signal (`ctrl-D`).
```
$ ./console.py
(hbnb) quit
$
```
```
$ ./console.py
(hbnb) EOF
$
```

## Storage🛄
Classes are handled by the abstracted storage engine defined in the `FileStorage class`.

Every time the backend is initialized, HolbertonBnB instantiates an instance of `FileStorage` called `storage`. The storage object is loaded/re-loaded from any class instances stored in the JSON file `file.json`. As class instances are created, updated, or deleted, the `storage` object is used to register corresponding changes in the `file.json`.

## Testing
Unittests for the HolbertonBnB project are defined in the tests folder. To run the entire test suite simultaneously, execute the following command:
```
$ python3 unittest -m discover tests
```
Alternatively, you can specify a single test file to run at a time:
```
$ python3 unittest -m tests/test_console.py
```

## Authors
- [Nyakundi Vivianne](https://github.com/Vivi-anne/AirBnB_clone.git)
- [Clinton Aloo](https://github.com/ClintonAloo)

