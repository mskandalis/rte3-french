# French version of the English RTE-3 dataset (RTE3-FR)

The present RTE3-FR dataset is the French translation of the Textual Entailment English dataset used in the RTE-3 Challenge (https://nlp.stanford.edu/RTE3-pilot/).

Like its English counterpart, the French RTE-3 dataset is composed of a development set and a test set, each containing 800 T/H pairs.

The dataset is annotated for a 3-way task with the following labels: entailment (0), neutral (1), contradiction (2). 

RTE3-FR is available in XML and TSV format.

It is also available on huggingface.co as a [monolingual French dataset](https://huggingface.co/datasets/maximoss/rte3-french) (same as here) or as part of a [multilingual dataset containing all manually translated versions of RTE-3 dataset](https://huggingface.co/datasets/maximoss/rte3-multi). 

# How to use in python

```
import pandas as pd

dev = pd.read_csv("./RTE3-FR-dev-set-3class.tsv", sep='\t')
print(dev)

test = pd.read_csv("./RTE3-FR-test-set-3class.tsv", sep='\t')
print(test)
```

# Cite

TBA

# Acknowledgements

This work was supported by the French Defence Innovation Agency (AID) of the Directorate General of Armament (DGA) of the French Ministry of Armed Forces, and by the ICO, _Institut Cybersécurité Occitanie_, funded by Région Occitanie, France.
