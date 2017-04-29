# RandomAPI
A simple API which returns a random object after a random amount of time with a random status code - unless you tell it not to

Use this for testing various API things. Esp useful for testing how your app might respond to long or erroneous requests.

* CORS enabled, so feel free to hit it up with js
* It's set up to deploy to Heroku, so if mine stops working, feel free to deploy to your own Heroku ;)
* supports `GET` and `POST`

## Usage

```
curl https://random-api-responder.herokuapp.com/api/ -i

HTTP/1.1 303 See Other
Connection: keep-alive
Server: gunicorn/19.7.1
Date: Sat, 29 Apr 2017 11:57:49 GMT
Content-Type: application/json
Access-Control-Allow-Origin: *
Content-Length: 327
Via: 1.1 vegur

{"esse": "timhuang@taylor.biz", "necessitatibus": "2002-11-11T21:39:47", "dignissimos": "amandafoster@young-torres.com", "doloribus": "1990-07-07T23:25:32", "vitae": "wsbnDvkhdXzDCXqipdkX", "quisquam": "1984-08-12T12:18:10", "dolor": "http://gordon.com/register.html", "quo": "linda30@brown.com", "aut": "bJpasAqukmCkztjtaWXO"}
```


