# 2019-10-28-Lyon-Docker-Meetup

My talk from the Lyon, France Docker Meetup on October 28, 2019.

# Slides

The slides are written using [RevealJS](https://revealjs.com). To view the presentation, open `index.html` in your web browser.

You can also run a local HTTP static file server, for example:

```console
$ python -m SimpleHTTPServer 7000
```

And then open `http://localhost:7000` in your browser.

# Demo

This demo comes straight from [Servantes](https://github.com/windmilleng/servantes). To try it out, [install Tilt](https://docs.tilt.dev/install.html) and then run these commands:

```console
$ cd servantes
$ tilt up
```

You should see a colorful console UI pop up in your browser. You can scroll between the different services that Tilt is running for you and check out their logs, status, etc...

Also, you can pop up a browser view of all this in action. Press the `b` key to open it up. In the browser view, you can click on one of the services on the right side and see the same kind of information as in the terminal (logs, status, etc...) but importantly, you can also get a link to the port-forwarded server that service runs on!

Simply click that link and see the particular microservice running.