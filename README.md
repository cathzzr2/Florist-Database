# Anatta Flowers Shop Database System

A comprehensive database management system designed to streamline operations for Anatta Flowers Shop in Oakville, Canada.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation and Setup](#installation-and-setup)
- [Features](#features)
- [Project Structure](#project-structure)
- [Contribution](#contribution)
- [License](#license)
- [Commercial Use](#commercial-use)
- [Acknowledgements](#acknowledgements)

## Introduction

This project was initiated to modernize and enhance the operations of Anatta Flowers Shop. With a focus on improving customer experience, inventory management, and automating supply replenishment, this system has significantly boosted the shop's operational efficiency.

## Requirements

For more information about the technical requirements of running this project on your local computer, please refer to [here] (REQUIREMENTS.md).


## Installation and Setup

1. Clone the repository:

```
git clone https://github.com/crown-of-napoleon/Florist-Database.git
```

2. Navigate to the project directory and install the required dependencies:
```
pip install -r requirements.txt
```

3. Run the Flask application:
```
flask run
```

## Features

- **Relational Database**: Built on MySQL, ensuring structured and efficient data storage.
- **Web Interface**: User-friendly interface developed with Python and Flask.
- **Dynamic Content**: AJAX calls integrated for real-time content updates, enhancing responsiveness.
- **User Authentication**: Secure login system using Flask’s session object.
- **Inventory Management**: Automated processes for tracking and replenishing stock.

## Project Structure

### Files:
- `InventoryApp.py`: Application file related to inventory management.
- `SalesApp.py`: Application file related to sales management.
- `CustomerApp.py`: Application file related to customer management.
- `EmployeeApp.py`: Application file related to employee management.
- `initializeSchema.sql`: SQL script to initialize the database schema.
- `REQUIREMENTS.md`: File detailing the requirements for the project.
- `LICENSE`: License file for the project.
- `CONTRIBUTING.md`: Guidelines for contributing to the project.
- `COMMERCIAL.md`: Information related to commercial aspects of the project.
- `.gitignore`: File specifying which files and directories to ignore in Git.
- `README.md`: Documentation for the project.

### Folders:
- `src/`: Javascript files for the webstie.
- `static/`: Directory for static files like CSS.
- `templates/`: Directory for HTML templates.
- `testing/`: Unit and integration testing for the code.

## Contribution

Contributions are welcome! Please read the contribution guidelines before submitting pull requests.

[Contribution guidelines for this project](CONTRIBUTING.md)

## License
This project is licensed under the MIT License. The full details of the license can be seen [here](LICENSE).

## Commercial Use

Commercial use of this project is allowed subject to certain specified circumstances, restrictions, and exceptions. see [here](COMMERCIAL.md) for more details.

## Acknowledgements

- Anatta Flowers Shop for their collaboration and feedback.
- Oakville Trafalgar High School's Computer Science Department for their recognition and support.
- All contributors and testers who helped in refining this system.

