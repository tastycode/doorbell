# doorbell

This application just listens for POST requests from `/ring`. If this
endpoint is hit, all clients make a doorbell sound. 

I use this with a smart-button that issues a post request to this
server. I have an android plugged into our house speakers with a browser
opened to this service. So if the button gets pressed, we hear a
doorbell.

```bash
   curl -x POST "http://localhost:1337/ring"
```
