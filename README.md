# [scttmthsn/rwasa](https://hub.docker.com/r/scttmthsn/rwasa/)

[rwasa](https://2ton.com.au/rwasa/) is a full-featured, high performance,
scalable web server. It's written in x86_64 with no external library dependencies.

Run the container, binding a directory to serve from to `/var/www`.

    docker run -d -p 8080:8080 -v /path/to/serve:/var/www scttmthsn/rwasa

To check whether it worked, browse to [http://localhost:8080](http://localhost:8080).