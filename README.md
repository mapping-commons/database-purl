# Coordinating Database PURLs with w3id

The Semantic Web stack, in particular RDF, plays a very important role in integrating data across domains such as biology and medicine.

Unfortunately, many widely used databases such as HGNC do not have a specific PURL (Persistent URL) scheme for their identifiers.

W3id.org is a volunteer run service to supply PURLs for a variety of applications, including data integration efforts in the Semantic Web. While adding a new record is straight forward even with technical knowledge, many groups neither have time nor the required expertise to manage their PURL spaces, including programming redirects for identifiers. We seek to provide an intermediate service that manages PURL spaces for a number of databases centrally, which is then syncronised with as specific w3id.org ID space, `https://w3id.org/db` (db for "database"). As a first goal, we are collaborating with HGNC to define the hgnc namespace as follows: `https://w3id.org/db/hgnc`. This is less direct then `https://w3id.org/hgnc`, but allows us to build a central governance structure, provide a seemless service for updating purl spaces and provide some oversight over the PURLs to ensure that they are not _changed_ accidentally or intentially by the source providers. This increases trust into the PURL scheme for RDF data integration. Furthermore, it takes some load of the w3id.org maintainers, as only already well reviewed changes will be pushed to w3id.org.

## Database maintainers

Please edit [.htaccess] file. You have to have permission to edit your section.