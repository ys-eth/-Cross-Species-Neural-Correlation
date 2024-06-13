## Cross-Species Correlation Project

### Overview

In this project, we explored the relationship between gene expression patterns and the electrophysiological properties of neurons across different brain structures in humans and mice. By analyzing data from the Allen Brain Atlas, we aimed to identify conserved neural properties and patterns that could provide insights into the similarities and differences in brain function between these species. Our approach involved data cleaning, visualization, and various machine learning techniques to analyze and interpret the data.

### Research Question

How do the gene expression patterns and electrophysiological properties of neurons correlate across the different brain structures of humans and mice?

### Background & Prior Work

Studying the connection between gene expression patterns and the electrophysiological properties of neurons is crucial for understanding how brain functions emerge at the cellular level. Different brain regions involved in cognition, sensory processing, and motor control exhibit specific characteristics influenced by their gene expression profiles and electrophysiological properties. Our group is particularly interested in the correlations between human brain function and neural activity in mice, as these similarities can validate whether discoveries in mouse physiology apply to humans.

- Gouwens et al. (2020) correlated the transcriptomic and electrophysiological diversity in mouse visual cortical neurons, identifying unique neuronal types with distinct molecular and functional profiles. This study expands our knowledge of the molecular foundations of neuronal diversity, offering insights that could lead to a deeper understanding of how complex neural networks work.
- Clancy et al. (2009) contributes to our understanding of cross-species correlations with a focus on the cortical GABAergic and subplate neural populations in mice, rats, and macaque species. The authors observed that these particular neurons have many different shapes and structures, which sets them apart from the more common type of neurons called pyramidal neurons, which is closely related to some of the findings from Gouwens et al. (2020).
- Földy et al. (2016) demonstrated how specific gene expression patterns correspond to electrophysiological behaviors in human cortical neurons, assisting in our understanding of how the human brain functions. These studies, supported by resources like the Allen Brain Atlas, have created an in-depth view of how genetic and electrophysiological properties can be visualized with large-scale data. The Allen Brain Atlas has made it possible to make inferences about many kinds of data observed by the firing of action potentials. This gives us the chance to observe the behavior of neurons, helping doctors catch and diagnose neurological disorders before they worsen.
- Recent research by Kim et al. (2023) further supports the relevance of using mice as models for human brain studies by showing that inhibitory circuit motifs are strikingly similar between humans and mice. Their study highlights conserved synaptic dynamics involving excitatory and inhibitory neurons, reinforcing the notion that findings in mouse models can be relevant to understanding human neurophysiology. This cross-species comparison adds a significant layer of validation to the extensive use of mouse models in neuroscience research, emphasizing the evolutionary conservation of key neural circuits.

### References

1. [Gouwens et al. (2020)](https://pubmed.ncbi.nlm.nih.gov/33186530/)
2. [Clancy et al. (2009)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2779099/)
3. [Földy et al. (2016)](https://pubmed.ncbi.nlm.nih.gov/27531958/)
4. [Allen Brain Atlas](https://portal.brain-map.org/?utm_source=google&utm_medium=cpc&utm_campaign=brand_brainmaporg&gad_source=1&gclid=Cj0KCQjw_-GxBhC1ARIsADGgDjtsd3F3KRm0a_lF7V1HnmiDBTRpFChm8CFby2PwiNrXDjFz0NzB1fYaAlWDEALw_wcB)
5. [Kim et al. (2023)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10332809/)

### Hypothesis

We hypothesize that the characteristics of neurons will not form distinct clusters between humans and mice, but rather will show significant correlation, reflecting conserved neural properties across these species.

### Dataset(s)

- **Dataset Name:** Cell Features: Allen Brain Atlas - Cell Types
- **Link to the dataset:** [Allen Brain Atlas Cell Types](https://celltypes.brain-map.org/data)
- **Number of observations:** 2333 rows and 53 columns

We plan to combine the brain cell database's datasets by aligning the gene expression profiles and electrophysiological properties of neurons from both human and mouse brain structures. This will involve standardizing the data formats and using statistical methods to integrate and compare the features across species to identify conserved patterns and correlations.
