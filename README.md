# Notes-To-Self

An app for writing date-stamped notes to an SQLite database.

By default, this app runs in debug mode.

All notes are saved to the 'test.db' file.

This app is a fork of [this repo](https://github.com/jakerieger/FlaskIntroduction).

# Checklist

- Make sure than python is installed and on the $PATH.
- Make sure that pip is installed and on the $PATH
- If you are NOT using a virtual environment, then make sure that all the modules listed in 'requirements.txt' are installed globally with pip.

# To use the virtual environment

Enter the following commands

```
$ cd env/bin/
$ source activate
```

# To deactivate the virtual environment

```
$ deactivate
```

# To run the app

Open a terminal in the the working directory, then run the command

```
$ py app.py
```

# Boomark 'localhost:5000'

Once the server is running, open your browser at [localhost:5000](http://localhost:5000/) to use the app.


# Clear cache to see changes

A 'clear cache' browser extension may need to be used in order see changes in the app on localhost.
