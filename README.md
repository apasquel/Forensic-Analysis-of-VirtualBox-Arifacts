# Forensic-Analysis-of-VirtualBox-Arifacts
This is way of publizing my research manuscript titled Forensic Analysis of VirtualBox Artifacts. The idea was to answer the question: "How can a Digital Forensic Analyst investigate a VirtualBox VM found during an investigation?". As the paper explains, typically VirtualBox VMs are popular with script kiddies and potentially more advanced actors. Therefore, an analyst will need to know how to investigated INTO the guest OS. 

This work was completed during my studies at Bloomsburg University of Pennsylvania (now called Commonwealth University of Pennsylvania-- a merger). I could not have done this work without them. 

# Abstract

Virtualization technology is the process of dividing up physical hardware into separate virtual pieces. We focus on a particular virtualization technique: A Virtual Machine (VM). These VMs are often simple, easy, and free to set up on a local machine. A popular method of using localized VMs is using a level II hypervisor such as Oracle’s VirtualBox. Our purpose is to detail VirtualBox forensic artifacts so that investigators and responders can use them in their work when the VM’s resources and internal storage are in question. This paper outlines three main forensic artifacts: (1) The VirtualBox Log Structure, (2) The Virtual Disk Image (VDI) Header, (3) Snapshot UUIDs and Snapshot Forensic Methods. These artifacts allow the possibility to recover data held within the VM’s resources.

I hope you enjoy reading my paper! 

~Austin Pasquel
