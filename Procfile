web: gunicorn happyfuntime.wsgi --chdir backend --limit-request-line 8188 --log-file -
worker: celery worker --workdir backend --app=happyfuntime -B --loglevel=info
