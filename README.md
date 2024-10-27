# Microkernel Text Editor (Modular Architecture)

## Overview
This project demonstrates the **Microkernel Architectural Pattern** using a modular text editor. The core system provides basic text editing functionality, while additional features (such as spell-check and word count) are implemented as plug-ins.

## Project Structure
The project is divided into two parts:
- **Front-End (React)**: Manages the UI for the text editor and plug-ins.
- **Back-End (Spring Boot)**: Handles file management and plug-in services (e.g., spell-checking, word count).

### Folder Structure:


## Features
- **Core Features**: Basic text editing and file saving/loading.
- **Plug-ins**: Extend the text editor with features like spell-check and word count.

## Setup Instructions
1. **Clone the repository**: 


2. **Run the Front-End (React)**:
- Navigate to the `frontend` folder and run:
  ```
  npm install
  npm start
  ```

3. **Run the Back-End (Spring Boot)**:
- Navigate to the `backend` folder and run App.java

4. **Open the Application**:
Open your browser and visit `http://localhost:3000` to see the editor in action.
