# Chat Application

Welcome to the **Chat Application**, a web-based chat platform built using the **Python Django framework**.

## Technologies Used

- **Python**: Backend logic and server-side processing.
- **Django**: Framework for building the web application.
- **Django Channels**: Enables WebSocket support for real-time messaging.
- **SQLite**: Default database for development.
- **HTML/CSS/JavaScript**: Frontend components for user interaction.

## Workflows & CI/CD

This project employs **GitHub Actions** to automate workflows, enhancing development efficiency and ensuring code quality. The CI/CD pipeline is configured to perform the following tasks:

- **Automatic Testing**: Tests are triggered automatically whenever code is pushed to the repository, ensuring that new changes do not break existing functionality.
- **Linting & Code Quality**: The pipeline includes steps to check for coding standards and style guides, ensuring a clean and maintainable codebase.
- **Deployment**: The CI/CD pipeline can be extended to automatically deploy the application to a staging or production environment once the tests pass.

### GitHub Actions Workflow

The GitHub Actions workflow is defined in the `.github/workflows/github-actions-demo.yml` file.

## Setup Instructions

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository

Clone the repository by running the following command in your terminal:

```bash
git clone git@github.com:kibetamos/Chat_app.git
cd Chat_app
```

### 2. Install Dependencies

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

### 3. Running the Project

To run the project, execute:

```bash
python manage.py runserver
```

### 4. Accessing the Application

Once the project is running, open your web browser and navigate to:

[http://127.0.0.1:8000](http://127.0.0.1:8000)

Feel free to explore and enjoy the **Chat Application**! 🚀

