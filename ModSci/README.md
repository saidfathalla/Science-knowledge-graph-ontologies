# Modern Science Ontology (ModSci)
Modern Science Ontology (ModSci) is an upper ontology for modeling relationships between modern science branches and related entities, such as scientific discoveries, phenomena, renowned scientists, instruments, etc. 
ModSci provides a unifying framework for the various domain ontologies that make up the Science Knowledge Graph Ontology Suite. 
ModSci is a poly-hierarchical ontology that can be utilized in semantic web applications. 

## Schema diagram
The following figure shows the core concepts in the ontoilogy.
![modsci schema](https://user-images.githubusercontent.com/21238109/208491436-2d950157-25d2-47a1-b470-eaaf900dc6e7.png)


## Ontology Publishing
The ontology is published under a persistent URL (https://w3id.org/skgo/modsci#) with dereferenceable URIs. 
We configured the server to provide human-readable HTML content from the vocabulary URI using the recipes provided in [Best Practice Recipes for Publishing RDF Vocabularies](https://www.w3.org/TR/swbp-vocab-pub/).

## License
The ontology has been published under the open [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).

## Indexing
ModSci can be browsed online, through a web-based repository front-end for browsing and visualizing published ontologies, at:
 - [BioPortal](http://bioportal.bioontology.org/ontologies/MODSCI), 
 - [Linked Open Vocabularies](https://lov.linkeddata.es/dataset/lov/vocabs/modsci), and 
 - [AberOWL](http://aber-owl.net/ontology/ModSci/).
 

## Documentation and visualization
The Wizard for documenting ontologies [WIDOCO](https://github.com/dgarijo/Widoco) is used to create HTML documentation for the ontology (available via [https://w3id.org/skgo/modsci#]), thus enabling human understandability of the ontologies.
Besides, the \texttt{rdfs:comment} property is used to provide a human-readable description of each resource. 
An interactive visualization for browsing ModSci hierarchy has been developed using [D3.JS](https://d3js.org/) libraries.

## Use cases
ModSci powers two projects for semantically representing scholarly information: 
- [Open Research Knowledge Graph](https://www.orkg.org/orkg/): for the categorization of research papers 
- [OpenResearch.org](https://www.openresearch.org/wiki/Main_Page):for the categorization of the information about scientific events, research projects, scientific papers, publishers, and journals.
