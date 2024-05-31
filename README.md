# GeneFEAST

GeneFEAST, implemented in Python, is a gene-centric functional enrichment analysis summarisation and visualisation tool that can be applied to large functional enrichment analysis (FEA) results arising from upstream FEA pipelines. It produces a systematic, navigable HTML report, making it easy to identify sets of genes putatively driving multiple enrichments and to explore gene-level quantitative data first used to identify input genes. Further, GeneFEAST can compare FEA results from multiple studies, making it possible, for example, to highlight patterns of gene expression amongst genes commonly differentially expressed in two sets of conditions, and giving rise to shared enrichments under those conditions. GeneFEAST offers a novel, effective way to address the complexities of linking up many overlapping FEA results to their underlying genes and data, advancing gene-centric hypotheses, and providing pivotal information for downstream validation experiments.

> Please see the [User Guide](https://avigailtaylor.github.io/GeneFEAST/user_guide.html) for installation and usage instructions.

> Once you have installed GeneFEAST (or downloaded the docker container) follow these links for:
> - [Single FEA summary example input data and output report](https://avigailtaylor.github.io/GeneFEAST/example_usage.html).
> - [Multi FEA summary example input data and output report](https://avigailtaylor.github.io/GeneFEAST/example_usage_multi.html).

---

### Citation

If you use GeneFEAST in your research, please cite the paper:
- Taylor, A., Macaulay, V.M., Maurya, A.K., Miossec, M.J., Buffa, F.M. GeneFEAST: the pivotal, gene-centric step in functional enrichment
  analysis interpretation. [arXiv:2309.00061](https://doi.org/10.48550/arXiv.2309.00061)

If you use an upset plot generated by GeneFEAST, please also cite: 
- Lex, A., Gehlenborg, N., Strobelt, H., Vuillemot, R., Pfister, R. UpSet: Visualization of Intersecting Sets. IEEE Transactions on Visualization and Computer Graphics (InfoVis ‘14), vol. 20, no. 12, pp. 1983–1992, 2014. doi.org/10.1109/TVCG.2014.2346248

If you use a GO hierarchy image generated by GeneFEAST, please also cite:
- Klopfenstein, D.V., Zhang, L., Pedersen, B.S. et al. GOATOOLS: A Python library for Gene Ontology analyses. Sci Rep 8, 10872 (2018). 
https://doi.org/10.1038/s41598-018-28948-z
