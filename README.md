# nginx-proxy

We add a custom configuration file to jwilder/nginx-proxy to customize it for Amazon ELB used
The settings therein are meant to prevent HTTP 499 errors as well as making sure we see the originiating client IP in our logs rather than the Amazon ELB address.
