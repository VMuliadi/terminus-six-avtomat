# terminus-six avtomat

## pre-requisites
- registered ssh on raspberry pi
- openssh-client
- ansible

## (optional) initial setup
- `ansible-vault create credentials.yml`

## ansible-vault value
### noip-ddns-duc.yaml
```
no-ip:
  user: {{noip_user}}
  password: {{noip_password}}
  hostname: {{noip_hostname}}
```
