# Pilot Structure

Per our chat on 12/21 we need 32 lessons grouped into 8 weeks/units. A lesson
would be 60 mins of lecture that fades in 30 mins of lab time with structured
scenarios to reinforce learning.  We’d also have a 30 mins or so Snack and Talk
session between the lessons that we can use to bring in folks to talk, or
address socializing/networking issues, etc. 

### Lesson 1 of the day

    [ 60m lecture                           ]  
    [ 30m lab          ] [ 30m snack & talk ]

### Lesson 2

    [ 60m lecture                           ]  
    [ 30m lab          ] [ 30m snack & talk ]

# Example Curriculum

A typical devops project is setting up and deploying applications onto
workstation, development, and production environments, while scaling
storage/compute with automation as much as possible. 

In this example curriculum, we use a web server to show the outline of
that typical devops project.

* Week 1: Compute node overview using local host, vagrant, and mobile devices
* Week 2: Compute environments using Amazon Web Services
* Week 3: Storing data using databases and file services
* Week 4: Setting up an application
* Week 5: Deploying applications
* Week 6: Scaling storage with EBS, LVM, S3
* Week 7: Scaling compute with ELB, haproxy
* Week 8: Automate as much as possible

## Week 1: Compute node overview

Students explore what makes a server and how servers interact in a local
network.  This unit establishes the concepts such as services, file,
process, node, addressing that will be reinforced in later units.

The concrete project is setting up a web server for pictures and web
pages.  By the end of the unit, students will set up web servers for
each other as well as themselves, and manage web content using images
and folders.

### Day 1.1: 

Establish basic concepts of what is a server, and how they are already
using advanced computers on their phones, tablets, and media centers.

  * Explore OS X on their workstations
  * Explore iOS/Android on their phones, tablets, media centers

### Day 1.2: 

Extend basic server concepts from OS X/iOS/Android to Ubuntu using a
local virtual machine.  Able to serve images using local storage.

  * Explore Ubuntu in VirtualBox vagrants with a web server

### Day 2.3: 

Extend local web server to networked servers.  Students can visit not
only their local web servers, they visit each other's web servers.

  * Explore networking with OS X workstations and Ubuntu web servers

### Day 2.4: 

Do remote work on partner workstations.  Show there's not much
difference between remote work in a vagrant and in a remote workstation.

  * Set up more Ubuntu web servers on partner's workstations
