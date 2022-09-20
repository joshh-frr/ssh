# reference
```
ssh-keygen -t rsa -b 4096 -C "test@email.com"
[enter]
[enter new passphrase]
eval $(ssh-agent -s)
ssh-add ~/.ssh/id_rsa
clip < ~/.ssh/id_rsa.pub


you can set your own file location
ssh-keygen -t rsa -b 4096 -C "test@email.com" -f ~/.ssh/id_rsa2
```
