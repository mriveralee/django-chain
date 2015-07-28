Quick Commands
# Setup Overview
0. Activate VirtualEnv
  `source ./env/bin/activate`
1. Start Mysql with Test User
  `mysql --user=test_user --password=test123`
2. Migrate Databases / Create Tables for [Django](https://docs.djangoproject.com/en/1.8/intro/tutorial01/):
  `sudo python manage.py migrate`
3. Start the Django Development Server
  `python manage.py runserver`
  Note: Default port is ip:port is `127.0.0.1:8000`. It can be changed using the
  start command: `python manage.py runserver [?ip:port]` - The ip is optional
4. Test your Django Application:
  `python manage.py startapp [app_label]`

# Making Changes to Models
1. Edit `models.py` to change the modes  
2. Run `python manage.py makemigrations` to create migrations for those changes
3. Run `python manage.py migrate` to apply those changes to the database
