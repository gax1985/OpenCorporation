


Please permit me to use the **Writer's Guild** as a model for demonstation purposes :



#### The User Experience 


The operating system itself would host the writer's editor, It would enable the writer to write this work of art, and at the same time providing the computing power for other writers to write, and aspiring writers to learn the craft. The way this could be done is with creating a **Docker Cluster** or a **Kubernetes Cluster**. The operating system that the user actually interacts with would contained in a **Docker Container**!

This formula provides the element of *layering*, in which we would strive to insure everyone's utmost security, and practice effective utilization of computing resources (to cut down on the damage that is done every day to our beautiful planet : ). 

So , to simplify : 


The *hypervisor*  would run *Docker/Kubernetes Containers* which contain the *graphical user interface* that the writer would use to create their work of art!


I have done a lot of research in my aim to find the right graphical user interface for the operating system that is fun to use and light on resources, and I found that the **Linux-based Window Managers** fit the bill, as they are extremely light-weight and *endlessly customizable* ( which would be our bread and butter!)




So to demonstrate : 



##### Hyprland 


I have found the following screenshots on Hyprland's website ([Hyprland](https://hyprland.org/)), in which the makers hosted *ricing contests (it refers to the Art of Customizing Window Managers)* : 


![[Pasted image 20240304202515.png]]



![[Pasted image 20240304202637.png]]



![[Pasted image 20240304202717.png]]



Please feel free to check out their wonderful works of art at the following link : 


[Hall of Fame (hyprland.org)](https://hyprland.org/hall_of_fame/)



#### The Operating System (*which runs the User Interface*)



I am really excited to recommend a Linux distribution that is truly mindblowing in its potential, where one can configure the operating system from one file ( or more if more complexity/resourcefulness is desired), save the configuration file, and then install the operating system on another machine and re-create the user experience that they normally use while retaining all the desired applications! 


It helps a *ton* to be able to restore to a previous generation if disaster strikes! Thankfully, NixOS does!


Due to its highly-configurable nature, we can create configurations for operating systems used by the different *guilds*, in which we would work with the creators directly to come up with the best configuration possible for them. Configuration files can be edited as needed, and the changes would be pushed to the desired container on a routine basis. 


The **Operating System** should be prepared in a way that can be run on almost any device out there in the wild. We know that we can not guarantee that it would run, due to the differences in processors, the processor's architecture, the availability of drivers and so on. Since the majority of computer systems are running Microsoft Windows, I thought the following formulations should be made to provide a wider *availability* : 

##### 1. A WSL2 Container (for **Microsoft Windows**)

>[!howto]
>
>1. We would create a **NixOS-Based WSL2 Container**. 
>2. In the **WSL2 Container**, we would install [[[Kubernetes](https://kubernetes.io/)|Kubernetes]] to it, and configure it that it would be added to the container's configuration file via the steps mentioned in the following link : 
>   [[[Kubernetes - NixOS Wiki](https://nixos.wiki/wiki/Kubernetes)]]

>[!note]
>
>We could install the **Nix Package Manager** to a pre-existing *WSL2 Container* , or we can use [[[elitak/nixos-infect: [GPLv3+] install nixos over the existing OS in a DigitalOcean droplet (and others with minor modifications) (github.com)](https://github.com/elitak/nixos-infect)|nixos-infect]] to install NixOS on non-NixOS-based systems! 


##### 2. A Bare Metal NixOS-based Distribution


This option would provide the means to run our operating system on bare-metal ( which means it can be installed directly unto a hard-drive, USB Flash Drive) or to run it in a virtual machine. The latter option would be tremendously helpful at the design stage, as we would simulate different configurations ( in terms of virtualized hardware) to mimic realistic usage scenarios ( such as developing the operating system to run on Android devices for example). 

##### 2. A NixOS-based Distribution (running virtually on iPhone/iPad)


Apple's mobile devices would be a bit more challenging, as the only hypervisor that worked on iOS and iPad OS devices is [UTM](https://getutm.app/). Nonetheless,  if we examine the portion of the [Documentation]([iOS | UTM Documentation (getutm.app)](https://docs.getutm.app/installation/ios/)) involving the installation of the hypervisor unto an iOS/iPadOS device, the steps are far too daunting for us without the technological know-how and means to jailbreak their device.


##### 2. A NixOS-based Distribution (running virtually on MacOS)


Running the hypervisor on a MacOS-based device would be far easier than its mobile counterparts ( due to the mentioned reasons). 






## The Cluster


Since this idea stems of the shared computing power from all the participants in the organization, we would have to come up with different options to make the **Cluster** a reality. After a lot of research, I thought the following options are available to do so : 






























Let us proceed to [[Writers' Guild]], so we can see a manifestation of **Open Corporation**! 






