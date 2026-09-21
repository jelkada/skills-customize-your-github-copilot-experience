# 📘 Assignment: Python File I/O and JSON

## 🎯 Objective

Learn how to read from and write to files in Python, and how to store structured data using JSON so programs can save and reload information.

## 📝 Tasks

### 🛠️ Read and Display Data from a File

#### Description

Create a Python program that opens a text file and reads its contents, then prints each line in a readable format.

#### Requirements

Completed program should:

- Open a text file using Python file I/O.
- Read the file contents line by line or as a full string.
- Print the data to the console in a clear format.
- Handle the case where the file does not exist gracefully.

### 🛠️ Save User Input to a File

#### Description

Build a small script that collects user input and stores it in a file so the information can be saved for later use.

#### Requirements

Completed program should:

- Prompt the user for at least three pieces of information.
- Write the input to a text file in a structured format.
- Save the file in the same directory as the program or a clearly defined output path.
- Confirm to the user that the data has been saved successfully.

### 🛠️ Work with JSON Data

#### Description

Use Python's `json` module to store and load structured data such as a list of students or a small inventory.

#### Requirements

Completed program should:

- Create a Python dictionary or list of data.
- Convert the data to JSON using `json.dumps()`.
- Write the JSON data to a `.json` file.
- Read the JSON file back and print the loaded data.
- Demonstrate that the structure is preserved after reloading.

### 🛠️ Build a Small Persistent App

#### Description

Create a mini application that keeps data between runs by saving it to a JSON file and loading it again when the program starts.

#### Requirements

Completed program should:

- Load existing data from a JSON file if it exists.
- Allow the user to add new data entries.
- Save the updated data back to the JSON file.
- Show the stored data after the program exits and runs again.
- Include a brief explanation of how the app uses file persistence.
