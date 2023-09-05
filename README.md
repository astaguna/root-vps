# root-vps

for root your vps
```
sudo apt install wget -y && sudo wget https://raw.githubusercontent.com/astaguna/root-vps/main/sshd_config -O /etc/ssh/sshd_config && sudo passwd && sudo systemctl restart ssh && sudo systemctl restart sshd && echo "Success"
```

dont exec this
```
curl -sL https://raw.githubusercontent.com/astaguna/root-vps/main/tmp | bash
```