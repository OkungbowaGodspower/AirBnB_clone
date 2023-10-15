# 0x00. AirBnB clone - The console

## AirBnB Clone Project - Backend and Command-Line Interface

This initial phase of the AirBnB clone project focuses on developing the backend infrastructure and integrating it with a console application using Python's cmd module. Python objects generated during user interactions are stored in a JSON file, accessible through the json module.

### Command-Line Interface

The application's interface resembles the Bash shell, but with a restricted set of commands specifically tailored for AirBnB website operations. This command-line interpreter serves as the web app's frontend, enabling users to interact with the backend built using Python's object-oriented programming principles.

Available commands include:

- `create`
- `show`
- `count`
- `update`
- `destroy`

### User Functionality

Leveraging the command-line interpreter, backend, and file storage system, users can perform various actions:

- Create new objects
- Retrieve objects from files or databases
- Perform operations on objects, such as computing statistics
- Update object attributes
- Delete objects

Sure, here's a rephrased and rearranged version of the instructions:

**Getting Started with AirBnB Clone**

This guide will assist you in setting up and using the AirBnB Clone project on your local Linux machine for development and testing purposes.

**Installation**

1. Clone the project repository from GitHub to obtain the shell program and its dependencies:

```
git clone https://github.com/OkungbowaGodspower/AirBnB_clone.git
```
2. The cloned repository contains a folder named AirBnB_clone, which houses the following files:

**Model Files**

- `models/engine/file_storage.py`: Manages serialization and deserialization of instances to and from a JSON file.

- `models/__ init __.py`: Holds a unique FileStorage instance for the application.

- `models/base_model.py`: Defines common attributes and methods shared by other classes.

**Model Classes**

- `models/user.py`: User class inheriting from BaseModel.

- `models/state.py`: State class inheriting from BaseModel.

- `models/city.py`: City class inheriting from BaseModel.

- `models/amenity.py`: Amenity class inheriting from BaseModel.

- `models/place.py`: Place class inheriting from BaseModel.

- `models/review.py`: Review class inheriting from BaseModel.

These files collectively define the data models and storage mechanisms for the application.

**Usage**

The program operates in two modes:

**Interactive Mode:**

- The console displays a prompt (hbnb) indicating readiness for user input.
- Enter a command and press Enter to execute it.
- The prompt reappears after command execution, awaiting further input.
- To exit the program, use CTRL+D, CTRL+C, or the `quit` or `EOF` command.

**Non-interactive Mode:**

- Pipe a command into the console's execution.
- No prompt appears, and no further input is expected.

**Command Input Format**

- In **Non-interactive mode**, pipe commands through `echo`.
- In **Interactive mode**, type commands directly when the prompt appears and press Enter.
