# Road-Construction-Planning-and-Preventing-Obstruction


# Road Construction Using Highway Planning and Obstruction Prevention

### Table Of Contents

-  Abstract
-  Introduction
-  Project Requirements
-  Literature Survey
-  Block Diagram
-  Pseudo Code
-  Output Screentshot
-  Conclusion
-  References
-  Our Team


### 1. Abstract

The project titled ROAD CONSTRUCTION USING HIGHWAY PLANNING AND
OBSTRUCTION PREVENTION aims to address one of the major issues that the Indian
road construction department is facing. These days we notice that a large number of roads
are not in proper condition and many of them require restoration. Many of which are in
high usage and require immidiate repair. Our project aims to help athorities with
providing them the most profitable path for road contruction for a given map and the
sequence in which these roads can be addressed so that it would be convenient for both
the authorities as well as the general public.Our project collects various forms regarding
the map for the road that needs to be constructed, with this data we find the most shortest
and profitable path possible . Then we collect data for utility and traffic for all the roads
,then we normalize the data collected and generate a appropriate sequence in which the
road construction should be addressed. We have also included a deadline section so that
the roads that take more then the allocated time are highlighted and if necessary removed.
Also, a check for hindrance detection is added which can be used when we have limited
number of resources and a proper allocation of these resources is required. For this we
take inputs for resources which can refer to asphalt, machinery, mortar etc. Then we
require maximum resources needed for each road, amount of resources allotted for each
road, and available resources, based on which a safe sequence is generated that prevents
any unwanted stoppage of work.


### 2. Introduction

In countries like India where we are seeing a steep rise in the overall population there arise a
necessity of new habitat and scouring of vacant land to make new buildings, accommodations
and environments which are connected by roads. As per the statistics we get to know that a
total of 2098624 km of road was laid in India alone during the period 2001 to 2005 and these
numbers are continuously rising with each passing year. So the maintenance and construction
of new roads require a tremendous work force and attention from the government. So it
becomes necessary to design a proper algorithm that can manage the overall process of road
construction.

So the first part of the project deals with the task of getting the parameters through which a
road can be assigned a particular priority and accordingly can be used for further estimations
and calculations. So for this purpose we consider 3 parameters associated with a particular
road namely the size,utility and the traffic associated with each road . For the purpose of
getting the road size we employ yet another renowned and precise algorithm known as
djikstra algorithm to get the shortest road length

Scheduling is one of the most widely used techniques to using which any operation involving
several tasks can be ordered in such a way so that easy execution of the entire operation
becomes possible in the most efficient way possible avoiding any sort of errors and
confusions. The programme that does the task of scheduling is termed as a scheduler. Now
the scheduling used in the project involves priority scheduling without the use of pre-
emption(the reason for the same is explained in the later part of the project) ,So here the
algorithm decides how to schedule the various construction processes in the given region
based on their priorities , which in-turn is decided on the basis of various factors which are
mentioned in the above paragraph of the project. So all the constructions will be handled
accordingly.

In the second part of the proposed work, We tried to focus on the very common issue of delay
and stopping of the entire construction process due unavailability of various resources
involved in the construction process so we compared this scenario with the dead-lock
condition that arises in the operating systems while assigning resources to various running
processes and this lead us to use the same algorithm that we use in operating systems that is
the bankers algorithm for our project as well using various resources involved in the road
construction process so as to avoid any condition of an absolute deadlock state in our
construction process. The resources we use are discussed in later part of the project .So using
this bankers algorithm we make sure that at no situation should occur where for the lack of
required resources, all work gets stopped or hindered. So, the implementation of this
algorithm becomes necessary. The safe sequence advices in what order to proceed so that by
the available resources, all tasks can be completed.

### 3. Project Resource Requirement

- Software Requirements
  
    This project has been created using CODE BLOCKS
C Programming language has been used for the code

- Hardware Requirements

    Intel i3/i5/i7/i9

    Windows 7/8/8.1/10

    4 GB RAM

    4.0 GHz processor
  
### 4. Conclusion

The proposed model is highly recommended as it successfully implements all the ideas that
were initially put forth. The main purpose was to find out order in which a group of roads are
mended or constructed so that within short time and correct resources, the roads are dealt
with, without any ambiguity, prioritizing the important ones over the others. So in this way
we get an ideal sequence for a large set of construction processes ongoing in the entire
country which would not have been possible to deal with manually .The designed model is
also able to find the most profitable route for the road construction whose map was given to
us. By applying dijkstra algorithm to this map we were able to find the profitable route for
construction .The model is also able to checks the safe sequence based on the data available
to the authorities, whereby it says if the certain available resources is enough for the safe
mending of all the given roads.


Now we discuss that The reason to implement Priority Scheduling over the other methods is
to ensure that the correct purpose is met and solved. In the given scenario, using other
efficient algorithms like Shortest Job First is not feasible because the prior knowledge of
every parameter is not sometimes possible because continuous damage of various other roads
is possible in real life, and hence they will keep adding to the list making it impossible for
roads of higher priorities to get completed. Also, the interruption of a going on task and
resuming of others, while resuming the first one later is not possible in this scenario because
an important road cannot wait forever once mending it has been started. The traffic and utility
of that particular road does not allow it to wait for others. Hence, the best possible algorithm
for the implementation was Priority Scheduling.

