Provenance Corpus
=================

This is the [Wf4Ever](http://www.wf4ever-project.org/) Provenance corpus.
The corpus is [maintained at GitHub](https://github.com/wf4ever/taverna-prov).
For more information, read about the [Provenance corpus in the Wf4Ever
wiki](http://www.wf4ever-project.org/wiki/display/docs/Provenance+corpus).

Each of the folders represent a [Taverna](http://www.taverna.org.uk/) 
workflow from [myExperiment](http://www.myexperiment.org/). The folders
are called for instance `1234-v1` representing version 1 of workflow
1234 on myExperiment - ie.
`http://www.myexperiment.org/workflows/*1234*/versions/*1*`


Within the workflow folder, different workflow runs are shown as 
`run1`, `run2` etc, each containing the provenance output of 
export using the [Taverna-Prov plugin](https://github.com/wf4ever/taverna-prov).


Licensing
---------

Each workflow has separate copyright and licensing information. The
file `LICENSE.txt` should be a symlink to the appropriate license
from the licenses/ folder. It is currently unclear if the license for a
workflow extends to its provenance outputs; as the provenance trace will
contain parts of the workflow definition (namely processor names and
ports) and could be used to recreate a partial workflow definition, it
could be considered "derived work". 

The intermediate and resulting data might be covered by separate
licenses for the services invoked by the workflow.

This combined work, if not overriden by the above, is
distributed under the [Creative Commons Attribution 3.0 Unported
license](http://creativecommons.org/licenses/by/3.0/) and copyrighted by
the [Wf4Ever project partners](http://www.wf4ever-project.org/partners):

* iSOCO, Spain
* University of Manchester, UK
* Universidad Politécnica de Madrid, Spain
* University of Oxford, UK
* Poznan Supercomputing and Networking Center, Poland
* Instituto de Astrofísica de Andalucía, Spain
* University Medical Centre, The Netherlands
