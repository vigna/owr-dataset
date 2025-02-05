# The Open Wikipedia Ranking Dataset

[The Open Wikipedia Ranking](https://wikirank.di.unimi.it/) is an effort
to rank the English Wikipedia pages using open-source software, classical
centrality measures, and an entirely reproducible process.

For each year, we provide:

- A title file, containing the title of a Wikipedia page per
  line.
- A category file, a file parallel to the title file, containing for
  each line a list of the “instance of” properties associated with each
  page by Wikidata, closed transitively by “subclass of”. These
  categories can be used to select pages using the classification provided
  by the Wikidata ontology.
- Four ranking files, for indegree, PageRank (⍺ = 0.75), harmonic
  centrality, and page views, in big-endian 64-bit IEEE 754 format (i.e.,
  Java binary format), in the same order as the title file.
- The same rankings in ASCII text format, again in the same order
  of the title file.

Please write to sebastiano.vigna@unimi.it if you have questions about
the dataset.

The licensing for the data set is the same as that of Wikipedia, which
is detailed at https://en.wikipedia.org/wiki/Wikipedia:Copyrights:

Permission is granted to copy, distribute and/or modify Wikipedia's text under
the terms of the Creative Commons Attribution-ShareAlike 4.0 International
License and, unless otherwise noted, the GNU Free Documentation License,
unversioned, with no invariant sections, front-cover texts, or back-cover texts.
