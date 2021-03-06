.. _vyosonbaremetal:

Appendix D - Running on Bare Metal
##################################

I opted to get one of the new Intel Atom C3000 CPUs to spawn VyOS on it.
Running VyOS on an UEFI only device is supported as of VyOS release 1.2.

Shopping Card
-------------

* 1x Supermicro CSE-505-203B (19" 1U chassis, inkl. 200W PSU)
* 1x Supermicro MCP-260-00085-0B (I/O Shield for A2SDi-2C-HLN4F)
* 1x Supermicro A2SDi-2C-HLN4F (Intel Atom C3338, 2C/2T, 4MB cache, Quad LAN with
  Intel C3000 SoC 1GbE)
* 1x Crucial CT4G4DFS824A (4GB DDR4 RAM 2400 MT/s, PC4-19200)
* 1x SanDisk Ultra Fit 32GB (USB-A 3.0 SDCZ43-032G-G46 mass storage for OS)
* 1x Supermicro MCP-320-81302-0B (optional FAN tray)

Optional (10GE)
---------------
If you wan't to get additional ethernet ports or even 10GE connectivity
the following optional parts will be required:

* 1x Supermicro RSC-RR1U-E8 (Riser Card)
* 1x Supermicro MCP-120-00063-0N (Riser Card Bracket)

Latest VyOS rolling releases boot without any problem on this board. You also
receive a nice IPMI interface realized with an ASPEED AST2400 BMC (no information
about [OpenBMC](https://www.openbmc.org/)) so far on this motherboard.

Pictures
--------

.. figure:: /_static/images/1u_vyos_back.jpg
   :scale: 25 %
   :alt: CSE-505-203B Back

.. figure:: /_static/images/1u_vyos_front.jpg
   :scale: 25 %
   :alt: CSE-505-203B Front

.. figure:: /_static/images/1u_vyos_front_open_1.jpg
   :scale: 25 %
   :alt: CSE-505-203B Open 1

.. figure:: /_static/images/1u_vyos_front_open_2.jpg
   :scale: 25 %
   :alt: CSE-505-203B Open 2

.. figure:: /_static/images/1u_vyos_front_open_3.jpg
   :scale: 25 %
   :alt: CSE-505-203B Open 3

.. figure:: /_static/images/1u_vyos_front_10ge_open_1.jpg
   :scale: 25 %
   :alt: CSE-505-203B w/ 10GE Open 1

.. figure:: /_static/images/1u_vyos_front_10ge_open_2.jpg
   :scale: 25 %
   :alt: CSE-505-203B w/ 10GE Open 2

.. figure:: /_static/images/1u_vyos_front_10ge_open_3.jpg
   :scale: 25 %
   :alt: CSE-505-203B w/ 10GE Open 3

.. figure:: /_static/images/1u_vyos_front_10ge_open_4.jpg
   :scale: 25 %
   :alt: CSE-505-203B w/ 10GE Open 
