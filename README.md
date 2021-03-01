**Digital Blood Bank Nepal**
============================

* * *

### About this project

This is a small project by the students of Amrit Science College. This project uses MongoDB and is deployed to Heroku. This The sebsite for this project is [dbb.ayushb.com](dbb.ayushb.com)

* * *

### Environment Variables

Please set the following environment variables for the program to run:

*   `DBB_DJANGO_SECRET`: This is the secret key for django during production. Keep it safe.

* * *

### Local Server Deployment

You can deploy this project in your local server using the following steps:

*   `pip install -r requirements.py`
*   `python manage.py makemigrations`
*   `python manage.py migrate`
*   `python manage.py runserver`

You can then access this project on your browser using:

`127.0.0.1:8000`

* * *

### Remote Server Deployment

While deploying to the remote server please go to `DigitalBloodBank/settings.py` and change the values in `ALLOWED_HOSTS` as per your requirements.

* * *

This is an open source project by:

*   Anubhav Gautam: [Github](www.github.com/) [Twitter](twitter.com/)
*   Ayush Bhattarai: [Github](www.github.com/aaxyat) [Twitter](twitter.com/aaxyat)
*   Pramila Chapagain: [Github](www.github.com/) [Twitter](twitter.com/)
*   Utsarga Pokharel: [Github](www.github.com/) [Twitter](twitter.com/)