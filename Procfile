web: gunicorn aresapi.wsgi -w 4 --max-requests 100
worker: celery -A  aresapi worker --concurrency=8 -Ofair
beat: celery -A aresapi beat
