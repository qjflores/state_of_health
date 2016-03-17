#How can we better understand the state of "access" in the world?


With the enormous amount of data from a host of different organizations available on the Internet today, we now are able to gain new insights into the state of world health and understand patients like never before.

How can we leverage public datasets and application programming interfaces (API) to build insights and visualizations on which diseases are most burdensome to patients, hospitals and global economies?

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

