# Why did I fork this?
The original git repo wasn't importable as is. So i forked it to add the necessary dependencies and make it importable.


# Equivalent Passage Plan Method

An event identification and trajectory simplification method based on behaviour identification and translation. Trajectory segments deemed to correspond to coastal or ocean navigation are translated into equivalent passage plan segments, a succinct description of the movements and behaviour of the ship. As a trajectory simplification method, it provides two main advantages over commonly used trajectory simplification methods: more meaningful simplified trajectories with better encoding of basic behaviours and the possibility to retain interesting behaviours in full resolution. As an event identification method, it is capable of differentiating between normal ocean or coastal navigating behaviour and complex or interesting behaviour, such as pilotage, reaction to a traffic conflict, or an involuntary deviation from the passage plan. 

To run, the code requires the the following python packages:

- numpy
- pandas
- nvector
- matplotlib
- matplotlib basemap toolkit

nvector requires a few geospacial libraries, that can be tricky to install on windows machines.
You can download precompiled versions of them (here)[https://www.lfd.uci.edu/~gohlke/pythonlibs/]