# ECE-461L-Project-Team-Team-Name
## Overview
In this project, the team implemented a Proof of Concept (PoC) for a web application, which functioned as a Hardware-as-a-Service (HaaS) system. In this Haas Application users are able to create encrypted accounts, log into encrypted accounts, or logout of encrypted accounts. Users can also create, join or leave projects, and check-in or check-out hardware resources for the projects.

## Prerequisites
Users should have these following programs to run the application on their own local machine
- Python (https://www.python.org/downloads/)
- Node.js (https://nodejs.org/en/)

### Setting Up the Frontend
- npm install
- npm run build

### Setting Up the Backend
- python -m venv venv 
- source venv/Scripts/activate
- pip install -r requirements.txt --user
- python .\backend.py

## Program Software
- Backend: Python Flask
- Frontend: React.js
- Database: MongoDB

## Testing
We used two types of testing when testing the application for the frontend we used manual testing and for the backend we used unit testing.

### Frontend Testing
We achieved the testing for the frontend by running through the application. Each button was tested and the database was checked for any changes to the data.

### Backend Testing
We achieved this by using Pytest and calling each of the python flask functions to check if each function was doing its job.

## Authors
- Gavin Nguyen
- Caleb Domingue
- David Johns
- Leon Shaji
- Elizabeth Kroger
