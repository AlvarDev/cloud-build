# cloud-build
This is a demo for a GLab about Cloud Build

Run localhost test
```shell
gunicorn -b 0.0.0.0:8080 main:app
```

Test locally
```shell
curl -X POST \
	http://localhost:8080/echo \
	-H 'Content-Type: application/json' \
	-d '{"name": "AlvarDev"}'
```
