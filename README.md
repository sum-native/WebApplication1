# WebApplication1
.NET Application with docker features

Running the app:

$docker build -t webapplication .

$docker run -d -p 80:80 -p 443:443 --name test-app webapplication

Accessing the app:

Browse to http://localhost/ or https://localhost/
