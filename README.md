# Django To-Do List Application

A simple and stylish to-do list web application built using the Django framework. This project allows users to easily manage their tasks by adding, marking them as complete, and deleting them.

## Features

* **Add Tasks:** Easily input and add new tasks to your list.
* **View Tasks:** See all your active and completed tasks at a glance.
* **Mark as Complete:** Toggle the status of a task to mark it as finished. Completed tasks are visually distinguished.
* **Delete Tasks:** Remove tasks from your list that are no longer needed.
* **Clean and Responsive Design:** Features an attractive and user-friendly interface thanks to custom CSS.

## Technologies Used

* **Python:** The primary programming language.
* **Django:** A high-level Python web framework used for building the application.
* **HTML:** Used for structuring the web pages.
* **CSS:** Used for styling the application and providing a visually appealing user interface.
* **SQLite:** The default lightweight database used by Django for development (can be configured for other databases).
* **Git:** For version control.
* **GitHub:** For hosting the project repository.

## Setup Instructions

1.  **Clone the Repository:**
    ```bash
    git clone <repository_url>
    cd django-todolist
    ```
    *(Replace `<repository_url>` with the actual URL of your GitHub repository)*

2.  **Create and Activate a Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS and Linux
    venv\Scripts\activate  # On Windows
    ```

3.  **Install Dependencies:**
    ```bash
    pip install Django
    ```

4.  **Make Migrations:**
    ```bash
    python manage.py makemigrations tasks
    python manage.py migrate
    ```

5.  **Run the Development Server:**
    ```bash
    python manage.py runserver
    ```

6.  **Open in Browser:**
    Navigate to `http://127.0.0.1:8000/` in your web browser to view the application.

## Usage

* **Adding Tasks:** Enter your task in the input field at the top of the page and click the "Add Task" button.
* **Completing Tasks:** Click the "Complete" link next to a task to mark it as done. The task will be displayed with a strikethrough.
* **Deleting Tasks:** Click the "Delete" link next to a task to remove it from your list.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them.
4.  Push your changes to your forked repository.
5.  Submit a pull request.


## Author

[V S Krishna Chaitanya Avvari/krishchai73]
