# Grizzlt Hardwood App

Built with python and falcon from this [core set of docs](http://falcon.readthedocs.io/en/stable/user/tutorial.html)

#### Notes along the way first build:

Install list, using pip3 and python3.6:
 - falcon
 - ipython, for REPL
 - gunicorn
 - httpie
 - pytest
 - msgpack

Whats done:

 - Start the virtaul env with `source .venv/bin/activate`
 - Start the api server from the root with `gunicorn --reload wood.app`
 - test routes with `curl` or `httpie`


