# Python
First step run poetry install 
Second step run gunicorn -w 4 -b 0.0.0.0:8000 main:app to start WSGI server
To HTTP add /api/v1/hello-world-3 to see result
