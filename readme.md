Usage
-----

Script start multiple ssh tunnels with autossh and simple conf file. 


```
mkdir -p /etc/autossh/

cd autossh_systemd

cp tunnels.conf /etc/autossh/
cp autosshd /usr/bin
cp autossh.service /usr/lib/systemd/system/autossh.service

systemctl enable autossh.service
systemctl start autossh.service

```

Configuration file
------------------

Read file `tunnels.conf` and start autossh process for each line (expect comments).





