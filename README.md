# deepRL-nd


Install jupyter notebook kernel for virtualenv:
$ ipython kernel install --user --name=env --display-name "whatever the heck u want"


To generate requirements.txt from a virtualenv:
(env) $ pip install pip-tools
(env) $ pip-compile #requires setup.py


To update all installed packages:
(env) $ pip-compile --upgrade

To update a virtualenv to requirements.txt:
(env) $ pip-sync
