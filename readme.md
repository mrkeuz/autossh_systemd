Usage
-----

Scripts for permanently create multiply ssh tunnels. 

```
git clone https://github.com/lazydev86/autossh_systemd.git

cd autossh_systemd

mkdir -p /etc/autossh/
cp tunnels.conf /etc/autossh/

ln autossh.service /usr/lib/systemd/system/autossh.service
systemctl enable autossh.service
systemctl start autossh.service

```

