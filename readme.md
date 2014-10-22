Usage
-----

Script start multiple ssh tunnels with autossh and simple conf file. 


```
mkdir -p /etc/autossh/

cd autossh_systemd

cp autosshd.conf /etc/autossh/
cp autosshd /usr/bin
cp autosshd.service /usr/lib/systemd/system/autosshd.service

systemctl enable autosshd.service
systemctl start autosshd.service

```

Configuration file
------------------

Read file `autosshd.conf` and start `autossh` process for each line (expect comments).





