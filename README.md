# isosteric-replacements
An exercise in the form of a Jupyter Notebook with describes how to use Python, pandas, and rdkit to enumerate isosteric replacements of a given drug-like chemical structure.

There are two versions of the notebook
- the "normal" one, `isosteric-replacements`, that should be the first one to be tried out.
- the "expanded" version, `isosteric-replacements-expanded`, which include cross-joining operations on the isosteric database, increasing greatly the number of isosteric replacements the notebook can suggest.

### Logic behind the "expanded" version
The logic done is quite simple. If chemical groups A and B are both isosteres of a chemical group C, that means that A and B should (or must) be isosteres of each other. This logic was implemented using the free software [KNIME](https://www.knime.com) to create the extended table. 

## Requirements
It is required that you have the Python modules `pandas` and `rdkit` (and their dependences) configured in your conda environment. 

## License
(c) Cedric Graebin (Drug Discovery Unit, University of Dundee, Scotland). This notebook is distributed under the terms of the GPL v3 license.
