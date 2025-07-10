# Scientific Events Ontology (SEO)
[![License: CC-BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Ontology](https://img.shields.io/badge/Ontology-SEO-blue)](https://saidfathalla.github.io/SEOontology/Documentation/)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/saidfathalla/SEOontology)
[![GitHub last commit](https://img.shields.io/github/last-commit/saidfathalla/SEOontology)](https://github.com/saidfathalla/SEOontology/commits/master)
[![GitHub issues](https://img.shields.io/github/issues/saidfathalla/SEOontology)](https://github.com/saidfathalla/SEOontology/issues)


SEO, the Scientific Events Ontology, is a reference ontology for modeling data related to scientific events, including conferences, symposia, and workshops.
Documentation is available via its IRI. We describe a systematic redesign of the information model that is used as a schema for the event pages of the OpenResearch.org community wiki, reusing well-known vocabularies to make OR-SEO interoperable in different contexts. OR-SEO is now in use on thousands of OpenResearch.org events pages, which enables users to represent structured knowledge about events without having to deal with technical implementation challenges and ontology development themselves.
We reuse several well-known ontologies to make SEO interoperable in different contexts:

- The [Semantic Web Conference (SWC)](https://d-nb.info/1193192226/34) ontology is used to represent, e.g., _Conferences_ and _ConferenceSeries._
- [Time-indexed Value in Context (TVC)](https://sparontologies.github.io/tvc/current/tvc.html) is used to represent, e.g., _Duration_ and _Interval_.
- [Dublin Core Metadata Initiative (DCMI)](https://www.dublincore.org/) is used to describe metadata of typical entities in scientific events, e.g., of _Agents_ or _Proceedings_,
- [The Friend-of-a-Friend (FOAF) ontology](http://xmlns.com/foaf/spec/) describes involved persons and their social network profiles,
- [Semantically-Interlinked Online Communities (SIOC)](http://www.sioc-project.org/) describes information from online communities such as Role and Site.
- [SPAR ontologies](http://www.sparontologies.net/) describe research papers type (fabio), publications identifiers (datacite) and document parts (doco).
- [SemSur ontology](https://saidfathalla.github.io/SemSur/doc/) describes research findings based on an explicit semantic representation of the knowledge contained in scientific publications
- [ DBpedia Ontology](https://dbpedia.org/ontology/) (dbo) is used to represent geographical data, such as _dbo:Country_ and _dbo:City_.
 
## Ontology Overview

- **Ontology IRI**: https://w3id.org/seo#
- **Format**: OWL
- **Domain**: Events and social engagement
- **Creator**: [Said Fathalla](https://github.com/saidfathalla)

## Visualization
You can see a visualization of the main branch SEO.owl using [WebVOWL](https://service.tib.eu/webvowl/#iri=https://raw.githubusercontent.com/saidfathalla/SEOontology/master/SEO.owl).

## Publications
- Fathalla, Said, Sahar Vahdati, Christoph Lange, and Sören Auer. "SEO: A scientific events data model." In The Semantic Web–ISWC 2019: 18th International Semantic Web Conference, Auckland, New Zealand, October 26–30, 2019, Proceedings, Part II 18, pp. 79-95. Springer International Publishing, 2019.
- Fathalla, Said, Sahar Vahdati, Sören Auer, and Christoph Lange. "The scientific events ontology of the openresearch.org curation platform." In Proceedings of the 34th ACM/SIGAPP Symposium on Applied Computing, pp. 2311-2313. 2019.

## LICENSE
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). 
