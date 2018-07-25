# datasets-br

Describing the datasets-br directives and using this project as [point of generic discussions](https://github.com/datasets-br/datasets-br/issues).

## Dataset-BR directives

1. To post qualified datasets in the [Datahub.io](http://datahub.io);
2. To unify, by curatory process, a set of [Wikidata](http://wikidata.org) fragments if items, or commom instances of an item;
3. To unify  terminology to express CSV colunm names, table and column semantics ([SchemaOrg conventions](http://schema.org) when possible) 
3. [Digital preservation](https://en.wikipedia.org/wiki/Digital_preservation) (CSV files and data dumps from original soruces) of the curated datasets;
5. Monitoring/auditing Wikidata and [OpenStreetMap](http://openStreetMap.org) changes, in the context of the curated datasets.

## Use as an ecosystem of datasets

Example of use with 2 BR's datasets, [`state-codes`](https://github.com/datasets-br/state-codes) and [`city-codes`](https://github.com/datasets-br/city-codes).

![](assets/dataModel-example01.png)

Operating with pure SQL or [SQL-unifier](https://github.com/datasets-br/sql-unifier) will be easy to merge with other datasets... 
With PopstgreSQL you can offer datasets in an standard API with [PostgreREST](https://postgrest.org/en/v5.0/) 
(or its  descendents [pREST](https://postgres.rest) and [PostGraphile](https://www.graphile.org/postgraphile/)), 
or plug-and-play with [SchemaOrg](http://schema.org) standards, 
[FrictionlessData](https://frictionlessdata.io/specs/) standards (and [tools](https://frictionlessdata.io/software/)), etc. 

## Documentation
... [under construction](docs) 

Conventions for [data provenance and prepare](docs/README.md).

------

[&#160; Contents and data of this project are dedicated to<br/> ![](assets/CC0-logo-200px.png) ](LICENSE.md)


