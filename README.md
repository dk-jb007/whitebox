### whitebox

A low cost hardware based switch based on off the shelf components that is capable of running a 3rdparty operating system over a Linux foundation. All white boxes consist of four basic modules:

* Power Supply Unit
* Board Management Controller (manages environmentals)
* Microsever (routing protocols, management, UI)
* Switching ASIC (forwarding functions, Broadcom being the major supplier)

![Flow Diagram](Images/Basic.png)

### In order to understand further, lets discuss first, **what is disaggregation?**
* decoupling of network hardware with network operating system
* gives customer a choice to choose network hardware and the NOS that is best suited for their application ennvironment
 

### Does IOS-XR run on third party devices?
Yes, IOS-XR7 runs on severalcertified whiteboxes;the Edgecore AS-5916 and AS-7816. [[Click me](https://xrdocs.io/cloud-scale-networking/blogs/2018-03-08-enabling-ios-xr-on-third-party-network-hardware/)]


### What skills do I need to support whiteboxes?
1. XR software configuration and troubleshooting (LNT XR)
2. Whitebox Architecture -Understanding and working knowledge of router/switch hw architecturesCPU, PSU, ASICs etc
3. Working knowledge of Linux and Linux tools, particularly [ONL](http://opennetlinux.org/)
4. Docker for Docker base installationsof XRon whitebox
5. ONIE -Open Network Install Environment

#### Additional desirable skills
1. Knowledge of the [open compute project](https://www.opencompute.org/)
2. Ansible
3. Python, REST
4. DEVNET, Netconf, Restconf, Yang, NSO





