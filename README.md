# PythonAlibabaApacheServerSSLWorking
how to deploly flask app with wsgi in alibaba centos 7 with ssl from letsencrypt

app folder: /var/www/hitme
configuration folder: /etc/httpd
SSL certificate :
https://www.rosehosting.com/blog/how-to-install-lets-encrypt-with-apache-on-centos-7/

check you google keep: 
https://keep.google.com/u/0/#NOTE/1okQlv7rNiE_lrL1DA_PNtAhu18FTYEUckL2IqeRvatLpBBH8Q_WVVLeLCZxPpww
systemctl restart httpd.service
Alibaba console creds : rameshelava@gmail.com,regularPwd
Host: 147.139.1.55
port : 22
username: root
password: regularPwd

Apache httpd flask run 
/var/www/hitme
https://dev.to/sm0ke/flask-deploy-with-apache-on-centos-minimal-setup-2kb7
URL to test: 147.139.1.55/posts 
merge the above code with below to get sqllite marshmallow
https://rahmanfadhil.com/flask-rest-api/
pip install Flask \
    Flask-SQLAlchemy \
    Flask-RESTful \
    flask-marshmallow
    
    Minimal apache configuration
    https://www.codementor.io/@abhishake/minimal-apache-configuration-for-deploying-a-flask-app-ubuntu-18-04-phu50a7ft
