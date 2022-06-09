## Requirements
- python3

## Installation
```
pip install ansible ansible-galaxy
ansible-galaxy install -r requirements.yml
```

## Authelia password generation

Login to container and run `authelia hash-password -m 128 -i 2 <password>`

## To do
- add vuetorrent iOS fix
- openvpn_qbit .ovpn file
