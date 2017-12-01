# library-of-alexandria

Automated science and math.

Math and science have become too big for individuals. We find it hard to keep up and to cram the relevant knowledge into our small heads. We need better tools to continue push the boundaries.

### Potential projects

* Automatic meta-analysis: cluster papers on the same topic, extract results, weight by reliability, integrate.
* Summarisation, distillation and explanation.
* Clustering: find similar ideas across different fields
* Truth propagation. A graph of theories, that is pruned with evidence, ...
* Active learning (predict experiments)
* UCB algorithm for allocating grant money (explore-exploit). Matching researchers and grants?
* Tree search through proofs
* Automated journal reviewed by AI
* Automated uni courses. 

### The data

* Get papers from arxiv (or similar? biovix, sci-hub)
* Create new DS for parsed papers? And then manually label a bunch of papers myself?
* Math databases? Parse papers and construct a database? (e.g. for computational complexity?)

### Approach 1.0: Graphs

* Construct various graphs; (not would prefer the graph nodes to be topics/ideas/theories rather than papers)
  * Citation network
  * Similarity network
  * Dependency network (based on the math? or just ordering in time?)
* Construct a graph from a single paper!

### Collecting evidence

* Parse papers and pick out the evidence. 
* A search engine for evidence. 
  * Query(smoking, cancer) -> fn(p(cancer) = m\*smoking + c)
  * Query(gravity) -> ???

### Deeper questions

* What makes something true? Evidence and only a single theory that fits the evidence.
* Math is weird. Since it all follows logical ... ? What we are looking for is things that are; beautiful, interpretable, have an intuitive explanation, clearly apply in the real world, examples, ...?
* What makes good scientific research? Removing uncertainty, increasing possibilities (new questions), ???, ...

### ?

> A theory is the compression of facts.
