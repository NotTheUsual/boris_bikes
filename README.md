# Boris Bikes

This is the Week 3 Project for Makers Academy. The task was to create a model of a system for tracking loan bikes (much like London's Barclays Cycle Hire). There's no interface for using it, but you can directly manipulate everything in irb, if you feel like it.

So, everything starts with a Bike. I bike knows whether or not it's broken, and can be fixed. Then we have a series of Bike Containers. Bike Containers have bike storage of a certain capacity, the ability to dock and release bikes, and also to return information such as the number of bikes docked, and which bikes are available or not. A Docking Station is just a simple Bike Container. A Van is a Bike Container with the additional abilities to load all the broken bikes from a docking station, load all the fixed bikes from a garage and unload as many bikes as possible into either a docking station or a garage. A garage is just a Bike Container which fixed bikes whenever they're docked.