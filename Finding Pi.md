# Finding Pi

The RaspberryPi is only available at local net, so you need to be physically present
at the club (or connected via ssh to the dedicated server).

## Ubuntu
```
sudo nmap -sP 192.168.0.0/24 | grep B8:27:EB -B 2
```

The response will cotanin the IP along with the MAC address
