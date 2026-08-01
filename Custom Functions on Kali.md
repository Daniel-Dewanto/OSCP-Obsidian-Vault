# `vpnup`
>Used to start OFFSEC VPN

```shell
# connect to the OffSec VPN using universal.ovpn
vpnup() {
    sudo openvpn --config /home/kali/offsec/universal.ovpn "$@"
}
```

