# Flask-TailwindCSS Starter Project

This is a starter project for building Flask web applications with integrated Tailwind CSS for styling.

## Installation

To use this project, follow these steps:

1. Clone the repository:

`git clone https://github.com/your-username/your-project.git`

2. Change into the project directory:

`cd your-project`

3. Install the required Python packages using pip:

`pip install -r requirements.txt`

4. Install the required Node.js packages using npm:

`npm install`

## Usage

To start the Flask application, run the following command:

`python run.py`

The application will be accessible at http://localhost:5000/.

## Watching Tailwind CSS

This project includes a script that watches for changes in the CSS file and automatically recompiles it using Tailwind CSS.

To start the watcher, run the following command in a separate terminal window:

`npm run create-css`

This will start the watcher and keep an eye on the CSS file for changes. Any changes you make to the CSS file will trigger the recompilation process, and the changes will be reflected in the application immediately.

## Project Structure

The project structure follows a standard Flask application layout with integrated Tailwind CSS. Here's an overview of the main directories and files:

- `app/`: Contains the Flask application files.

  - `static/`: Contains the static assets such as CSS, JavaScript, and images.
  - `templates/`: Contains the Jinja2 templates used for rendering views.
  - `routes.py`: Defines the routes and view functions.
  - `models.py`: Includes the database models if applicable.
  - `forms.py`: Includes the form definitions if applicable.
  - Other files and directories specific to your application.

- `run.py`: The entry point for running the Flask application.

- `requirements.txt`: Lists the Python packages required for the project.

## Contributing

Contributions to this starter project are welcome. If you encounter any issues or have suggestions for improvements, please submit them via GitHub issues or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
