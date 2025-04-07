# MathAlgoDB
## The MathAlgoDB knowledge graph
Numerical Algorithms are a principal tool for simulation, optimization or control. Yet, finding a suitable algorithms to one's problem, software implementations of an algorithm, or surveys on certain algorithms is often hard. **MathAlgoDB** aims to improve this by assigning metadata to algorithms as a community project, and make it searchable.

**MathAlgoDB** is a Knowledge Graph for numerical algorithms with a [reference web front-end](https://mathalgodb.mardi4nfdi.de) providing a semantic search engine, a full-text search, and a browsable index. The graph represents knowledge by relations between five classes of (meta-)data: problem, algorithm, benchmark, software, and publication, which are defined in the MathAlgoDB ontology.

**MathAlgoDB** is not only for mathematicians from the fields numerical analysis, numerical linear algebra, scientific computing, computational science and engineering, and data science, but also for scientists, researchers, engineers, or students from all fields interested in numerical algorithms.

**MathAlgoDB** is a MaRDI (MAthematical Research Data Initiative) measure, to make numerical research data FAIR (Findable, Accessible, Interoperable, Reusable), particularly numerical algorithms and their meta-data.

Technically, the **MathAlgoDB** front-end is based on an RDF data model in Turtle syntax, served by Apache Jena Fuseki, and queried via SPARQL.

## Authors
- Christian Himpe, University of Münster (https://orcid.org/0000-0003-2194-6754)
- Frank Wübbeling, University of Münster (https://orcid.org/0000-0002-2375-2008)
- Hendrik Kleikamp, University of Münster (https://orcid.org/0000-0003-1264-5941)
- René Fritze, University of Münster (https://orcid.org/0000-0002-9548-2238)
- Stephan Rave, University of Münster (https://orcid.org/0000-0003-0439-7212)

## Usage and Exploration
- MathAlgoDB_Ontology.ttl holds the OWL definition of the ontology in Turtle File syntax.
- MathAlgoDB_Data.ttl holds the knowledge graph data for sample fields Numerical Analysis and Model Order Reduction.
- The graph is available for exploration through the user interface at https://mathalgodb.mardi4nfdi.de/.
- The ontology documentation is available through https://mathalgodb.mardi4nfdi.de/static/widoco/v1/index-en.html.

## License
The ontology MathModDB is licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Funding Acknowledgement
The work has been funded by the DFG (German Research Foundation), project number 460135501, NFDI 29/1 “MaRDI – Mathematische Forschungsdateninitiative”.
