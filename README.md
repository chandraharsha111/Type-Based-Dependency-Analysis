# Type-Based-Dependency-Analysis
* Developed a type-based dependency analyzer that would build a type table by extracting lexical content from source code.
* Implemented a dependency analysis table which would give information about each file and the list of files depending upon it
* Traced the Strong Components using Trajan’s Algorithm. A strong component is the largest set of files that are mutually dependent.
* All the analysis results were stored in a NoSQL DB i.e. implemented from scratch.  Storing the analysis results in NoSQL Data Base would help us persist the analysis results in the form of metadata as XML
