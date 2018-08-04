# Docker Mailhog Shared

Docker compose setup for Mailhog to be shared with multiple projects in local machine.

Mailhog is an application that acts like an SMTP server which can be used to testing emails without actually sending emails.

## Usage

Run the container.

~~~
cd /path/to/docker-mailhog-shared
sudo docker-compose up -d
~~~

Visit the Web interface at: http://localhost:8025

Point your app's SMTP settings to:

* SMTP host: 127.0.0.1
* PORT: 1025
