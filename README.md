## Terminal API Flows

Setup a venv with Python 3.

Adjust the settings for your environment inside the `__init__.py` file inside the `terminal_api_flows` folder.

To install:
> pip install -e .

Ensure urllib3 is installed if it is not already:
> pip install urllib3

You can then run the `terminal-api.py` file as you wish. I did not put in an `entry_points` for it in `setup.py` since most likely it will be run with a debugger inside VSCode or PyCharm.
