<img class="slide-img" src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.znetlive.com%2Fblog%2Fwp-content%2Fuploads%2F2016%2F06%2Fvirtual-cloud.jpg&f=1&nofb=1" />

## Virtualization Workshop

---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/v26zyfd6yf0r33s46vpe.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

# WELCOME!

---


<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/52vy4yxt8yw76d2u8dsm.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->


# Volunteer Introductions

----
<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/l2bjw34wnusyf5q2qq3p.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->


# Nader Rais

* Your facilitator!
* Graduate at 2021 from ESPRIT School og engineering Tunisia
  * BA Computer Science, Minor in Mathematics
* Worked as a System Administrator, QA Analyst, Software Engineer, Full Stack Instructor
* I am currently a Senior Developer at codinggame

----

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/ts1p4x68ezcwbofpgaw2.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

## Expectations

<div class="dark-bg">
  <ul>
  <li>Be respectful of your classmates and volunteers.
    <ul>
      <li>Do not talk over each other.</li>
      <li>Respect each others space.</li>
    </ul>
  <li>Help each other! Use each other as a resource.</li>
    <ul>
      <li>Teaching is learning.</li>
    </ul>
  <li>Mistakes are OK. Mistakes mean you're learning.</li>
  <li>Have fun!</li>
  </ul>
</div>


---


<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/9ewm8485k5auk0rhn0go.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->


# Overview

----

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/8t2s8jw1zcb9iyvd8hwe.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

## Cloud Computing 

* Introduction of Virtualization
* 
* Cloud Consumers diffrences


---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/wja6g3w9ebwj6cw753eg.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

# Virtualization in CLoud Computing

---

# what is virtualization ? 

----

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/ypy8bw9fgw1zv2b4htp2.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

Virtualization is the "creation of a virtual (rather than actual) version of something, such as a server, a desktop, a storage device, an operating system or network resources".

In other words, Virtualization is a technique, which allows to share a single physical instance of a resource or an application among multiple customers and organizations. It does by assigning a logical name to a physical storage and providing a pointer to that physical resource when demanded.

----
<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/krqazc6jzd3b2893tefg.tablet.mp4" data-background-video-loop="loop" data-background-video-muted -->

## What is the concept behind the Virtualization

Creation of a virtual machine over existing operating system and hardware is known as Hardware Virtualization. A Virtual machine provides an environment that is logically separated from the underlying hardware.

> The machine on which the virtual machine is going to create is known as Host Machine and that virtual machine is referred as a Guest Machine 

---

## Types of Virtualization

1. Hardware Virtualization.
2. Operating system Virtualization.
3. Server Virtualization.
4. Storage Virtualization.

---

#### How does virtualization work in cloud computing?

Virtualization plays a very important role in the cloud computing technology, normally in the cloud computing, users share the data present in the clouds like application etc, but actually with the help of virtualization users shares the Infrastructure.

The main usage of Virtualization Technology is to provide the applications with the standard versions to their cloud users, suppose if the next version of that application is released, then cloud provider has to provide the latest version to their cloud users and practically it is possible because it is more expensive.

To overcome this problem we use basically virtualization technology, By using virtualization, all severs and the software application which are required by other cloud providers are maintained by the third party people, and the cloud providers has to pay the money on monthly or annual basis.
---

# Virtualization Challenges 

----

## Depleted resources—performance and availability suffer
Performance issues—often created by a move from physical hardware to virtual hardware—and VM saturation cause application networking resources to be depleted at a much faster rate.

----
## Lack of application awareness— OS virtualization doesn’t virtualize the application
Virtual infrastructure platforms include software that can migrate running VM instances from one physical device, which often causes a lapse in app availability.

----
## Additional, unanticipated costs—the virtual solution costs more than the physical problem
Additional costs often result from implementing OS virtualization; new hardware and software licenses can be required to solve problems with availability, performance, and management.
----
## Unused virtualization features—the network limits implementation
New virtual platforms include many advanced networking technologies, such as software switching and support for VLAN segmentation; however these features are localized and isolated to the VM platforms. They are not integrated with the rest of the Application Delivery Network because there is no sharing of information between VMware and the network.
----
## Overrun storage network—growth exceeds planning
OS and data files that typically reside on internal storage in physical server environments are moved to shared storage in virtual environments. OS drives are converted to fl at-file virtual machine disks (VMDKs), which take up 10-100s of GBs each of networked storage. Little used or inactive VMDKs can remain on expensive storage well after they are needed, driving up storage costs.
----
## Congested storage network—data pipes can’t handle the volume
OS virtualization can dramatically increase data storage traffi c, and passing large amounts of data from multiple guests through one host storage network connection, such as NFS, can cause instant bottlenecks, flooding, and congestion.
----
## Management complexity—management tools don’t work together
Managing VMs as part of the complete management solution can be a struggle. This includes managing the VMs themselves as well as managing all parts of the data center as one delivery unit.

---
# Virtualization Security :
----
### Intro : 
As virtualization components increase and the virtualized environment expands, the main concern becomes how to maintain safe levels of security and integrity of the system. 

---- 
## Security challenges and risks due to virtualization
----
* Sharing of files between Hosts and Guests
A compromised guest can remotely access a host file, modify, and/or make changes when a file-sharing is used. The malicious guest may modify directories used to transfer files.
----
* Administrator access and separation of duties
In a virtualized environment, however, network and server management can both be delegated from the same management platform. This provides a novel challenge for the separation of duties that will effectively work.  In most cases, virtualization systems grant full access to all virtual infrastructure activities.
---
# Virtualization common attacks
----
### Denial of Service Attack (DoS)
In case of a successful denial of service attack here, hypervisors are likely to be completely shut down and a backdoor created by the black hats to access the system at their will.
----
### Host Traffic Interception
Loopholes or weakness points present in the hypervisor can allow for tracking of files, paging, system calls, monitoring memory and tracking disk activities.
----
### VM Jumping
If a security vulnerability such as a hole exists in a supervisor, a user can almost seamlessly hop over from one VM to the other. Unauthorized users from a different VM can then manipulate or steal valuable information.


---
<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/sx0p5v9at3ucuaz9e0z7.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

# Conclusion 

---

* Mainly Virtualization means, running multiple operating systems on a single machine but sharing all the hardware resources. And it helps us to provide the pool of IT resources so that we can share these IT resources in order get benefits in the business.
---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/oaahb8d8i5t768wlkg5i.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->

# Stay Safe ,
# Stay Home , 
# Wash your Hands !
## Have a good Sleep 😴 !
---

<!-- .slide: data-background-video="https://cdn.flixel.com/flixel/rxfubz1e9pzn8lqf5su1.hd.mp4" data-background-video-loop="loop" data-background-video-muted -->
## Thank You For Your Attention!
