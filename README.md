# CRO
The Common Rule Ontology \(CRO\), is a BFO-based ontology of the U.S. Common Rule 45 CFR 46. This federal *regulation* is also known as the [Federal Policy for the Protection of Human Subjects](https://www.hhs.gov/ohrp/regulations-and-policy/regulations/common-rule/index.html). 

The ontology attempts to represent subparts A through D of the Common Rule. The CRO contains classes for major parts of the [1991 version of the regulations](https://www.hhs.gov/ohrp/regulations-and-policy/regulations/45-cfr-46/index.html), as in effect prior to January 19, 2017. 

Classes are also implemented for the "secondary research" parts of the [2017 revision of the Common Rule](https://www.hhs.gov/ohrp/regulations-and-policy/regulations/finalized-revisions-common-rule/index.html) that was slated to go into effect on January 19, 2018. As of this writing on 3/5/2018 however, implementation of the regulation remains on hold pending administrative review and final decision by the Trump administration. Further development of the 2017 parts of this ontology await the outcome the administration's review of the Common Rule. 

### owl:versionInfo: 2018-02-26 \(draft\)
## Warning: This ontology is currently in a pre-release DRAFT form
While the ontology remains in this form, the developers give no assurances as to the permanance of the URI's in the ontology. Although the ontology is substantively finished, as of March 2018 the ontology is actively being worked on by a set of core developers and collaborators. We have recently finished a workshop on Informed Consent and the Informed Consent ontology (See https://github.com/ICO-ontology/ICO) in Little Rock, Ark. where a series of development principles and design patterns for work representing research rights, permissions, and obligations were decided on. The framework uses deontic roles. We intend to harmonized the CRO with the Informed Consent Ontology, as well as several other BFO-based/OBO-Foundry ontologies.

Note that this work has not yet been fully reviewed by the OBO Foundry. Consequently the OBO namespace "CRO" has not been reserved and may change. Since the work has not yet been accepted by OBO Foundry, we can make no guarantees as to full compatibility with that repository. As such the ontology has not yet been submitted to the [OntoBee repository](http://www.ontobee.org/). Additionally we have not yet submitted the ontology to any other repository, such as the [NCBO BioPortal](https://bioportal.bioontology.org/). Publications describing the work are under development.

## License and attribution:
The Common Rule Ontology (CRO)  by Drs. Frank J. Manion, Marcelline R. Harris, and Cui Tao  is licensed under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode) \(CC BY 4.0\). You are free to share (copy and redistribute the material in any medium or format) and adapt (remix, transform, and build upon the material) for any purpose, even commercially. for any purpose, even commercially. The licensor cannot revoke these freedoms as long as you follow the license terms. You must give appropriate credit (by using the original ontology IRI for the whole ontology and original term IRIs for individual terms), provide a link to the license, and indicate if any changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

## Creators and Contributors
Many people, including many colleagues from the OBO Foundry, have contributed to the development and validation of the CRO. A full list of people involved in this effort can be found in the annotation properties in the OWL file.

## Editor's note (FJM).
When using or expanding this ontology, it is important to note that care has been taken to use definitions of classes and relations with meaning to the legal community. This differs from many OBO Foundry ontologies whose underlying definitions are biological. For example, for the definition of "child" we could have imported the "child" class from the [Human Phenotype Ontology](http://human-phenotype-ontology.github.io/) \(HPO\). However, child in HPO  refers to a specific biological age (a human developmental stage that covers the period from birth until 12 years old) where as the definition of a child according to the Common Rule is "Children are persons who have not attained the legal age for consent to treatments or procedures involved in the research, under the applicable law of the jurisdiction in which the research will be conducted."


