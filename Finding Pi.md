# Finding Pi

The RaspberryPi is only available at local net, so you need to be physically present
at the club (or connected via ssh to the dedicated server).

## Default IP
`192.168.0.3`

## If it fails...
The router is configured for assigning a static local IP to the RaspberryPi, if by
any chance the previous IP is not working, you can try finding its by one of this methods

### nmap

#### Installation
https://nmap.org/book/install.html

#### Usage
```
sudo nmap -sP 192.168.0.0/24 | grep B8:27:EB -B 2
```

The response will cotanin the IP along with the MAC address
