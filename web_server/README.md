# Web server

Bash scripts that configure an Ubuntu 16.04 web server: installing
Nginx, setting up redirects, and creating a custom 404 error page.

## Files

- 0-transfer_file: Bash script that transfers a file from the client
  to the server using scp with a given SSH private key.
- 1-install_nginx_web_server: Bash script that installs and configures
  Nginx to serve a page containing "Holberton School".
- 2-setup_a_domain_name: contains the domain name configured with an
  A record pointing to the web-01 server IP.
- 3-redirection: Bash script that configures Nginx to redirect
  /redirect_me with a 301 Moved Permanently response.
- 4-not_found_page_404: Bash script that configures Nginx with a
  custom 404 page containing "Ceci n'est pas une page".
