# Flask tutorial

## Using POST
There is a file [flask_basic_app](flask_basic_app.py) which let you test POST method. To test it:
1. Activate flask in one terminal
```sh
set FLASK_APP=flask_basic_app.py
flask run
```
2. Run this command to test:
```sh
curl  -X POST -d "{\"name\":\"xyz\"}" 127.0.0.1:5000/ -H Content-Type:application/json
```
You should receive the output as:
```sh
{"you sent":{"name":"xyz"}}
```
**With file [flask_restful_basic](flask_restful_basic.py) you can do simmilar operations.**

