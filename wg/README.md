

Using `wg-quick`, put a valid wireguard configuration at `/etc/wireguard/`
```
sudo systemctl enable wg-quick@wg0.service
sudo systemctl daemon-reload

# if desired
sudo systemctl start wg-quick@wg0
```


## Reference
https://www.ivpn.net/knowledgebase/linux/linux-autostart-wireguard-in-systemd/
