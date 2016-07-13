# nginx-project-server

These are the config files for the node-project-server nginx setup. 

This setup assumes node-project-server is running on port 8080 on the same machine.


Build instructions for Linux:

    1. install nginx with package manager

    2. copy nginx.conf and sites-available to /etc/nginx

    3. copy sites-available/default to /etc/nginx/sites-enabled

    4. start nginx with $sudo nginx
    
    5. test the server by going to localhost in the browser
