## UAV State of Affairs

### The idea behind this repo

The idea behind this repo is to feed some of the West Balkan's
UAV R&D engineers with the information they DESPERATELY tried to
obtain from me (Y2010 up to nowadays). I have some obligations
to keep some sensitive data at least for 20Y, but anyway, these
days the UAV R&D went far fast forward from the Stone Ages of
UAVs (in the 1980s and 1990s).

### Bit of History

Remember, the first very primitive UAVs were invented by Nazi
Germany in late 1930s/beginning of 1940s.

They were called V1, or FAU1 (German spelling of letter V):

* [V-1 flying bomb](https://en.wikipedia.org/wiki/V-1_flying_bomb)

[OFF Topic] Saturn V is a retired American super heavy-lift launch
vehicle developed by NASA under the Apollo program. Some people
call Saturn V as Saturn 5. Some: Saturn Fau (developed from V2
(Fau zwei).

### Tomahawk inspiration

Many of private companies, as well as military ones were mortally
hypnotised/inspired with Tomahawk design from late 1990s, and the
efficiency!

Since then, many HW and SW improvement were done to such kind of
UAVs, especially in the HW VLSI fields (the silicon gate become
to be very thin (14nm - 10nm), allowing very complex silicons
(mainly SOCs) to be developed and manufactured.

Also the different controllers, especially gyroscopes and cameras
were invented: 3D gyroscopes, ADIRUs, as well as LIDAR technology,
allowing much more precise and far richer feature set.

Talking NOT only about Tomahawk missile, but also about modern
UAVs, driven by AI (Artificial Intelligence), which uses Learning
Algorithms based upon Neural Networks (with 10 of millions of
neural reconfigurable nodes (given ULSI HW), each node with given
specific logic).

* [Tomahawk missile](https://en.wikipedia.org/wiki/Tomahawk_(missile))
* [BGM-109 Tomahawk](https://de.wikipedia.org/wiki/BGM-109_Tomahawk)

### State of Affairs, Present Time

I decided to do for free some google search/investigation and
deliver for anyone/groups who is/are interested in UAV papers,
articles and high level algorithms, www pointers to very complex
flight controller databases/repos, which are serving as an
useful codebase resources for the drone flight controller
subsystem implementation.

Algorithms posted for free to boost the Development and
Research (R&D) in the area of UAVs (Unmanned Areal Vehicles).

This I plan to do as a roling repo update (as Time allotted and
opportunities allow).

Here are the base pointers to these documents (author's choice).
Some of the documents in .pdf formats are posted in the same
directory as this README.md document.

### US companies, involved in such a complete (A-Z) AI drones' R&D

#### Boeing
* [Boeing](https://www.boeing.com/)

#### General_Atomics
* [General_Atomics](https://www.ga.com)

#### Lockheed Martin
* [Lockheed Martin](https://www.lockheedmartin.com)

#### Northrop Grumman
* [Northrop Grumman](https://www.northropgrumman.com)

#### Raytheon (Tomahawk)
* [Raytheon (Tomahawk)](https://www.rtx.com/raytheon)

### Theorethical Algorithms

#### How to Stabilize Drone Footage?
* [How to Stabilize Drone Footage](https://dronesurveyservices.com/how-do-you-stabilize-drone-footage/)

#### Improved Bat Algorithm for UAV Path Planning in Three-Dimensional Space
* [Improved Bat Algorithm for UAV Path Planning](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9334996)

This paper describes the flight path planning for unmanned aerial
vehicles (UAVs) based on the advanced swarm optimization algorithm
of the bat algorithm (BA) in a static environment. The main purpose
of this work is that the UAVs can obtain an accident-free, shorter,
and safer flight path between the starting point and the endpoint
in the complex three-dimensional battlefield environment. Based on
the characteristics of the standard BA and the artificial bee
colony algorithm (ABC), a new modification of the BA algorithm is
proposed in this work, namely, the improved bat algorithm
integrated into the ABC algorithm (IBA). The IBA mainly uses ABC
to modify the BA and solves the problem of poor local search
ability of the BA.
* [Improved Bat Algorithm for UAV Path Planning in Three-Dimensional_Space](https://github.com/ZoranStojsavljevic/UAV_State_of_Affairs/blob/main/Publications/Improved_Bat_Algorithm_for_UAV_Path_Planning_in_Three-Dimensional_Space.pdf)

#### UAV Formation Trajectory Planning Algorithms: A Review
* [UAV Formation Trajectory Planning Algorithms: A Review](https://www.mdpi.com/2504-446X/7/1/62)

This paper explains heuristic algorithms, machine learning
methodology, multi-UAV formation algorithms and trajectory
planning.

As to have further understanding, the paper tries to explain
Artificial Intelligence (AI) using all the above techniques.
* [UAV Formation Trajectory Planning Algorithms](https://github.com/ZoranStojsavljevic/UAV_State_of_Affairs/blob/main/Publications/UAV_Formation_Trajectory_Planning_Algorithms.pdf)

#### Three dimensional stabilization controller
* [Three dimensional stabilization controller](https://www.sciencedirect.com/science/article/abs/pii/S0019057821005565)

Three dimensional stabilization controller based on improved
quaternion transformation for fixed-wing UAVs.

#### A method for stabilization of drone flight controlled by autopilot with time delay
* [A method for stabilization of drone flight controlled by autopilot with time delay](https://link.springer.com/article/10.1007/s42452-020-1962-6)

In this paper, the methods of the stability theory of differential
equations with time delays are used in the study of an actual
engineering problem of a drone (UAV) autonomous flight. We describe
correct operation of autopilot for supply stability of desirable
drone flight. There exists a noticeable delay in getting
information about position and orientation of a drone to autopilot
in the presence of vision-based navigation (visual navigation). In
spite of this fact, we demonstrate that it is possible to provide
stable flight at a constant height in a vertical plane. We describe
how to form relevant controlling signal for autopilot in the case
of the navigation information delay and provide control parameters
for particular case of flight.
* [drone flight stabilization controlled by autopilot with time delay](https://github.com/ZoranStojsavljevic/UAV_State_of_Affairs/blob/main/Publications/drone_flight_stabilization_controlled_by_autopilot_with_time_delay.pdf)

### UAV development repos/sites

#### Open Source Autopilot for Drone Developers
* [Open Source Autopilot for Drone Developers](https://px4.io/)

This is the Open Source repo for the autopilot development.

It is mainly driven by Swiss company called Auterion:
* [Auterion](https://auterion.com/)

On github:
* [PX4 Autopilot](https://github.com/PX4/PX4-Autopilot)

Overall PX4 github repos' search:
* [PX4 github repos' search](https://github.com/search?q=px4&type=repositories)

#### The open standards for drone hardware: Pixhawk
* [Pixhawk](https://pixhawk.org/)

For Building Flight Controller Products Pixhawk Autopilot
Reference Standard:
* [autopilot](https://pixhawk.org/standards/#autopilot)

On github:
* [Pixhawk Standards](https://github.com/pixhawk/Pixhawk-Standards)
* [Pixhawk Hardware](https://github.com/pixhawk/Hardware)

#### MAVLink Developer Guide
* [MAVLink](https://mavlink.io/en/)

MAVLink is a very lightweight messaging protocol for communicating
with drones (and between onboard drone components).

#### Beagle Bone nano UAV Drone Project
* [Beagle Bone nano UAV Drone Project](https://www.beagleboard.org/projects/uav-drone-project)

### Real Work Done on the Drone Architecture
* [Real Work Done on the Drone Architecture](https://github.com/ZoranStojsavljevic/UAV_State_of_Affairs/tree/main/Pixhawk_Hardware_Architecture)

### Conclusion

I spent some few days of my time to get these, so I guess, these
are destined to whom it may concern!

About Boeing MQ-2X and such of Life wonders/beauties! Please,
address the concerns to the Boeing corporation:
* [Boeing MQ-28](https://en.wikipedia.org/wiki/Boeing_MQ-28_Ghost_Bat)

Ghost Bat Is An Aircraft Like No Other:
* [Ghost Bat video](https://www.youtube.com/watch?v=rxJQLI_OEnk)

About Reaper MQ-9 and such of Life wonders/beauties! Please,
address the concerns to the General Atomics corporation:
* [Reaper MQ-9](https://de.wikipedia.org/wiki/General_Atomics_MQ-9#Bewaffnung_MQ-9A)

How Air Force Drone Pilots "Fly" The $32 Million MQ-9 Reaper:
* [How Air Force Drone Pilots "Fly" MQ-9 Reaper](https://www.youtube.com/watch?v=7kQAnhET0ec)

About MQ-8 and such of Life wonders/beauties! Please, address the
concerns to the Northrop Grumman corporation:
* [Northrop_Grumman_MQ-8](https://de.wikipedia.org/wiki/Northrop_Grumman_MQ-8)

About RQ-170_Sentinel (one captured by Iran), please, address the
concerns to the Lockheed Martin corporation:
* [Lockheed Martin RQ-170 Sentinel](https://en.wikipedia.org/wiki/Lockheed_Martin_RQ-170_Sentinel)

Many thanks for reading and understanding,

Author
