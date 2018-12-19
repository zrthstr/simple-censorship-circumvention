# Simple censorship circumvention

This project aims to provide a robust set of tools to effortless regain free internet access when surfing from dark corners of the internet.

This implies fully automated setup of diverse proxys, vpns, tunnels and bridges on cheap cloud providers.


## Scope
* Deal with the censorship in central-alsia, iran, turkey, china.
* Increase the effort need for eavesdropping.
* Minimizing exposure to legal threats for example caused by filesharing under a german IP.



## Overvidew of Methods

Have and spectrum of uninterupted channel to either TOR, I2P, or to any cloud provider.
```


                                    .-~~~-.
                            .- ~ ~-(       )_ _
                           /                     ~ -.
                          |      The Internet         \
                           \                         .'
                             ~- . _____________ . -~


   +---------+    +---------+                        +---------------------+
   |         |    |         |                      +---------------------+ |
   |   I2P   |    |   Tor   |                    +---------------------+ | +
   |         |    |         |                    | Random Cloud Hosting| +
   +----+----+    +----+----+                    +--------+------+-----+
        |              |                                  |      |
        |              |                                  |      |
        |              |      +=================+         +---+--+
        |              |      | Some Oppressive |             |
        |              |      |    Firewall     |             |
        |              |      +=================+             |
        |              |                                      | 
        |              |                                      |
        |              |   +------------------------+         |
        |              |   |    Obfuscation layer   |         |
        |              +---+ bridges, proxys & VPNs +---------+
        +------------------+(meek, obfs4, wireguard)|
                           +-----------+------------+
                                       |
                                       |
                              .________|________.
                              |.---------------.|
                              +|               |+
                              ||               ||
                              ||      You      ||
                              ||               ||
                              ||               ||
                              ||_______________||
                              /.-.-.-.-.-.-.-.-.\
                             /.-.-.-.-.-.-.-.-.-.\
                            /.-.-.-.-.-.-.-.-.-.-.\
                           /______/__________\___o_\
                           \_______________________/


```


## Tools
### setup
Ansible, terraform, packer, vault, cloud-init


### OS
archlinux, debian


### Networking
wireguards, meek, obfs4, tor, i2p, ssh


### DNS provider
namecheap


### Integrated Cloud providers
scaleway


### Cloud providers up next
hetzner/hcloud, ...

