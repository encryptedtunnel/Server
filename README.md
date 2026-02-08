  schema of Vagrant vm with root ssh access :)
  if you want you can set user for your inventory and hosts
```
    _________________________________
    |                                |
    |   _________      __________    |
  80+--|  nginx  |----|  backend |   |
 443+--|         |    |__________|   |
    |  |         |     ___________   |
    |  |         |----|  frontend |  |
    |  |_________|    |___________|  |
    |   __________                   |
  22+--| fail2ban |                  |
    |  |__________|                  |
    |________________________________|
    |
    |---> iptables
```