## Networking concept and OSI layering

Ok, so we have already mentioned that the Internet is a computer network, but what is a **network**? Well, as in discrete mathematics, here we have to go back to graph theory, that is, the theory that studies mathematical structures used to model relations between objects, through sets of vertices and edges. For instance, the figure below is a graph.

![img](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/6n-graf.svg/220px-6n-graf.svg.png)

A computer network is an application of a graph in the computer science context. 

Let us consider, for sake of simplicity, our home, where we might have an Internet connection and a set of machines connected to it. For instance, if we have three machines connected to our access point (the machine providing us with Internet access), then we have a graph with four vertices and three edges, connected as depicted below.

[image of a three-way graph]

This computer network is made out of two different types of equipment: three computers, and an access point, which we will initially consider as a router. A **router** is a network equipment able to manage routes to what enters and exits it, similarly to a receptionist in a university, diverting people via specific paths regarding their pretended destinations to take classes.

[image of a student questioning a receptionist lady on how to go to his classroom]

These actions of routing entering “objects” to different destinations could also be made by a common computer machine, but as the number of objects being processed could achieve a very high order of magnitude, specific equipment is way better recommended to be used—that’s why we use routers. So routers do not need to be able to do everything in the network—they do have to be able to route the “objects”.

Let’s now talk a bit about these “objects”—they are named **packets**, and they are units of data passing from machine to machine, within or between different networks. Such packets represent meaningful data or parts of a larger object which meaning is solely understandable by its source and destination endpoints. In the next chapter we will explore more in depth how these packets are created and which information is contained in them.

