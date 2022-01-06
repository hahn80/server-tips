# Install nginx server

1. Install nginx server
```
sudo apt install nginx
```

2. Adjust the firewall
```
sudo ufw app list
sudo ufw status
sudo ufw allow 'Nginx HTTP'
sudo ufw allow 'Nginx HTTPS'
sudo ufw allow 'OpenSSH'
sudo ufw show added
sudo ufw enable

sudo ufw status numbered
sudo ufw delete 3
```
