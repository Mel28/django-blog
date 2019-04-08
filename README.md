<h4>Command line commands</h4>
<ul>
<li> sudo pip3 install django==1.11 </li>
<li>django-admin startproject django_blog . </li>
<li>python3 manage.py runserver $IP:$C9_PORT (then copy suggested host into allowed host array within settings file.)</li>
setting up virtual env :
wget -q https://git.io/v77xs -O /tmp/setup-workspace.sh && source /tmp/setup-workspace.sh 
Then you can create a virtual environment with any name. The name foo is just a common placeholder variable name in computing. Use a name that means something to you. 

To activate this new virtual environment you use the workon command. 
workon foo 
To deactivate it you can use 
deactivate 

#Djano Blog

<h3>Testing</h3>
[![Build Status](https://travis-ci.org/Mel28/django-blog.svg?branch=master)](https://travis-ci.org/Mel28/django-blog)


<h4> commands </h4>
./manage.py createsuperuser : creates a super user
./manage.py makemigrations 
>> migrate : migrates the application
./manage.py runserver $IP:$PORT : runs the app