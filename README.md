# Azure MySQL Data Visualization

This project demonstrates how to set up a simple data visualization application using Streamlit, Flask, and Azure services. The project consists of two main components:

- **Backend:** A Flask API that connects to an Azure MySQL database and provides endpoints to fetch degree and timestamp data.

- **Frontend:** A Streamlit app that visualizes the data obtained from the Flask API.

## Project Structure

The project is organized into two folders:

- **backend:** Contains the Flask API code and Docker configuration.
- **frontend:** Contains the Streamlit app code and Docker configuration.

## Setup Instructions

### Backend Setup

1. Navigate to the `backend` directory.

2. Build the Docker image:
   ```bash
   docker build -t backend-image .

# DATABASE SET UP IF YOU WANT TO USE ON YOUR AZURE :

1.Create your MySQL database on Azure Portal 
2.Place yourself in backend folder : 
cd /Backend
3.Run the command to create database and tables:
python database.py

----------------------------

# Run the Docker container:

docker compose up --build

### For the report of this TP please view Azure TP.pdf 