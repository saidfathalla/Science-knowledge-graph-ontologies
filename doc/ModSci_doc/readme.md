# The Modern Science ontology Documentation

This documentation is created using [WIzard for DOCumenting Ontologies (WIDOCO)](https://dgarijo.github.io/Widoco/).


## About Widoco output

The purpose of Widoco is to reuse and integrate existing tools for documentation, plus the set of features listed below:
* Separation of the sections of your html page so you can write them independently and replace only those needed.
* Automatic annotation in RDF-a of the html produced.
* Association of a provenance page which includes the history of your vocabulary (W3C PROV-O compliant).
* Metadata extraction from the ontology plus the means to complete it on the fly when generating your ontology.
* Guidelines on the main sections that your document should have and how to complete them.

Widoco will create 3 different folders:
|
|-provenance (a folder including an html and RDF serialization of how the documentation page was created)
|-resources (folder with the different resources)
|-sections (folder with the different sections of the documentation, separated for easy editing. Just edit one and the main page will be updated)

## Completing ontology metadata.

Widoco uses the ontology metadata to update a configuration file. If you complete that configuration file (ended up widoco.conf), the tool will enhance your html with additional details, such as how to cite the document, previous revisions, icons with the licence, etc.
