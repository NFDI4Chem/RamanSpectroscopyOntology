# Design Patterns & Decisions
 
**This page is still a stub and will be updated regularly in the iterative development of VISBO to document modeling decisions and design patterns.**

Following best practices in ontology development, we will reuse well established design patterns whenever possible.

## Planned Process Pattern
 OBI's way of modeling [meassurements and processes](https://github.com/obi-ontology/obi/wiki/Data-and-Values) is one of the most prominent process patterns used throughout the OBO ontologies. 
 
Lars Vogt and Tobias Kuhn demonstrate the actual use of this pattern within a knowledge graph quite nicely on the example of a mass measurement as follows (cited from their preprint [DOI:10.13140/RG.2.2.13742.59203](http://doi.org/10.13140/RG.2.2.13742.59203), p.8):
 ![](C:\Users\stroemertp\VibrationSpectroscopyOntology\docs\images\Fig4_10.13140_RG.2.2.13742.59203.png)
 > Figure 3: A detailed machine-actionable representation of the metadata relating to a weight measurement datum documented as an RDF ABox graph. The representation takes the form of an ABox semantic graph following the RDF syntax. The graph documents a mass measurement process using a balance. It relates an instance of mass measurement assay (OBI:0000445) with instances of various other classes from different ontologies, specifying who conducted the measurement, where and when it took place, following which protocol and using which device (i.e., balance). The graph furthermore specifies the particular material entity that served as subject and thus as input of the measurement process (i.e., ‘objectX’), and it specifies the data that is the output of the observation, which is contained in a particular weight measurement assertion.


## Vibrational Raman Spectroscopy

Here you can see the first draft of VIBSO's terminology box that focuses on vibrational Raman spectroscopy and which also shows how VIBSO depend on reusing existing ontology classes, relations and design patterns. The initially identified needed terms, depicted here with a red border, were derived from a Raman spectrometer output.

![Raman spectroscopy terminology box](images/VISBO_Raman_Tbox.png)

What is needed next are iterative reviews of this draft by domain experts to expand it and to ensure that the [competency questions](competency_questions.md) of VIBSO can be answered. 