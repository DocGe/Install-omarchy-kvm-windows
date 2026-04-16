Trouver clé oem
```
sudo strings /sys/firmware/acpi/tables/MSDM
```

Activer réseau
```
/etc/libvirt/network.conf

# default: #firewall_backend = "nftables"
firewall_backend = "iptables"
```
