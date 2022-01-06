# Connect to a server via ssh remote

1. Create ssh key from local computer
```
openssl genrsa -aes128 -passout pass:PASSWORD -out mykey 2048
openssl rsa -in mykey.pem -pubout > mykey.pub
cp mykey mykey.pub ~/.ssh/
```

2. Add SSH login for username
```
ssh-copy-id -i ~/.ssh/mykey username@host
```
Now we can login into remote server with ssh
