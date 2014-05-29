Cluster Flow
============

Cluster Flow is a pipelining tool to automate and standardise bioinformatics analyses on high-performance cluster environments. It is designed to be easy to use, quick to set up and flexible to configure.

## Cluster Flow Website - [http://ewels.github.io/clusterflow/](http://ewels.github.io/clusterflow/)

There's a new website which for the Cluster Flow documentation which has loads of helpful information and examples. You can see it here: [http://ewels.github.io/clusterflow/](http://ewels.github.io/clusterflow/)

If you're anxious to just get your hands on the code, check out the [releases page](https://github.com/ewels/clusterflow/releases)

Licence
-------
Cluster Flow is released with a GPL v3 licence. Cluster Flow is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. For more information, see the licence that comes bundled with Cluster Flow.

Change Log
----------
#### [v0.2](https://github.com/ewels/clusterflow/releases/tag/v0.2) - 2014-05-29
* New Stuff
	* Now compatable with SLURM
	* Customise batch job commands in the config (see the [docs](http://ewels.github.io/clusterflow/installation/#making_cluster_flow_work_with_your_environment)
	* Created new GitHub pages website to hold documentation: http://ewels.github.io/clusterflow
* Updates
	* Ported repository to github: https://github.com/ewels/clusterflow
	* Wrote new readme for github
* Bugs Squashed
	* Custom modules in `~/clusterflow/modules/` weren't being found
	* General code clean-ups all over the place 

#### [v0.1](https://github.com/ewels/clusterflow/releases/tag/v0.1) - 2014-04-25
* The first public release of Cluster Flow, although it's been in use at the Babraham Institute for around 6 months. It's been in heavy development throughout that time and is now approaching a state of being relatively stable.


Credits
-------
Cluster Flow was written by [Phil Ewels](http://phil.ewels.co.uk) whilst working in the [Babraham Bioinformatics](http://www.bioinformatics.babraham.ac.uk/) group in Cambridge, UK. He now maintains it whilst working at the [Science for Life Laboratory](http://www.scilifelab.se/) in Stockholm, Sweden.