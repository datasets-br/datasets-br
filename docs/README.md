## Conventions for data proveance
[*Data provenance* provides a historical record of the data and its origins](https://en.wikipedia.org/wiki/Data_lineage#Data_Provenance).
Most of the data in this project (Datasets-BR), or similar projects like [Datahub.io](http://datahub.io), 
are simply the copy of some portions of data from an authority that worked to produce them, and offers reliability in their processes.  
Some datasets or portions of datasets of this project also have origem in the "filtering" of that raw original datasets, 
so can be described as **preparation** algorithm (a simple recipe), or expressed as a software that can run again to any one reproduce the process. 


As a [convention over configuration](https://en.wikipedia.org/wiki/Convention_over_configuration) strategy, 
there are two general approaches to describe the original sources of a dataset:

* Registering here as [`datapackage.json` in the FrictionlessData standard](https://frictionlessdata.io/specs/data-package/);

* Registering at [Wikidata](http://wikidata.org) in each item its source as *reference*, with [*has quality*](https://www.wikidata.org/wiki/Property:P1552) or with [*stated in*](https://www.wikidata.org/wiki/Property:P248).

To express algorithms of the transformations, please frefer the simplest, functional and "standard" way. The convention is to use the following priority of languages:

1. With SQL statements (with no or some PL/pgSQL functions).

2. With Python or Javascript.

3. With Perl, make, shell and others.

