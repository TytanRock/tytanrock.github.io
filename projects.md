---
title: Projects
permalink: /projects
description: Various projects I've done
---

# School-Related Projects

## Research Project
<img src="/assets/images/projects/cohda.jfif" alt="Image of CohdaMK5" style="float:right">
I'm doing a research project with Dr. Yunsheng Wang from Kettering's CS Department. The research involves MK5 DSRC units and communication between them in a V2V (vehicle to vehicle) and V2X (vehicle to infrastructure) style.

I'm also working on edge node computing in vehicles as a means of offloading computation-intensive programs to a dedicated computer. I.E. Vision processing on a dedicated offboard processor to improve performance of automated vehicles.

## CS-203 Java and Algorithms III Projects
Java 3, CS-203, required some projects to be completed.
I cannot remember what I had to do in the class, as it was a year before I moved it into a Github Repo, however I wanted to add it to help others out if possible.
Repository is [here](https://github.com/TytanRock/CS-203-Assignments).

## CS-231 Programming Paradigms Projects
Programming Paradigms, CS-231, required multiple projects to be completed.
Those projects consisted of some C projects, and some Haskell projects.
Repository is [here](https://github.com/TytanRock/CS-231-Projects).

## CS-351 Cloud Computing Projects
Cloud Computing, CS-351, required some homework assignments to be completed.
They consisted of using Amazon Web Services to spin up EC2 instances and S3 buckets to process large quantities of data quickly.
Repository is [here](https://github.com/TytanRock/CS-351-CloudComputing)

## CS-451 Operating Systems Projects
Operating Systems, CS-451, required multiple low level C projects to be completed for class credit.
I have also taken on the added work of integrating Jenkins into every build of a project, to ensure I understand how Jenkins works and how to develop simple C unit tests.
Repository is [here](https://github.com/TytanRock/CS-451).

# Non-School Projects

## Home Server
I've set up a couple home servers to be used as network drives for computer backups for my family.

### Docker
I've set up a docker interface on one of the servers that allow me to deploy docker containers. I tend to prefer deploying docker containers for major applications such as jenkins to make the process simpler and controlled. I handle the containers using Portainer and a web interface.

### Jenkins

One of those major applications I use a docker container for is Jenkins. It's configured to look at my repositories and try to build them based on a Jenkinsfile that exists in them. I've utilized Jenkins in my CS 451 assignments to verify they pass verification tests, but not much beyond that.

<a href="https://www.jenkins.io/"><img src="/assets/images/projects/jenkins.png" alt="Image of Jenkins App" style="margin-left:20px;height:120px;width:100px;"></a>

### Visual Studio Code in Webpage interface
I'm also the programming mentor of a robotics team, where we use Java. The team members are assigned chromebooks from their school, which means they are unable to install and run visual studio code, the IDE we use to program in FRC. I've looked for solutions to this, and settled on [code-server](https://github.com/cdr/code-server), a visual studio code implementation in a web browser. I've configured the one that my team uses to have all the necessary WPI extensions, so that the students can focus on the programming aspect of the robot. It works pretty well, and using Git and Github, we're able to easily transfer changes from the server to a local machine for deployment.

### Minecraft Server
Of course, I have a minecraft server on the machine. I found out that there exists Minecraft docker containers, which are super fun because I can set up the container with rules to restart the server in case of a power outage. I currently run both a vanilla server using paper, and a FTB revelation server, neither of which are public.

## Embedded Systems
I'm interested in embedded systems, so I have a repo for the various projects I pick up and work on. I'll do things like connect a dsPic to an RFID reader, or to an lcd display and see if I can communicate with it successfully.
Repository is [here](https://github.com/TytanRock/DsPIC-Projects).

## Hacking and Penetration Testing
Recently, I've taken an interest in penetration testing and set up a kali machine to advance my understanding of it. I've been using the website [TryHackMe](https://tryhackme.com/) to learn various techniques and the tools used.
My profile is available under the same username, [here](https://tryhackme.com/p/TytanRock).

I've also begun work on a repository to increase my efficiency, developing tools that I find useful. It's kind of like metasploit, but tailored to what I'm doing, that repository is available [here](https://github.com/TytanRock/kali-scripts).

<script src="https://tryhackme.com/badge/39868"></script>

## CAD-Work
### Inventor and Onshape
I am familiar with Autodesk Inventor and Onshape for 3d CAD software, where I have designed a chess set using Inventor, and a [3d Model](https://cad.onshape.com/documents/89701ed42737cd73d5f612e3/w/dba0564388030888f467bf9d/e/9a8574c201287417260c4710) of the board game [Settlers of Catan](https://www.catan.com/) using Onshape, among other various items.

I have printed out the chess set and the settlers of catan board game using a personal 3d printer, using ABS and PLA filament respectively.

<a href="https://cad.onshape.com/documents/89701ed42737cd73d5f612e3/w/dba0564388030888f467bf9d/e/9a8574c201287417260c4710"> <img src="/assets/images/projects/SettlersOfCatan.png" alt="Image of Settlers of Catan CAD"> </a>

### Eagle
I am also familiar with Autodesk Eagle. The biggest project for this would be my PCB that converts game arcades to retropie arcades. The PCB itself is simple but includes rerouting a 20pin header and a simple audio amplifier to utilize the built in speakers for the arcade. Available [here](https://github.com/TytanRock/Eagle-Projects).

<img src="/assets/images/projects/eagle.png" alt="Image of Eagle CAD">
<img src="/assets/images/projects/board.png" alt="Image of Assembled board" style="width:600px;height:400px;">
