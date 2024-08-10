
# Systematic personal health monitoring systems (PHMS) mapping study resources

This repository was created to store resources related to the article titled "Semantic Web technologies in sensor-based personal health monitoring systems: A systematic mapping study", which is currently under review at the Semantic Web Journal.  An updated copy of the article can be found on [arXiv](https://arxiv.org/abs/2306.04335).

## Abstract
In recent years, there has been an increased focus on early detection, prevention, and prediction of diseases. This, together with advances in sensor technology and the Internet of Things, has led to accelerated efforts in the development of personal health monitoring systems. This study analyses the state of the art in the use of Semantic Web technologies in sensor-based personal health monitoring systems. Using a systematic approach, a total of 43 systems are selected as representative of the current state of the art. We critically analyse the extent to which the selected systems address seven key challenges: interoperability, context awareness, situation detection, situation prediction, decision support, explainability, and uncertainty handling. We discuss the role and limitations of Semantic Web technologies in managing each challenge. We then conduct a quality assessment of the selected systems based on the data and devices used, system and components development, rigour of evaluation, and accessibility of research outputs. Finally, we propose a reference architecture to provide guidance for the design and development of new systems. This study provides a comprehensive mapping of the field, identifies inadequacies in the state of the art, and provides recommendations for future research.

![Map summarising the state of the art in the field.](https://github.com/mbithenzomo/semantic_phms_mapping_study/blob/main/images/map.png?raw=true)

## Research Papers
The research papers describing the 43 systems systematically selected for this study can be found [here](https://github.com/mbithenzomo/semantic_phms_mapping_study/tree/main/related_reviews).

Existing review and survey articles that are related to this study can be found [here](https://github.com/mbithenzomo/semantic_phms_mapping_study/tree/main/related_reviews), primarily divided into four groups. The reviews in Group 1 focus on the use of Semantic Web technologies in the health domain; those in Group 2 review the use of sensors and IoT in the health domain; those in Group 3 review the use of Semantic Web technologies with sensor and IoT data; and finally, Group 4 consists of reviews that do not fit neatly into any of the first three.

<img src="https://github.com/mbithenzomo/semantic_phms_mapping_study/blob/main/images/related_reviews.png?raw=true" alt="drawing" width="500" class="center"/>

## Analyses
The spreadsheets with the raw data from the challenges analysis and quality analysis of the systems can be found [here](https://docs.google.com/spreadsheets/d/1CBGaYS43Ky2i--eqxNIbfgHdinqupvAUs6V5bVXWGzI/edit?usp=sharing) and [here](https://docs.google.com/spreadsheets/d/1SVIbMidxDGlQFexG1fmJJUV94iNtarBRvyzxBxgPG6M/edit?usp=sharing), respectively.

## Resources

### Ontologies

 - [Semantic Sensor Network (SSN)](https://w3c.github.io/sdw/ssn/) (latest editor's draft)
 - [Smart Appliances REFerence (SAREF) core](https://saref.etsi.org/core/)
 - [SAREF for e-health and ageing well (SAREF4EHAW)](https://saref.etsi.org/saref4ehaw/)
 - [SAREF for wearables (SAREF4WEAR)](https://saref.etsi.org/saref4wear/)

### Standards and languages

 - [Resource Description Framework (RDF)](https://www.w3.org/RDF)
 - [RDF Schema (RDFS)](https://www.w3.org/wiki/RDFS)
 - [RDF-star](https://w3c.github.io/rdf-star/cg-spec)
 - [Notation 3](https://w3c.github.io/N3/spec)
 - [Web Ontology Language (OWL)](https://www.w3.org/OWL)
 - [Semantic Web Rule Language (SWRL)](https://www.w3.org/Submission/SWRL)
 - [Shapes Constraint Language (SHACL)](https://www.w3.org/TR/shacl)
 - [SPARQL Protocol and RDF Query Language (SPARQL)](https://www.w3.org/TR/rdf-sparql-query)

### Development tools

- [Protégé](https://protege.stanford.edu/) - ontology editor
- [Apache Jena](https://jena.apache.org/) - framework for building Semantic Web and Linked Data applications
- [Ontotext GraphDB](https://www.ontotext.com/products/graphdb/) - graph database
- [Stardog](https://www.stardog.com/platform/) - enterprise knowledge graph platform
- [Amazon Neptune](https://aws.amazon.com/neptune/) - serverless graph database

## How to cite
If you find this work useful, please cite it as follows:
```
@article{nzomo_semantic_2024,
      title={Semantic Web technologies in sensor-based personal health monitoring systems: A systematic mapping study},
      author={Nzomo, Mbithe and Moodley, Deshendran},
      year={2024},
      journal={arXiv preprint arXiv:2306.04335},
}
```
