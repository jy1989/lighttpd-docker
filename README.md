# lighttpd Docker image

gen file for download in lighttpd then you can test the speed of server

fork from [spujadas/lighttpd-docker](https://github.com/spujadas/lighttpd-docker)  and add download page

### Start a container with Docker

With the default configuration files:

	$ sudo docker run --rm -t -p <http-port>:80 jy1989/lighttpd-download-test

### go to http://yoursite:<http-port>  you will see the download page.


