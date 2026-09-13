auto enp0s3
iface enp0s3 inet static
    address 10.0.2.15/24
    gateway 10.0.2.2
    dns-nameservers 10.0.2.3

auto enp0s3.10
iface enp0s3.10 inet static
    address 10.0.10.1/24
    vlan-raw-device enp0s3

auto enp0s3.20
iface enp0s3.20 inet static
    address 10.0.20.1/24
    vlan-raw-device enp0s3

auto enp0s8
iface enp0s8 inet static
    address 192.168.56.10/24
