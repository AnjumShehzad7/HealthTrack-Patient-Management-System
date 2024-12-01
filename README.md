
 HealthTrack Patient Management System


**HealthTrack** is an open-source Electronic Medical Record (EMR) and Patient Management System built using Django. It is designed to simplify the management of patient data, appointments, and medical records for healthcare providers. With a user-friendly interface and a modular structure, HealthTrack is easy to customize and extend for various healthcare needs.

Key Features:
- Patient data management
- Appointment scheduling
- Secure medical records storage
- Customizable and modular architecture
- Built-in admin panel for managing healthcare operations

---

### Project Structure:

- **docs/**: Documentation files for the project.
  - `source/`: Contains Sphinx configuration files for generating project documentation.

- **HealthDB/** (to be renamed **HealthTrack/**):
  - `patient/`: Django app responsible for managing patient-related functionality.
  - `static/`: Static assets (CSS, JavaScript, images).
  - `templates/`: HTML templates for rendering pages.
  - `settings.py`: Django project settings.
  - `urls.py`: URL routing configuration.
  - `views.py`: Django views to handle HTTP requests and responses.
  - `wsgi.py`: Entry point for WSGI-compatible web servers.

- **static/**: General static files for the project.
  - `admin/`: Styles and scripts specific to the admin panel.
  - `css/`: General CSS files.
  - `js/`: JavaScript files for client-side functionality.

- **README.rst**: Project documentation and setup instructions.
- **requirements.txt**: Python dependencies required for the project.
- **pavement.py**: Paver tasks for project setup and management.
- **manage.py**: Django management script for running development server, migrations, etc.

---

### Ubuntu 14.04 Development Build Instructions:

    # Retrieve the latest apt-get list
    $sudo apt-get update

    # Install virtualenv, pip, and paver
    $sudo apt-get install python-pip python-virtualenv python-paver

    # Fork HealthTrack
    http://github.com/<your_user_name>/HealthTrack

    # Clone your forked repo
    $git clone https://github.com/<your_user_name>/HealthTrack.git

    # Install dependencies
    $cd HealthTrack
    $paver setup

    # Start the development server
    $paver start

---

### Mac OS X Development Build Instructions:

    # Install pip
    $sudo easy_install pip

    # Install virtualenv and paver
    $sudo pip install virtualenv paver

    # Fork HealthTrack
    http://github.com/<your_user_name>/HealthTrack

    # Clone your forked repo
    $git clone https://github.com/<your_user_name>/HealthTrack.git

    # Install dependencies
    $cd HealthTrack
    $paver setup

    # Start the development server
    $paver start

---

Languages Used:
- JavaScript: 51.9%
- CSS: 31.0%
- Python: 12.1%
- Shell: 5.0%

