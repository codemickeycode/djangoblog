djangoblog
==========

simple django blog - product of following this tutorial:
http://net.tutsplus.com/tutorials/python-tutorials/python-from-scratch-creating-a-dynamic-website/

Create Virtualenv
```
mkvirtualenv -a <Projects path>/djangoblog --no-site-packages djangoblog
```

Create models and run server
```
(test)mickey:~/Projects/djangoblog (master)$ python manage.py syncdb

(test)mickey:~/Projects/djangoblog (master)$ python manage.py runserver
```
