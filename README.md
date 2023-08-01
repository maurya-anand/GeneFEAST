# GeneFEAST

GeneFEAST, implemented in Python, is a gene-centric functional enrichment analysis summarisation and visualisation tool that can be applied to large functional enrichment analysis (FEA) results arising from any upstream FEA pipeline. It produces a systematic, navigable HTML report, making it easy to identify sets of genes putatively driving multiple enrichments and to explore gene-level quantitative data first used to identify input genes. Further, GeneFEAST can compare FEA results from multiple studies, making it possible to, for example, highlight patterns of gene expression amongst genes commonly differentially expressed in two sets of conditions, and giving rise to shared enrichments under those conditions. GeneFEAST offers a novel, effective way to address the complexities of linking up many, overlapping FEA results to their underlying genes and data; advancing gene-centric hypotheses, and providing pivotal information for downstream validation experiments.

## Installation

We **strongly recommend** installing GeneFEAST in a **virtual environment** because the library has several requirements:

- python == 3.7
- matplotlib == 3.3.3
- numpy == 1.17.2
- pandas == 0.25.2
- upsetplot == 0.4.1
- goatools == 1.0.14
- scipy == 1.3.2
- networkx == 2.5
- lxml == 4.4.1
- beautifulsoup4 == 4.8.0
- pillow == 6.2.0
- PyYAML == 5.1.2
<br></br>
> Please follow the instructions at the top of this **[guide](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment)** to create and activate a virtual environment. Please only follow the instructions to the end of section **Activating a virtual environment** and then **come back here**.

<br></br>
Once you have created and activated your virtual environment, you can install the library using pip:

> $ pip install genefeast
