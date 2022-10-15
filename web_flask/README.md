# Web Flask

This is a sub-project within AirBnB Clone die as part of my of my learning process at Alx_Africa Software Engineering Programme 2022 in which I began working with Flask
and Jinja2. In this project, I began integrating the back-end storage engine
with the web static webpages written prior.


The most complete Flask/Jinja app-template combo in this directory is defined
in Flask module [100-hbnb.py](./100-hbnb.py) and Jinja template
[100-hbnb.html](./100-hbnb.html).

Execute the following command from the root directory of the project to run the Flask app:

```
~ $ HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost
HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_flask.100-hbnb
```

The app can be accessed at `0.0.0.0:5000/hbnb`.
