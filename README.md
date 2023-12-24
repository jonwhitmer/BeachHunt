```markdown
# Beach Hunt

## Description
Beach Hunt is a command-line application developed in C++ that simulates the experience of hunting for various items on a beach. The program utilizes object-oriented programming principles, featuring a parent class named `Item` and four child classes: `Shell`, `Wood`, `Glass`, and `Plant`.

## Authors
- Jon Whitmer
- Justin Schaeffer
- Ben Luzier

## Year of Creation
2022

## Usage
To start the program, compile the source files and run the generated executable. Once the program starts, follow the on-screen prompts to:

1. Collect Items: Add new items to your collection by providing their details.
2. Search Items: Search through the collected items based on specific attributes.
3. End Program: Exit the program and display the final collection data.

## Features
- Interactive command-line interface for easy navigation.
- Functions for adding items to and searching within the collection.
- Display of the final inventory of collected items.

## How to Compile
To compile the program, you need a C++ compiler like `g++`. Navigate to the directory containing the source files and run the following command:

```bash
g++ -o BeachHunt main.cpp item.cpp glass.cpp shell.cpp wood.cpp plant.cpp
```

Replace `main.cpp` with the name of your main source file if it's different.

## Running the Application
After compilation, you can run the program by executing the `BeachHunt` file in the command line:

```bash
./BeachHunt
```

## License
This project is licensed under custom terms that allow you to view and run the software, but not to modify, distribute, or use it for commercial purposes. For the full license, see the `LICENSE` file.

## Disclaimer
This is a student project and is intended for educational purposes only. The authors are not responsible for any misuse or damages caused by the software.

## Acknowledgments
We would like to thank everyone who contributed to the development and testing of this application.

```
