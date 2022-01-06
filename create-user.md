1. Create a normal user:
```
adduser username
```

2. Add sudo privileges to username
```
usermod -aG sudo username
```

3. Create nginx user
```
sudo adduser --system --no-create-home --group --disabled-login  nginx
```

4. List all users and groups
```
less /etc/passwd
less /etc/group
```
