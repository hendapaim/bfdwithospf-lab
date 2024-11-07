# BFD - Bidirecional Forwarding Detection
BFD - Bidirecional Forwarding Detection

    - Melhor tecnica para detectar falhas no link, porque acelera o tempo de convergência.

Lab on EVE-NG

Conf: 

if# bfd interval 50 min_rx 50 multiplier 3 

router ospf 24
    bfd all-interfaces
    network 192.168.24.X 0.0.0.255 area 0