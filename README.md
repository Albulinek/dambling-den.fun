Install NGINX



TODO: Create Docker container for NGINX for webservice
```
sudo apt update 
sudo apt install nginx

enable uwf
```

TODO: Enable firewall
/etc/nginx/nginx.conf
/etc/nginx/sites-available
/etc/nginx/sites-available/mydomain.com.conf

/var/www/<site_name>

Create folder for our website
sudo mkdir -p /var/www/domain-one.com/public_html

uWSGI -> unix implementation for Web Server Gateway Service

virtualenv uwsgi-tutorial
cd uwsgi-tutorial
source bin/activate

pip install Django
django-admin.py startproject mysite <nope
cd mysite <nope

pip install uwsgi
https://uwsgi-docs.readthedocs.io/en/latest/tutorials/Django_and_nginx.html

Install Docker

Build docker



