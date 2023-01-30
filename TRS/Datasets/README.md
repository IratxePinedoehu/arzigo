The core of our data generation process is a multidisciplinary repository managed by a search engine, which contains papers associated with different 
scientific fields, as computer science, neuroscience or microbiology. The repository is based on Semantic Scholar Open Research Corpus, developed by
Semantic Scholar. It is a scalable system for organizing published scientific literature in an heterogeneous graph, to facilitate manipulation and 
discovery through algorithmic techniques.

Based on this repository, the process tries to simulate the data collected in an educational institution where subjects are taught in different courses at
different moments in a semester. While taking a course, students consult and interact with research papers related to the subject and generate different kinds of interactions (access, download, consult different sections, add to
articles of interest. . . ). Driven by the values of a set of parameters, such as,number of papers available per subject, sessions per user and interactions
per session, the process generates the interaction history for each user.

Through this process, two datasets have been generated, where the main difference is in the number of papers that each of them contains. The first one,
called Small Catalog, contains a smaller catalog of papers, which leads to the generation of sequences of interactions that are more similar to each other,
even among different users. The second one, called Big Catalog, contains a bigger catalog of papers and therefore, the sequences of interactions are much
more heterogeneous.
