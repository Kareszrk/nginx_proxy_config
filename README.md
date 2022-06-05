### What is in this repository?

- Contains an implementation example of a proxy_pass from port to port on domain
- Shows you how to implement the same with SSL and auto redirect from 80 to 443

### How to install nginx?
Use the command below to install nginx

`$ apt install nginx -y`

------------
### Where to put this code into?
Open up a text editor, for example nano to edit the following file:

`$ nano /etc/nginx/sites-avaliable/default`

------------


This configuration is well-tested on over 100 concurrent visitors. Works perfectly.
