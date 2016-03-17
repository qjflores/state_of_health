# state_of_health

set up your virtualenv with virtualenvwrapper

# set up your dev env
http://cookiecutter-django.readthedocs.org/en/latest/developing-locally.html

# create you db

createdb state_of_health
createdb user state_of_health with password state_of_health

grant priveleges to db

export DATABASE_URL="postgres://state_of_health:state_of_health@127.0.0.1:5432/state_of_health"

# install python dependent packages 
sudo apt-get install python-dev python-pip libxml2-dev libxslt1-dev zlib1g-dev libffi-dev libssl-dev

# pip install requirements
pip install -r requirements.txt
pip install -r requirements/local.txt

