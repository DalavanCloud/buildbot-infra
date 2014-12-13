This roles allows to create a Python virtual environment.

The role should be used with the following parameters:

``venv_user``
    The user under which the virtual environment is created

``venv_home_dir``
    ansible likes absolute paths in way too many places, the virtual
    environment is created in the users' home directory and this is its path

``venv_name``
    The name of the virtual environment

``venv_packages``
    packages to be installed using 'pkgng'

``venv_python_packages``
    Python packages to be installed using 'pip install'
