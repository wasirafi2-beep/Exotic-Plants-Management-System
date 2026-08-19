ERROR: ValueError: password cannot be longer than 72 bytes, truncate manually if necessary (e.g. my_password[:72])

Solution:
    Check your bcrypt version:
        Run:
            ```python -m pip show bcrypt```
        You'll probably see:
            Version: 5.0.0

    Install bcrypt 4.3.0:
        Run:
            ```python -m pip install bcrypt==4.3.0```
            