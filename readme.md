Usage
-----

Script for permanent start multiple tunnels with simple conf file. 


```
mkdir -p /etc/autossh/

cd autossh_systemd

cp tunnels.conf /etc/autossh/
cp autosshd /usr/bin
cp autossh.service /usr/lib/systemd/system/autossh.service

systemctl enable autossh.service
systemctl start autossh.service

```

