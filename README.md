# Bookrev
This is a Book Review App. Which lets you register, login, see reviews
about the books you find by searching with their ISBN and also submit your own review.
This app has its own API you can use.

# HOW TO USE
1. In a terminal window, navigate into your project1 directory.
2. Run ( pip3 install -r requirements.txt ) in your terminal window to make sure that all of the necessary Python packages (Flask and
      SQLAlchemy, for instance) are installed.
3. Set the environment variable FLASK_APP to be application.py. On a Mac or on Linux, the command to do this is
      ( export FLASK_APP=application.py )
4. You may optionally want to set the environment variable FLASK_DEBUG to 1,
      ( FLASK_DEBUG=1 )   which will activate Flask’s debugger and will automatically reload your web application whenever
      you save a change to a file.
5. Set the environment variable DATABASE_URL to be the URI of your database,
    ( export DATABASE_URL= 'Your database URI' ) .which you should be able to see from the credentials page on Heroku.
6. Run ( flask run ) to start up your Flask application.
