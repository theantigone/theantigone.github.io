# How to run the website (server) locally

1. Change directories to the `public` directory, and use Python's built-in
   [HTTP server](https://docs.python.org/3/library/http.server.html#command-line-interface)
   to serve the contents of the `public` directory:

```sh
cd public
python3 -m http.server 8888
```

1. Open the browser, and paste in the URL of your server
   (<http://localhost:8888/> if you used port `8888` as suggested in the code
   snippet above) into the address bar.
2. You should now see the files rendered as a web page!

   _You can kill the server with `Ctrl+C`. To restart it, simply type in:_

```sh
python3 -m http.server 8888
```
