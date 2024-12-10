
# Flask Application

This project is a Flask-based web application designed to manage and display course timetables. 
It allows users to view courses filtered by levels and includes features like Docker containerization.

## Project Structure

- `app.py`: The main Flask application file.
- `templates/index.html`: The HTML template for the web interface.
- `.env` and `.env.example`: Environment variable configuration files.
- `requirements.txt`: Python dependencies for the project.
- `Dockerfile`: Instructions to build a Docker image for the application.

## Steps Followed During Development

1. **Setup Flask Environment**:
   - Installed Flask and configured the basic application structure.
   - Created routes and HTML templates for the user interface.

2. **Database Integration**:
   - Configured PostgreSQL as the database backend.
   - Used environment variables to store database credentials securely.

3. **Environment Setup**:
   - Added `.env` and `.env.example` files to manage sensitive configuration data.
   - Included a `.gitignore` file to prevent committing sensitive files.

4. **Dockerization**:
   - Created a `Dockerfile` to containerize the application.
   - Enabled easy deployment using Docker.

5. **Frontend Development**:
   - Designed the `index.html` template to display courses and levels dynamically.

6. **Testing and Deployment**:
   - Tested the application locally with debug mode enabled.
   - Built and ran the application inside a Docker container for consistency.

## Prerequisites

- Python 3.8+
- PostgreSQL
- Docker (optional, for containerized deployment)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd flask-app
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - Copy `.env.example` to `.env` and fill in the required values.

4. Run the application:
   ```bash
   python app.py
   ```

5. (Optional) Build and run using Docker:
   ```bash
   docker build -t flask-app .
   docker run -p 5000:5000 flask-app
   ```

## Features

- Dynamic course display by level.
- Secure environment variable management.
- Dockerized deployment for scalability.

## Screenshots

![Screenshot 1](i%20(1).png)
![Screenshot 2](i%20(2).png)

## Author

Matvey Gurilyov
