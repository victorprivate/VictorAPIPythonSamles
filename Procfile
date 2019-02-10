web: gunicorn VictorAPIPythonSamles:app -preload
heroku ps:scale web=1
heroku open
heroku logs --tail
heroku config:set WEB_CONCURRENCY=3
