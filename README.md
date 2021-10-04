# Knowledge Representation and Reasoning
## Jupyter notebooks from exercises in NTUA during 2020-21 year.

### *KRR_ex1.ipynb*
Manual creation of knowledge graph and SPARQL queries.
Creation of knowledge graph using a subset of kaggle dataset and quering Wikidata SPARQL endpoint.
Construction of complex SPARQL queries for use with the created knowledge graph.

### *KRR_ex2.ipynb*
Transform ntriples knowledge graph into OWL.
Create owl Classes and Properties using said knowledge graph.
Check and fix semantical correctness of ontology.
Use 'Protege' tool to work with new ontology and make use of its reasoner.
Use 'GraphDB' tool to load the ontology we improved with 'Protege' for querying with SPARQL.

### *KRR_ex3.ipynb*
Add geographical data using Geonames API and Wikidata SPARQL endpoint and add to our knowledge graph using the correct spatial hierarchy.
Parse each movies description and group movies based on keywords.
Create categories to add movies to matching appropriate keywords.
Add these categories and the movies assigned to them into our knowledge graph.
Analyse sentiment of movie reviews.
Create complex categories to assign movies using 'Protege'.
Use SPARQL queries to test those complex categories.
Create movies recommender using SPARQL queries on the finilized knowledge graph.
