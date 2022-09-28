Errors encountered
when trying to run python script on GCP, I get an error saying ### "thierry_pierre@flask-basic:~/flask-with-db$ python3 app.py
 * Serving Flask app 'app' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
Traceback (most recent call last):
  File "app.py", line 39, in <module>
    app.run(debug=True, host='0.0.0.0', port=800)
  File "/home/thierry_pierre/.local/lib/python3.6/site-packages/flask/app.py", line 920, in run
    run_simple(t.cast(str, host), port, self, **options)
  File "/home/thierry_pierre/.local/lib/python3.6/site-packages/werkzeug/serving.py", line 991, in run_simple
    s.bind(server_address)
PermissionError: [Errno 13] Permission denied"