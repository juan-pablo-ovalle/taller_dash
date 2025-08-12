# 1. Usefull commands

## 1.1. Connect to a AWS EC2 instance via ssh with .pem key pair file

```
ssh -o IdentitiesOnly=yes -i taller_dash_instance_keypair.pem ec2-user@13.222.189.138
```

## 1.1 Access to this app runing from aws ec2 instance

```
http://13.222.189.138:8050
```