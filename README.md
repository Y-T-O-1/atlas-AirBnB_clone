
# Atlas - AirBnB Clone

This is the beginning of the Atlas - Airbnb Clone. It's the foundation of re-creating Air-BnB, starting with the backend. 

<p align="center">
  <img src="https://github.com/bcart01v/atlas-AirBnB_clone/blob/main/assets/AirBNBLogo.png" alt="Atlas AirBNB logo">
</p>


## Project Description

#### AirBnB - Console

This is our AirBnB clone project. This repository contains the first step towards constructing our very own full-stack web application, which is essentially recreating the AirBnB platform. This is the first phase, known as "The Console," is a command interpreter designed to manage the core functionalities of our AirBnB application and lay the groundwork for the subsequent web development stages.
## Features


 **Command Interpreter:** To manage objects for the AirBnB clone, including:

- Creating new instances of BaseModel (e.g., new User or new Place)
- Retrieving an object from storage
- Performing operations on objects (e.g., count, compute stats)
- Updating attributes of an object
- Destroying an object

###
- **Serialization and Deserialization:** Conversion of instances into a JSON file and vice versa, enabling persistent storage of our data.
###
- **BaseModel Class:** A base class to take care of initialization, serialization, and deserialization of future instances.
###
- **User Authentication:** Basic user authentication management to create new users and manage their information.
###
- **Storage Management:** A simple file storage system to persist data between sessions, ensuring that our objects' data remains intact.


## How to Start

To start the console, simply navigate to the root directory and type 

``` ./console.py ```

### Usage

In interactive mode

``` (hbnb) help ```

#### Commands currently supported:

- ```quit``` and EOF to exit the program
- ```create``` to create a new object (e.g., create BaseModel)
- ```show``` to display an object (e.g., show BaseModel (ID)) - 
- ```destroy``` to delete an object
- ```all``` to display all objects of a class
- ```update``` to update attributes of an object

#### Non-Interactive Mode 

``` echo "help" | ./console.py ```


