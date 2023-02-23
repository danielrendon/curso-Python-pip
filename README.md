# Game Project

For running the game you must type the next commands in WSL terminal:

```sh
cd game
python3 main.py
```
# App Project

For installing virtual environment in linux:

```sh
sudo apt install -y python3-venv
```

For creating virtual environment creation in a module:

```sh
python3-m venv env  (env is replaced with the name of the environment)
```


To activate virtual environment:

```sh
source env/bin/activate
```

To exit virtual environment:

```sh
deactivate
```

Send needed dependencies to requirements.txt

```sh
pip3 freeze > requirements.txt
```

Install dependencies from requirements.txt

```sh
pip3 install -r requirements.txt
```

# If you want to contribute to the Population Project follow this steps
```sh
git clone
cd app
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
```