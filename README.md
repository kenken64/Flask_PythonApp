## Install flask

```
pip install flask
```

## Check flask version
```
python -c "import flask;print(flask.__version__)"
```
```
$ 2.1.3
```

## set main program 

```
export FLASK_APP=main
```

## set flask env

```
export FLASK_ENV=development
```

## Run flask program

```
flask run
```

```
* Serving Flask app 'main' (lazy loading)
 * Environment: development
 * Debug mode: on
 * Running on http://127.0.0.1:5000 (Press CTRL+C to quit)
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 802-447-687
```

## run it on different port 

```
flask run -p 5001
```

## export diff app 

```
export FLASK_APP=app
```

## App url 
https://protected-cove-84979.herokuapp.com/ 

## Git url
https://git.heroku.com/protected-cove-84979.git

## Deployment

```
echo "web: gunicorn app:app" > Procfile
python3 -m pip install Flask==1.1.2
python3 -m pip freeze > requirements.txt
```