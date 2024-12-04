# Hands-on Lab: Building and Deploying a Web App using Flask

## Overview

This lab involves creating a web application to perform basic mathematical operations (addition, subtraction, multiplication) using Flask. By completing this project, you'll learn how to develop and deploy a simple web app, connecting all the concepts from the course.

## Objectives

1. **Create Mathematical Functions**: Implement functions for addition, subtraction, and multiplication in Python.
2. **Package the Functions**: Organize the functions into a Python package for reuse.
3. **Deploy Using Flask**: Build a Flask web app to interact with the functions and deploy it to a server.

## Setup Instructions

1. **Clone the Project**:  
   Clone the repository to get started:
   ```bash
   git clone https://github.com/ibm-developer-skills-network/hjbsk-build_deploy_app_flask
   cd hjbsk-build_deploy_app_flask
2. **Create the Mathematical Functions**:
  In the Maths directory, create a mathematics.py file and add functions for summation, subtraction, and multiplication:
3. **Package the Functions:**
  - Create an __init__.py file to package the functions.
  - Import the functions into the server.py file.
4. **Implement Routes in Flask:**
In server.py, set up routes to call the appropriate functions:
 -  /sum: Adds two numbers.
 - /sub: Subtracts two numbers.
 - /mul: Multiplies two numbers.
5. **Deploy the App:**
 -  Run the app locally using Flask:

### Optional Practice
Try adding error handling to manage non-numeric input, returning helpful error messages when invalid data is submitted.

### Author(s)
1) **Shivam**
2) **Sierra Ripoche:** Developer in training for the Full Stack Software Development Specialization Certification
   
## Course Reference

This project is part of the **"Python Project for AI Application Development"** course offered by IBM on Coursera. You can learn more about the course and its modules by visiting the following link:

[Python Project for AI Application Development - Coursera](https://www.coursera.org/learn/python-project-for-ai-application-development)

## License
© IBM Corporation 2023. All rights reserved.
This notebook and its source code are released under the terms of the MIT License.
