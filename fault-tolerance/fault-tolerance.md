!SLIDE bullets incremental

# Fault Tolerance #

* Ability to deal with hardware or software outages
* Easily bring service back online with no data loss
* Make services more robust to outages

!SLIDE bullets incremental

# Components of Fault Tolerance #

* Disk Storage (RAID / Clustered storage backends)
* Multiple Machine
* Network paths

!SLIDE center

# Xen Fault Tolerance #

![xen-fault](xen-infra-fault.png)

!SLIDE bullets incremental

# Xen fault tolerance #

* Disk nodes had no redundant system
* Lack of adequate management software
* Old hardware
* Difficult & Expensive to scale

!SLIDE center

# Ganeti fault tolerance #

![ganeti-fault](ganeti-infra-fault.png)

!SLIDE bullets incremental

# Ganeti fault tolerance #

* Each node has storage replicated using DRBD
* Centralized management software
* Newer hardware
* Very easy to scale
