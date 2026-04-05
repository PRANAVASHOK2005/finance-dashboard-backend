Title: Finance Dashboard Back-End API
  * Project Overview
     This project aims to create a back-end for the finance dashboard application, which will allow users to interact with financial information according to their roles.
      The project is developed keeping in mind simplicity and efficiency of the system, as well as clean API architecture.
  * Objectives
     The goal of this project is to develop RESTful APIs for managing financial data efficiently and ensuring access control through role-based access control (RBAC).
     The system also offers summary-level analysis that helps create visualizations and insights on a dashboard.
     However, the system is designed to have a simple and modular backend architecture. This system focuses on proper data validation, error handling, and separation of concerns within the design and implementation of APIs.
     Moreover, this project sets up a solid foundation that may be scaled further by incorporating a database and authentication, among other features.
 * Tech Stack
     Language: Python
     Framework: FastAPI
     Server: Uvicorn
     Testing Interface: Swagger UI (/docs)
     Public Access: Ngrok
     Storage: In-memory (Python lists)
 *System Architecture
   User Roles & Access
   The system utilizes a role-based access control (RBAC) mechanism in which users are assigned roles that determine their permission levels as follows:
     Administrator: Full rights to generate and manage financial data.
     Analyst: Ability to read financial data and get analytical summaries.
     Reader: Limited read access to financial data.
     This approach ensures robust security and separation of duties.
 * Running the Project
   1. Dependencies Installation
    pip install fastapi uvicorn pyngrok
   2. Launching the FastAPI project
    Launch your `main.py` file to start the backend server
   3. ngrok tunnel launch
    Create a tunnel through ngrok for your local server at port 8000
   4. Swagger UI Access
    Visit the URL below in your web browser:
    https://<ngrok-url>/docs
    This can be used to test all API endpoints
 
