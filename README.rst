======================
MailAdmin distribution
======================

This is the default distribution using the django-mailadmin package to build an installable and ready to use application.

-----------
Quick start
-----------

1. Run `git clone https://github.com/thommyhh/mailadmin-distribution.git mailadmin` to clone the distribution repository

2. Change into the directory by running `cd mailadmin`

3. Prepare your virtual environment to not mess up your system: `mkdir ./venv && virtualenv ./venv -p python3` You may need to adjust "-p python3" to use the correct python version on your system

4. Activate your virtual environment: `. venv/bin/activate`

5. Install the packages: `pip install -r requirements.txt`

6. Execute migrations: `python manage.py migrate`

7. Create an admin user: `python manage.py createadmin`

8. Start the development server: `python manage.py runserver`

9. Open http://localhost:8000/mailadin/ and log in with your admin user
