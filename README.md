# https://class-scheduler-erel.herokuapp.com/
# class-scheduler
Built with guide: https://stackabuse.com/deploying-a-flask-application-to-heroku/

## Running web server locally
```
python -m venv venv/
source venv/bin/activate
pip install -r requirements.txt
python app.py
```
Then go to localhost:5000

## Add new packages
```
source venv/bin/activate
pip install <package_name>
pip freeze > requirements.txt
```
Make sure you commit the requirements file

App dashboard on Heroku: https://dashboard.heroku.com/apps/class-scheduler-erel/

# Future Improvements

### Use job scheduling to improve peformance
https://devcenter.heroku.com/articles/python-rq
