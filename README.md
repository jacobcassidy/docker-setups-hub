# Docker Setups Hub

This hub lists my various repositories containing Docker files for quickly setting up local servers for different development environments.

## NGINX-Proxy Network Development Servers

The following repositories use a [standalone NGINX Reverse-Proxy Docker network](https://github.com/jacobcassidy/docker-nginx-proxy-setup) that allows you to run multiple local servers simultaneously, all using unique local domain names on the standard 80 (HTTP) or 443 (HTTPS) ports. Which removes the need to manage port numbers, gives you clean domains to work from (no appended port number), and manages running your local domains on the HTTPS protocol with self-created TLS certificates:

### PHP Development Servers

- [NGINX, PHP-FPM & MySQL](https://github.com/jacobcassidy/docker-nginx-phpfpm-setup)
- [NGINX, PHP-FPM, MySQL, and Ray](https://github.com/jacobcassidy/docker-nginx-phpfpm-ray-setup)

### WordPress Development Servers

- [WordPress & MySQL](https://github.com/jacobcassidy/docker-wordpress-setup)
- [WordPress, MySQL, and Ray](https://github.com/jacobcassidy/docker-wordpress-ray-setup)
