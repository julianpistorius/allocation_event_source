web: newrelic-admin run-program gunicorn --pythonpath="$PWD/allocation_event_source" wsgi:application
worker: python allocation_event_source/manage.py rqworker default