# Emotion Classification Django Application

This is a Django-based web application for emotion classification. The project includes a machine learning model for classifying emotions, which is implemented in a Jupyter Notebook.

## Project Structure

- `mysite/` - Contains the Django project files.
- `Emotion Classification.ipynb` - Jupyter Notebook for emotion classification model training and testing.
- `LICENSE` - The license for the project.
- `README.md` - This file.

## Requirements

- Python 3.x
- Django 3.x (or the version you are using)
- Jupyter Notebook
- Required Python libraries

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. Create a virtual environment and activate it:

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the dependencies

4. Navigate to the Django project directory:

    ```bash
    cd mysite
    ```

5. Apply migrations:

    ```bash
    python manage.py migrate
    ```

## Running the Application

1. Navigate to the Django project directory (if not already there):

    ```bash
    cd mysite
    ```

2. Run the Django development server:

    ```bash
    python manage.py runserver
    ```

3. Open your web browser and go to `http://127.0.0.1:8000/home` to see the application running.

## License

This project is licensed under the terms of the MIT license. See the `LICENSE` file for details.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.
