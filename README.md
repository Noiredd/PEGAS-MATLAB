## PEGAS-MATLAB
*Powered Explicit Guidance Ascent System* is a simple physics simulator based on [Kerbal Space Program](https://kerbalspaceprogram.com/) together with an implementation of two real-word rocket guidance algorithms: previously [Powered Explicit Guidance](http://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/19660006073.pdf), more recently [Unified Powered Flight Guidance](https://ntrs.nasa.gov/search.jsp?R=19740004402) - as used in the **Space Shuttle** GN&C computer.

[PEGAS](https://github.com/Noiredd/PEGAS) started as an autopilot script for the game, but soon - due to its unique implementation of PEG and then UPFG - evolved into a complex piece of software that needed an entire simulation environment to develop and debug.
This infrastructure code was written in MATLAB and originally PEGAS repository held both that prototype code and the game script.
Since the prototype code grew somewhat beyond its original purpose, and at the present state it is a general testing platform for possibly many other projects, it was separated from the game code and placed in the following repository.

### Credits

MATLAB `linearFit.m` function contains pieces written originally by [Andrey Rubshtein](http://stackoverflow.com/users/817452/andrey-rubshtein) and [Nikolai Golovchenko](http://golovchenko.org).
`flightPlots.m` uses [Richard Crozier](http://www.mathworks.com/matlabcentral/profile/authors/1590682-richard-crozier)'s [`tightfit`](http://www.mathworks.com/matlabcentral/fileexchange/34055-tightfig) (see MATLAB\tightfit.license for attached BSD license).
I also made use of [Will Campbell](https://www.mathworks.com/matlabcentral/profile/authors/1050816-will-campbell)'s [`earth_sphere`](https://www.mathworks.com/matlabcentral/fileexchange/27123-earth-sized-sphere-with-topography) code (see MATLAB\earth_sphere.license for attached BSD license).
Thank you for your great work!
