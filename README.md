|  MEC Middlebox Solution
----------------------

We propose a middlebox approach for the MEC platform deployment in 4G LTE networks.
It is standard-compliant and transparent to existing cellular network components, so 
they need not be modified. The platform sits on the S1 interface, which connects an LTE base 
station to its core network, and does traffic filtering, manipulation and forwarding.
Such middlebox approach has low deployment cost and is easy to install. 
We have confirmed its viability on both OAI-based and commercial LTE platforms.
Please give it a try!!


![](https://i.imgur.com/ONV9mB5.png) 




  Getting Started
  _____________________
  
  This release demonstrates how to set up the MEC-middlebox platform and run it 
  with a release version of the OAI platform comprising both radio access network (RAN)
  and evolved packet core (EPC).


## Step 1: Download and install OAI RAN and EPC

   Download OAI source and installation guide here.
   
   [OAI Guide From Official](https://gitlab.eurecom.fr/oai/openairinterface5g/wikis/AutoBuild)
  
   
	Note:
	We use the following development branches for EPC and RAN.
  - EPC: SHA = 724542d0b59797b010af8c5df15af7f669c1e838
  - RAN: SHA = 67df8e0e7b46200b2ee43a2705def3340ddfd719



## Step 2: Download and install MEC-middlebox
   
   Download MEC-middlebox source here.
   
   [Source here](https://github.com/nemslab-nctu/MEC-Middlebox)


## Step 3: Configure your MEC platform

   Please fill in the following information and submit it.
   A link will be sent to you to download the configuration guide soon.
 
   [Fill info here](http://nems.cs.nctu.edu.tw/release/)





## License
All code found in this repository is licensed under GPLv3
```  
    Copyright 2018-2020 NEtworking and Mobile Systems Lab, NCTU

    This file is part of MEC-Middlebox.

    MEC-Middlebox is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    MEC-Middlebox is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with MEC-Middlebox. If not, see <https://www.gnu.org/licenses/>.
```

 Contact Us
  _____________________

  You are very welcome to report bugs, ask questions, or/and request supports.
  If there are any, please contact us via nems@g2.nctu.edu.tw.