Usage
-----

Scripts for permanently create multiply ssh tunnels. 

```
gir clone https://github.com/lazydev86/autossh_systemd.git

mkdir -p /etc/autossh/
cp tunnels.conf /etc/autossh/
ln autossh.service /usr/lib/systemd/system/autossh.service
systemctl enable autossh.service
systemctl start autossh.service
```

