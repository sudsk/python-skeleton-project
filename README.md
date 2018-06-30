# Python skeleton project

Whenever you want to start a new project, just do this:

1. Make a copy of your skeleton directory. Name it after your new project.

2. Rename (move) the NAME directory to be the name of your project or whatever you want to call your root module.

3. Edit your setup.py to have all the information for your project.

4. Rename tests/NAME_tests.py to also have your module name.

5. Double check it’s all working by using nosetests.

6. Start coding.  

# Setting up a virtualenv

Setup a .venvs directory where you can store all your virtual environments. 
```
mkdir ~/.venvs
```

Create a new virtual env with name "lpthw" - you can name it whatever you wish.
```
python3 -m venv --system-site-packages ~/.venvs/lpthw
```

Activate a virtual env
```
. ~/.venvs/lpthw/bin/activate
```

For nosetests, install nose
```
pip install nose
```

# Setting up python projects

Create a projects folder to store all python projects
```
mkdir ~/projects
```

Download the skeleton project folder from git. Optionally rename the project. Then run nosetests.
```
(lpthw) $:~/projects/skeleton$ nosetests
.
----------------------------------------------------------------------
Ran 1 test in 0.007s

OK
```
