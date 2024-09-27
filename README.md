# flask-official-tutorial
The contents of this repo are the results of following the official tutorial for Flask at: https://flask.palletsprojects.com/en/3.0.x/tutorial/

# Getting started, copied from: https://flask.palletsprojects.com/en/3.0.x/installation/
Python Version

We recommend using the latest version of Python. Flask supports Python 3.8 and newer.

## Dependencies

These distributions will be installed automatically when installing Flask.

    - Werkzeug implements WSGI, the standard Python interface between applications and servers.

    - Jinja is a template language that renders the pages your application serves.

    - MarkupSafe comes with Jinja. It escapes untrusted input when rendering templates to avoid injection attacks.

    - ItsDangerous securely signs data to ensure its integrity. This is used to protect Flask’s session cookie.

    - Click is a framework for writing command line applications. It provides the flask command and allows adding custom management commands.

    - Blinker provides support for Signals.

## Virtual environments
Virtual environments are independent groups of Python libraries, one for each project. Packages installed for one project will not affect other projects or the operating system’s packages.

Python comes bundled with the venv module to create virtual environments.

### Create an environment
Create a .venv folder within the project folder, navigate a prompt to the .venv folder

#### Windows
Run the following command in the prompt
> py -3 -m venv .venv

### Activate an environment
Before you work on your project, activate the corresponding environment:

#### Windows
Run the following command while in the \.venv directory:
> .venv\Scripts\activate

# Install Flask (If not previously installed)
Within the activated environment, use the following command to install Flask:
$ pip install Flask

# Run Flask
In a command prompt, navigate to the project root directory and run the command:
flask --app flaskr run --debug

To start the development server