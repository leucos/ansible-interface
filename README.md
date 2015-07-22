ansible-interfaces role
=======================

Debian style interface configuration

## Usage

    interfaces_v4:
      em1:
        type: static
        address: 10.0.0.1
        netmask: 255.255.0.0
        gateway: 10.0.255.254
    
      em2:
        type: dhcp
        mtu: 9000
    

Michel Blanc <mb@mbnet.fr>
