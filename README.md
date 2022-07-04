# Locust Demo for CSCC09
A demonstration of how to stress test web server traffic with Locust.

## Development Setup
1. Create a `virtualenv`
2. Install dependencies
```
(venv) pip install requirements.txt
```
3. Run locustfile
```
$ locust -f locustfile.py --host=https://microblog.cscc09.com
```
4. Visit http://0.0.0.0:8089/ for Locust UI