# geolab

## VERSION 1.0.0

*Objective*

The aim of this project is to develop a python module for processing molecular 
dynamics data. We currently using 
>
>	CP2K: https://www.cp2k.org/
>	DL_POLY: https://www.scd.stfc.ac.uk/Pages/DL_POLY.aspx
>	LAMMPS: http://lammps.sandia.gov/
>
to probe the mineral/water and mineral/organics interfaces.

This project is divided into following parts:
>   1. io
>   2. structure
>   3. dynamics
>   4. energy and forces

## Language

The development language is PYTHON. 

All comments and documentation should be written in English.

## History

> I started this project in 2016 for my undergraduate thesis.
> 
> I open-sourced it in 2017 and in an organized form.

## Installation

Just add the geolab directory to your PYTHONPATH like:
>   export PYTHONPATH=/path/to/geolab:$PYTHNPATH

Once installed, you have to run these commands to use the project:

	import geolab
	 
	 or
	 
	from geolab import io

Enjoy!

## Contributing

We’re really happy to accept contributions from the community, that’s the main reason why we open-sourced it! There are many ways to contribute, even if you’re not a technical person.

We’re using the infamous [simplified Github workflow](http://scottchacon.com/2011/08/31/github-flow.html) to accept modifications (even internally), basically you’ll have to:

* create an issue related to the problem you want to fix (good for traceability and cross-reference)
* fork the repository
* create a branch (optionally with the reference to the issue in the name)
* hack hack hack
* commit incrementally with readable and detailed commit messages
* submit a pull-request against the master branch of this repository

We’ll take care of tagging your issue with the appropriated labels and answer within a week (hopefully less!) to the problem you encounter.

If you’re not familiar with open-source workflows or our set of technologies, do not hesitate to ask for help! We can mentor you or propose good first bugs (as labeled in our issues). Also welcome to add your name to Credits section of this document.

### Submitting bugs

You can report issues directly on Github, that would be a really useful contribution given that we lack some user testing on the project. Please document as much as possible the steps to reproduce your problem (even better with screenshots).

### Discussing strategies

We’re trying to develop this project in the open as much as possible. We have a dedicated mailing-list where we discuss each new strategic change and invite the community to give a valuable feedback. You’re encouraged to subscribe to it and participate.

### Adding documentation

We’re doing our best to document each usage of the project but you can improve it or add you own sections. The documentation is available within the /docs/ folder. You don’t have to build anything, we’ll take care of it once your changes are merged.


## License

We’re using the GNU GENERAL PUBLIC LICENSE Version 3 license.


## Credits

* Author: Yingchun Zhang
* E-mail: yczhang@smail.nju.edu.cn
