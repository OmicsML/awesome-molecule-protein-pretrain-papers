This repository is a collection of awesome papers about deep learning model for molecule and protein. If you have any suggestions (missing papers, issues, other resources), feel free to pull a request or email me at [qiaolinlu99@gmail.com](mailto:qiaolinlu99@gmail.com).

# awesome-pretrain-molecule-protein-papers

- [awesome-pretrain-molecule-protein-papers](#awesome-pretrain-molecule-protein-papers)
- [Molecule](#molecule)
  - [Survey](#survey)
  - [Molecule Pretrain Model / Representation Learning](#molecule-pretrain-model--representation-learning)
  - [Molecule Generative Model](#molecule-generative-model)
  - [Molecule Protein Docking Model](#molecule-protein-docking-model)
  - [Tetrahedral Molecular Geometry](#tetrahedral-molecular-geometry)
  - [Chemical Reaction](#chemical-reaction)
  - [Drug Discovery](#drug-discovery)
  - [Chemistry Toolkits](#chemistry-toolkits)
  - [Molecule Dataset](#molecule-dataset)
  - [Materials](#materials)
  - [Molecular Dynamics](#molecular-dynamics)
- [Protein](#protein)
  - [Protein Pretrain Model / Representation Learning](#protein-pretrain-model--representation-learning)
  - [Protein Evolution](#protein-evolution)
  - [Protein Protein Docking Model](#protein-protein-docking-model)
  - [Protein Generative Model](#protein-generative-model)
  - [Protein Dataset](#protein-dataset)
- [3D Model](#3d-model)
  - [Equivariant Model](#equivariant-model)

# Molecule
## Survey
1. [2022 Current Opinion in Structural Biology] **Deep learning approaches for de novo drug design: An overview** [[paper]](https://doi.org/10.1016/j.sbi.2021.10.001)
2. [2022 arXiv] **Geometrically Equivariant Graph Neural Networks: A Survey** [[paper]](https://arxiv.org/pdf/2202.07230.pdf)
3. [2022 arXiv] **MolGenSurvey:A Systematic Survey in Machine Learning Models for Molecule Design** [[paper]](https://arxiv.org/abs/2203.14500)
4. [2023 Engineering] **Machine Learning for Chemistry: Basics and Applications** [[paper]](https://www.sciencedirect.com/science/article/pii/S2095809923002813)
5. [2023 IJCAI] **A Systematic Survey of Chemical Pre-trained Models** [[paper]](https://sxkdz.github.io/files/publications/IJCAI/CPM/CPM.pdf)[[code]](https://github.com/junxia97/awesome-pretrain-on-molecules)
6. [2023 Wiley] **Generative models for molecular discovery: Recent advances and challenges** [[paper]](https://wires.onlinelibrary.wiley.com/doi/full/10.1002/wcms.1608)
7. [2024 arXiv] **A Survey of Geometric Graph Neural Networks: Data Structures, Models and Applications** [[paper]](https://arxiv.org/pdf/2403.00485.pdf)
## Molecule Pretrain Model / Representation Learning

1. [2023 ICLR] **Uni-Mol: A Universal 3D Molecular Representation Learning Framework** [[paper]](https://openreview.net/forum?id=6K2RM6wVqKu)[[code]](https://github.com/dptech-corp/Uni-Mol.)
2. [2023 ICLR] **One Transformer Can Understand Both 2D & 3D Molecular Data** [[paper]](https://arxiv.org/pdf/2210.01765.pdf)[[code]](https://github.com/lsj2408/Transformer-M)
3. [2023 KDD] **Automated 3D Pre-Training for Molecular Property Prediction** [[paper]](https://arxiv.org/pdf/2306.07812.pdf)[[code]](https://github.com/LARS-research/3D-PGT)
4. [2022 KDD] **Unified 2D and 3D Pre-Training of Molecular Representations** [[paper]](https://arxiv.org/pdf/2207.08806.pdf)[[code]](https://github.com/teslacool/UnifiedMolPretrain)
5. [2023 KDD] **Dual-view Molecule Pre-training** [[paper]](https://dl.acm.org/doi/pdf/10.1145/3580305.3599317)[[code]](https://github.com/microsoft/DVMP)
6. [2022 arXiv] **CoSP: Co-supervised pretraining of pocket and ligand** [[paper]](https://arxiv.org/pdf/2206.12241.pdf)
7. [2022 Nature Machine Intelligence] **Molecular contrastive learning of representations via graph neural networks** [[paper]](https://arxiv.org/pdf/2102.10056.pdf)[[code]](https://github.com/yuyangw/MolCLR)
8. [2023 ICML] **Enhancing Activity Prediction Models in Drug Discovery with the Ability to Understand Human Language** [[paper]](https://openreview.net/forum?id=oeRMR0La70)
9. [Briefings in Bioinformatics] **MG-BERT: leveraging unsupervised atomic representation learning for molecular property prediction** [[paper]](https://www.researchgate.net/profile/Dong-Sheng-Cao/publication/351363304_MG-BERT_leveraging_unsupervised_atomic_representation_learning_for_molecular_property_prediction/links/609743a9458515d31507d9e2/MG-BERT-leveraging-unsupervised-atomic-representation-learning-for-molecular-property-prediction.pdf)[[code]](https://github.com/zhang-xuan1314/Molecular-graph-BERT)
10. [2021 NIPS] **Motif-based Graph Self-Supervised Learning for Molecular Property Prediction** [[paper]](https://arxiv.org/pdf/2110.00987.pdf)[[code]](https://github.com/zaixizhang/MGSSL)
11. [2022 ICLR] **Spherical Message Passing for 3D Molecular Graphs** [[paper]](https://openreview.net/pdf?id=givsRXsOt9r)[[code]](https://github.com/divelab/DIG)
12. [2022 NIPS] **ComENet: Towards Complete and Efficient Message Passing for 3D Molecular Graphs** [[paper]](https://openreview.net/pdf?id=mCzMqeWSFJ)[[code]](https://github.com/divelab/DIG)
13. [2022 Nvidia] **MegaMolBART** [[web-link]](https://docs.nvidia.com/launchpad/ai/clara-megamolbart/latest/clara-megamolbart-overview.html)[[code]](https://github.com/NVIDIA/MegaMolBART)
14. [2020 NIPS workshop] **Message Passing Networks for Molecules with Tetrahedral Chirality** [[paper]](https://arxiv.org/pdf/2012.00094.pdf)[[code]](https://github.com/PattanaikL/chiral_gnn)
15. [2023 arXiv] **Augmenting large language models with chemistry tools** [[paper]](https://arxiv.org/pdf/2304.05376.pdf)[[code]](https://github.com/ur-whitelab/chemcrow-public)
16. [2023 ICML workshop] **Extracting Molecular Properties from Natural Language with Multimodal Contrastive Learning** [[paper]](https://arxiv.org/pdf/2307.12996.pdf)

## Molecule Generative Model
1. [2021 NIPS] **Geomol: Torsional geometric generation of molecular 3d conformer ensembles** [[paper]](https://proceedings.neurips.cc/paper/2021/file/725215ed82ab6306919b485b81ff9615-Paper.pdf)[[code]](https://github.com/PattanaikL/GeoMol)
2. [2021 NIPS] **Predicting molecular conformation via dynamic graph score matching**
3. [2021 ICML] **GraphDF: A Discrete Flow Model for Molecular Graph Generation** [[paper]](https://proceedings.mlr.press/v139/luo21a.html)[[code]](https://github.com/divelab/DIG)
4. [2023 ICLR workshop] **Improving Small Molecule Generation using Mutual Information Machine** [[paper]](https://openreview.net/forum?id=iOJlwUTUyrN)
5. [2020 KDD] **MoFlow: An Invertible Flow Model for Generating Molecular Graphs** [[paper]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403104)[[code]](https://github.com/calvin-zcx/moflow)
6. [2022 ICLR] **Geodiff: A geometric diffusion model for molecular conformation generation** [[paper]](https://arxiv.org/pdf/2203.02923.pdf)[[code]](https://github.com/MinkaiXu/GeoDiff)
7. [2022 ICML] **Equivariant Diffusion for Molecule Generation in 3D** [[paper]](https://arxiv.org/pdf/2203.17003.pdf)[[code]](https://github.com/ehoogeboom/e3_diffusion_for_molecules)
8. [2022 NIPS] **Torsional Diffusion for Molecular Conformer Generation** [[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/994545b2308bbbbc97e3e687ea9e464f-Paper-Conference.pdf)[[code]](https://github.com/gcorso/torsional-diffusion)
9. [2022 ICLR] **An Autoregressive Flow Model for 3D Molecular Geometry Generation from Scratch** [[paper]](https://openreview.net/pdf?id=C03Ajc-NS5W)[[code]](https://github.com/divelab/DIG)
10. [2022 Research Square] **Accurate Protein-Ligand Complex Structure Prediction using Geometric Deep Learning** [[paper]](https://assets.researchsquare.com/files/rs-1454132/v1_covered.pdf?c=1647883536)[[code]](https://github.com/KeleiHe/LigPose)
11. [2022 arXiv] **BARTSmiles: Generative Masked Language Models for Molecular Representations** [[paper]](https://arxiv.org/abs/2211.16349)[[code]](https://github.com/YerevaNN/BARTSmiles/)
12. [2023 ICLR] **Diffdock: Diffusion steps, twists, and turns for molecular docking** [[paper]](https://arxiv.org/pdf/2210.01776.pdf%3C/p%3E)[[code]](https://github.com/gcorso/DiffDock)
13. [2023 ICLR] **De novo molecular generation via connection-aware motif mining** [[paper]](https://arxiv.org/pdf/2302.01129.pdf)[[code]](https://github.com/MIRALab-USTC/AI4Sci-MiCaM)
14. [2023 ICML] **MolDiff: Addressing the Atom-Bond Inconsistency Problem in 3D Molecule Diffusion Generation** [[paper]](https://arxiv.org/pdf/2305.07508.pdf)[[code]](https://github.com/pengxingang/MolDiff)
15. [2023 ICML] **Geometric Latent Diffusion Models for 3D Molecule Generation** [[paper]](https://arxiv.org/pdf/2305.01140.pdf)[[code]](https://github.com/MinkaiXu/GeoLDM)
16. [2023 ICLR] **Conditional antibody design as 3d equivariant graph translation** [[paper]](https://arxiv.org/pdf/2208.06073.pdf)[[code]](https://github.com/THUNLP-MT/MEAN)
17. [2023 bioRxiv] **Guided Diffusion for molecular generation with interaction prompt** [[paper]](https://www.biorxiv.org/content/10.1101/2023.09.11.557141v1.abstract)
18. [2023 Nature Machine Intelligence] **ResGen is a pocket-aware 3D molecular generation model based on parallel multiscale modelling** [[paper]](https://www.nature.com/articles/s42256-023-00712-7)[[code]](https://github.com/HaotianZhangAI4Science/ResGen)
19. [2023 Nature Computational Science] **Learning on topological surface and geometric structure for 3D molecular generation** [[paper]](https://www.nature.com/articles/s43588-023-00530-2)[[code]](https://github.com/HaotianZhangAI4Science/SurfGen)
20. [2023 arXiv] **Accurate transition state generation with an object-aware equivariant elementary reaction diffusion model** [[paper]](https://arxiv.org/pdf/2304.06174.pdf)
21. [2023 Nature Computational Science] **Guided diffusion for inverse molecular design** [[paper]](https://www.nature.com/articles/s43588-023-00532-0)[[code]](https://gitlab.com/porannegroup/gaudi)
22. [2023 JACS] **Generative Models as an Emerging Paradigm in the Chemical Sciences** [[paper]](https://pubs.acs.org/doi/10.1021/jacs.2c13467)
23. [2023 arXiv] **Generating Molecular Conformer Fields** [[paper]](https://arxiv.org/abs/2311.17932)
24. [2023 ICLR] **Retrieval-based Controllable Molecule Generation** [[paper]](https://arxiv.org/abs/2208.11126)[[code]](https://github.com/NVlabs/RetMol)
25. [2024 ICLR] **Unified Generative Modeling of 3D Molecules with Bayesian Flow Networks** [[paper]](https://openreview.net/forum?id=NSVtmmzeRB)
26. [2024 ICLR] **Training-free Multi-objective Diffusion Model for 3D Molecule Generation** [[paper]](https://openreview.net/forum?id=X41c4uB4k0)
27. [2024 Nature Machine Intelligence] **Generation of 3D molecules in pockets via a language model** [[paper]](https://github.com/stonewiseAIDrugDesign/Lingo3DMol)


## Molecule Protein Docking Model

1. [2015 Bioinformatics] **Fast, accurate, and reliable molecular docking with QuickVina 2** [[paper]](https://academic.oup.com/bioinformatics/article/31/13/2214/195750)
2. [2016 JCIM] **Protein-Ligand Scoring with Convolutional Neural Networks** [[paper]](https://arxiv.org/pdf/1612.02751.pdf)
3. [2017 Scientific Reports] **Protein-Ligand Blind Docking Using QuickVina-W With Inter-Process Spatio-Temporal Integration** [[paper]](https://www.nature.com/articles/s41598-017-15571-7)
4. [2018 Journal of Cheminformatics] **P2Rank: machine learning based tool for rapid and accurate prediction of ligand binding sites from protein structure** [[paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0285-8)[[code]](http://github.com/rdk/p2rank)
5. [2018 IJCAI] **Interpretable drug target prediction using deep neural representation** [[paper]](https://www.ijcai.org/proceedings/2018/0468.pdf)
6. [2019 JCIM] **Are the Apo Proteins Suitable for the Rational Discovery of Allosteric Drugs?** [[paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.8b00735)
7. [2020 Journal of Cheminformatics] **Edock: blind protein–ligand docking by replica-exchange monte carlo simulation** [[paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00440-9)[[web-link]](https://seq2fun.dcmb.med.umich.edu//EDock/)
8. [2020 Journal of Cheminformatics] **spyrmsd: symmetry-corrected RMSD calculations in Python** [[paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00455-2)[[code]](https://github.com/RMeli/spyrmsd)
9. [2021 Journal of Cheminformatics] **GNINA 1.0: molecular docking with deep learning** [[paper]](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00522-2)[[code]](https://github.com/gnina/gnina)
10. [2021 Briefings in Bioinformatics] **InstaDock: A single-click graphical user interface for molecular docking-based virtual high-throughput screening** [[paper]](https://doi.org/10.1093/bib/bbaa279)[[web-link]](https://www.hassanlab.org/instadock)
11. [2021 Nature Machine Intelligence] **A geometric deep learning approach to predict binding conformations of bioactive molecules** [[paper]](https://www.nature.com/articles/s42256-021-00409-9)[[code]](https://github.com/OptiMaL-PSE-Lab/DeepDock)
12. [2022 ICML] **EQUIBIND: Geometric Deep Learning for Drug Binding Structure Prediction** [[paper]](https://proceedings.mlr.press/v162/stark22b/stark22b.pdf)[[code]](https://github.com/HannesStark/EquiBind)
13. [2022 NIPS] **TANKBind: Trigonometry-Aware Neural NetworKs for Drug-Protein Binding Structure Prediction** [[paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/2f89a23a19d1617e7fb16d4f7a049ce2-Paper-Conference.pdf)[[code]](https://github.com/luwei0917/TankBind)
14. [2022 Molecular Systems Biology] **Benchmarking AlphaFold-enabled molecular docking predictions for antibiotic discovery** [[paper]](https://www.embopress.org/doi/full/10.15252/msb.202211081)
15. [2022 arXiv] **CoSP: Co-supervised pretraining of pocket and ligand** [[paper]](https://arxiv.org/pdf/2206.12241.pdf)
16. [2023 ICLR] **Diffdock: Diffusion steps, twists, and turns for molecular docking** [[paper]](https://arxiv.org/pdf/2210.01776.pdf%3C/p%3E)[[code]](https://github.com/gcorso/DiffDock)
17. [2023 ICLR] **E3Bind: An End-to-End Equivariant Network for Protein-Ligand Docking** [[paper]](https://arxiv.org/pdf/2210.06069.pdf)
18. [2023 PNAS] **Contrastive learning in protein language space predicts interactions between drugs and protein targets** [[paper]](https://www.pnas.org/doi/abs/10.1073/pnas.2220778120)[[code]](https://github.com/samsledje/ConPLex_dev)
19. [2023 Nature Computer Science] **Efficient and accurate large library ligand docking with KarmaDock** [[paper]](https://www.nature.com/articles/s43588-023-00511-5)[[code]](https://github.com/schrojunzhang/KarmaDock)
20. [2023 JCIM] **BMaps: A Web Application for Fragment-Based Drug Design andCompound Binding Evaluation** [[paper]](https://pubs.acs.org/doi/full/10.1021/acs.jcim.3c00209)[[web-link]](https://www.boltzmannmaps.com/)
21. [2023 JCTC] **Equivariant Flexible Modeling of the Protein–Ligand Binding Pose with Geometric Deep Learning** [[paper]](https://pubs.acs.org/doi/epdf/10.1021/acs.jctc.3c00273)[[code]](https://github.com/tiejundong/FlexPose)
22. [2023 arXiv] **Generalist Equivariant Transformer Towards 3D Molecular Interaction Learning** [[paper]](https://arxiv.org/pdf/2306.01474.pdf)
23. [2023 Openreview] **The Discovery of Binding Modes Requires Rethinking Docking Generalization** [[paper]](https://openreview.net/pdf?id=UfBIxpTK10)
24. [2023 Openreview] **Protein-Ligand Interaction Prior for Binding-aware 3D Molecule Diffusion Models** [[paper]](https://openreview.net/forum?id=qH9nrMNTIW)
25. [2023 arXiv] **Generating Molecular Fragmentation Graphs with Autoregressive Neural Networks** [[paper]](https://arxiv.org/pdf/2304.13136.pdf)[[code]](https://github.com/samgoldman97/ms-pred)

## Tetrahedral Molecular Geometry

1. [2020 NIPS workshop] **Message Passing Networks for Molecules with Tetrahedral Chirality** [[paper]](https://arxiv.org/pdf/2012.00094.pdf)[[code]](https://github.com/PattanaikL/chiral_gnn)
2. [2023 Nature Reviews Chemistry] **Detection and analysis of chiral molecules as disease biomarkers** [[paper]](https://www.nature.com/articles/s41570-023-00476-z)

## Chemical Reaction
1. [2018 Nature] **Planning chemical syntheses with deep neural networks and symbolic AI** [[paper]](https://www.nature.com/articles/nature25978)[[code-nonofficial]](https://github.com/linminhtoo/neuralsym)
2. [2020 JCIM] **Predicting Retrosynthetic Reaction using Self-Corrected Transformer Neural Networks** [[paper]](https://pubs.acs.org/doi/full/10.1021/acs.jcim.9b00949)[[code]](https://github.com/Jh-SYSU/SCROP)
3. [2020 Chemical Science] **Automatic retrosynthetic route planning using template-free models** [[paper]](https://pubs.rsc.org/en/content/articlehtml/2020/sc/c9sc03666k)[[code]](https://github.com/PKUMDL-AI/AutoSynRoute)
4. [2023 Nature Communications] **Retrosynthesis prediction with an interpretable deep-learning framework based on molecular assembly tasks** [[paper]](https://www.nature.com/articles/s41467-023-41698-5)[[code]](https://github.com/wangyu-sd/RetroExplainer)
5. [2023 Nature Machine Intelligence] **Bridging the Gap between Chemical Reaction Pretraining and Conditional Molecule Generation with a Unified Model** [[paper]](https://www.nature.com/articles/s42256-023-00764-9)[[code]](https://github.com/qiangbo1222/Uni-RXN-official)
6. [2024-ICLR] **RetroBridge: Modeling Retrosynthesis with Markov Bridges** [[paper]](https://arxiv.org/abs/2308.16212)

## Drug Discovery
1. [2021 JCIM] **OpenChem: A Deep Learning Toolkit for Computational Chemistry and Drug Design** [[paper]](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.0c00971)
1. [2023 Nature Communications] **Discovery of senolytics using machine learning** [[paper]](https://www.nature.com/articles/s41467-023-39120-1)[[code]](https://zenodo.org/record/7870357)
2. [2023 ICML] **Drug Discovery under Covariate Shift with Domain-Informed Prior Distributions over Functions** [[paper]](https://openreview.net/pdf?id=BbZVFj0QPv)[[code]](https://github.com/leojklarner/Q-SAVI)
3. [2023 Current Opinion in Structural Biology] **Structure-based drug design with geometric deep learning** [[paper]](https://www.sciencedirect.com/science/article/pii/S0959440X23000222)
4. [2023 Openreview] **Drug Discovery with Dynamic Goal-aware Fragments** [[paper]](https://openreview.net/forum?id=sLGliHckR8)
5. [2023 ICML] **DecompDiff: Diffusion Models with Decomposed Priors for Structure-Based Drug Design** [[paper]](https://openreview.net/forum?id=9qy9DizMlr)[[code]](https://github.com/bytedance/DecompDiff)
6. [2023 Openreview] **Streamlining Generative Models for Structure-Based Drug Design** [[paper]](https://openreview.net/forum?id=8DLVrWL78S)
7. [2023 Openreview] **Long-Short-Range Message-Passing: A Fragmentation-Based Framework to Capture Non-Local Atomistic Interactions** [[paper]](https://openreview.net/forum?id=rvDQtdMnOl)
8. [2023 ACS Central Science] **Geometric Deep Learning for Structure-Based Ligand Design** [[paper]](https://doi.org/10.1021/acscentsci.3c00572)
9. [2023 ICLR] **De Novo Molecular Generation via Connection-aware Motif Mining** [[paper]](https://arxiv.org/abs/2302.01129)[[code]](https://github.com/MIRALab-USTC/AI4Sci-MiCaM)
10. [2023 NIPS] **Tartarus: A benchmarking platform for realistic and practical inverse molecular design** [[paper]](https://arxiv.org/abs/2209.12487) [[code]](https://github.com/aspuru-guzik-group/Tartarus)
11. [2023 arXiv] **ChatGPT-powered Conversational Drug Editing Using Retrieval and Domain Feedback** [[paper]](https://arxiv.org/pdf/2305.18090.pdf)[[code]](https://github.com/chao1224/ChatDrug)
12. [2023 ACS Central Science] **2023-ACS Central Science / Geometric Deep Learning for Structure-Based Ligand Design** [[paper]](https://pubs.acs.org/doi/full/10.1021/acscentsci.3c00572)
13. [2023 Wiley] **Generative models for molecular discovery: Recent advances and challenges** [[paper]](https://wires.onlinelibrary.wiley.com/doi/full/10.1002/wcms.1608)

## Chemistry Toolkits

1. [RDKit](http://www.rdkit.org/): **Open-source cheminformatics software**
2. [PyMOL](https://pymol.org/2/): **A user-sponsored molecular visualization system on an open-source foundation**
3. [CDK](https://cdk.github.io/): **Chemistry Development Kit (Open Source modular Java libraries for Cheminformatics)**
4. [Open Babel](http://openbabel.org/wiki/Main_Page): **The Open Source Chemistry Toolbox**
5. [Cinfony](https://cinfony.github.io/): **A common API to several cheminformatics toolkits**
6. [Indigo](https://lifescience.opensource.epam.com/indigo/index.html): **A universal molecular toolkit that can be used for molecular fingerprinting, substructure search, and molecular visualization**
7. [ChemoPy](https://github.com/ifyoungnet/Chemopy): **A freely available python package for computational biology and chemoinformatics**
8. [ChemmineR](https://www.bioconductor.org/packages/release/bioc/html/ChemmineR.html): **A cheminformatics package for analyzing drug-like small molecule data in R**
9. [ChemKit](https://github.com/kylelutz/chemkit): **An open source software library for chemistry**
10. [DeepChem](https://deepchem.io/): **A Python library for machine learning and deep learning on molecular and quantum datasets**
11. [MolVS](https://molvs.readthedocs.io/en/latest/): **Molecular Validation and Standardization**
12. [spyrmsd](https://spyrmsd.readthedocs.io/en/develop/): **spyrmsd: symmetry-corrected RMSD calculations in Python**
13. [torchdrug](https://torchdrug.ai/): **A machine learning platform designed for drug discovery**
14. [torchprotein](https://torchprotein.ai/): **A machine learning library for protein science, built on top of TorchDrug**
15. [OpenChem](https://deepchem.io/): **A deep learning toolkit for computational chemistry and drug design**
## Molecule Dataset

1. [2012 JCIM] **Enumeration of 166 billion organic small molecules in the chemical universe database GDB-17** [[paper]](https://pubs.acs.org/doi/10.1021/ci300415d)
2. [2015 JCIM] **ZINC 15 – Ligand Discovery for Everyone** [[paper]](https://pubs.acs.org/doi/full/10.1021/acs.jcim.5b00559)
3. [2016 Nucleic Acids Research] **PubChem Substance and Compound databases**
4. [2017 Science Advances] **Machine learning of accurate energy-conserving molecular force fields** [[paper]](https://www.science.org/doi/10.1126/sciadv.1603015)[[data-link]](http://quantum-machine.org/datasets/)
5. [2018 Nucleic Acids Research] **ChEMBL: towards direct deposition of bioassay data** [[paper]](https://academic.oup.com/nar/article/47/D1/D930/5162468)
6. [2018 Nucleic Acids Research] **DrugBank 5.0: a major update to the DrugBank database for 2018** [[paper]](https://academic.oup.com/nar/article/46/D1/D1074/4602867)
7. [2018 JCIM] **Comparative Assessment of Scoring Functions: The CASF-2016 Update** [[paper]](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.8b00545)[[web-link]](http://www.pdbbind.org.cn/casf.php)
8. [2019 JCIM] **GuacaMol: Benchmarking Models for De Novo Molecular Design** [[paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.8b00839)[[code]](https://github.com/BenevolentAI/guacamol)[[web-link]](https://benevolent.ai/guacamol)
9. [2023 arXiv] **Towards Foundational Models for Molecular Learning on Large-Scale Multi-Task Datasets** [[paper]](https://arxiv.org/pdf/2310.04292v2.pdf)


|                                                 Dataset Name                                                 |  #Molecules  |                   Property                   |                       About Data                       |
| :-----------------------------------------------------------------------------------------------------------: | :-----------------: | :-------------------------------------------: | :-----------------------------------------------------: |
|                                    [GDB-17](https://gdb.unibe.ch/downloads/)                                    |        166B        |           small organical molecules           |               chemical universe database               |
| [QM9](https://figshare.com/collections/Quantum_chemistry_structures_and_properties_of_134_kilo_molecules/978904) |       133,885       |          quantum chemical properties          |                   a subset of GDB-17                   |
|                                      [ZINC15](https://zinc15.docking.org/)                                      | 230M(3D), over 750M |        bioactivity of small molecules        |          biologically relevant small molecules          |
|                               [GuacaMol](https://github.com/BenevolentAI/guacamol)                               |         N/A         |   benchmark suite for generative chemistry   |     a subset of molecules extracted from ChEMBL 24     |
|                                     [ChEMBL](https://www.ebi.ac.uk/chembl/)                                     |        2.4M        | bioactive molecules with drug-like properties |     contains chemical, bioactivity and genomic data     |
|                              [PubChem BioAssay](https://pubchem.ncbi.nlm.nih.gov/)                              |     270,998,024     |               PubChem BioAssay               |                   a subset of PubChem                   |
|                              [PubChem Compound](https://pubchem.ncbi.nlm.nih.gov/)                              |      1,366,263      |               PubChem Compound               |                   a subset of PubChem                   |
|                              [PubChem Substance](https://pubchem.ncbi.nlm.nih.gov/)                              |     109,891,994     |               PubChem Substance               |                   a subset of PubChem                   |
|                                     [DrugBank 5.0](https://go.drugbank.com/)                                     |         N/A         |                   drug data                   |       bioinformatics and cheminformatics database       |
|                                 [GEOM-Drugs](https://doi.org/10.7910/DVN/JNGTDF)                                 |      430,00 0      |                   drug data                   | a larger scale dataset of molecular conformers than QM9 |
<!-- |CrossDocked2020| -->
<!-- |[PDBBind](http://www.pdbbind.org.cn/index.php?action=showall)| 23,496 biomolecular complexes | binding affinity data (protein-protein, protein-ligand, protein-acid)| a subset of PDB database | 
| [MD17](https://archive.materialscloud.org/record/2020.82)| ||| -->

## Materials
1. [2023 Openreview] **Crystalformer: Infinitely Connected Attention for Periodic Structure Encoding** [[paper]](https://openreview.net/forum?id=fxQiecl9HB)
2. [2023 Openreview] **Scalable Diffusion for Materials Generation** [[paper]](https://openreview.net/forum?id=wm4WlHoXpC)
3. [2023 Openreview] **MOFDiff: Coarse-grained Diffusion for Metal-Organic Framework Design** [[paper]](https://openreview.net/forum?id=0VBsoluxR2)
4. [2023 JACS] **MOFormer: Self-Supervised Transformer Model for Metal–Organic Framework Property Prediction** [[paper]](https://pubs.acs.org/doi/full/10.1021/jacs.2c11420)[[code]](https://github.com/zcao0420/MOFormer)

## Molecular Dynamics
1. [2023 arXiv] **Score dynamics: scaling molecular dynamics with picoseconds timestep via conditional diffusion model** [[paper]](https://arxiv.org/pdf/2310.01678.pdf)[[code]](https://github.com/llnl/graphite)
# Protein

## Protein Pretrain Model / Representation Learning

1. [2020 bioRxiv] **Transformer protein language models are unsupervised structure learners** [[paper]](https://www.biorxiv.org/content/10.1101/2020.12.15.422761v1.full.pdf)[[code]](https://github.com/facebookresearch/esm)
2. [2021 PNAS] **Biological Structure and Function Emerge from Scaling Unsupervised Learning to 250 Million Protein Sequences** [[paper]](https://www.pnas.org/doi/abs/10.1073/pnas.2016239118)[[code]](https://github.com/facebookresearch/esm)
3. [2021 ICML] **MSA Transformer** [[paper]](http://proceedings.mlr.press/v139/rao21a/rao21a.pdf)[[code]](https://github.com/facebookresearch/esm)
4. [2021 NIPS] **Language models enable zero-shot prediction of the effects of mutations on protein function** [[paper]](https://proceedings.neurips.cc/paper_files/paper/2021/file/f51338d736f95dd42427296047067694-Paper.pdf)[[code]](https://github.com/facebookresearch/esm)
5. [2021 Nature] **Highly accurate protein structure prediction with AlphaFold** [[paper]](https://www.nature.com/articles/s41586-021-03819-2)[[code]](https://github.com/deepmind/alphafold)
6. [2021 Science] **Accurate prediction of protein structures and interactions using a three-track neural network** [[paper]](https://www.science.org/doi/10.1126/science.abj8754)[[code]](https://github.com/RosettaCommons/RoseTTAFold)
7. [2022 ICML] **Learning inverse folding from millions of predicted structures** [[paper]](https://proceedings.mlr.press/v162/hsu22a/hsu22a.pdf)[[code]](https://github.com/deepmind/alphafold)
8. [2022 bioRxiv] **OpenFold: Retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization** [[paper]](https://www.biorxiv.org/content/10.1101/2022.11.20.517210v3.full.pdf)[[code]](https://github.com/aqlaboratory/openfold)
9. [2021 PNAS] **Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences** [[paper]](https://www.pnas.org/doi/abs/10.1073/pnas.2016239118)[[code]](https://github.com/facebookresearch/esm)
10. [2022 bioRxiv] **Language models of protein sequences at the scale of evolution enable accurate structure prediction** [[paper]](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1.full.pdf?utm_campaign=M2D2%20Community%20Round-Up&utm_medium=email&utm_source=Revue%20newsletter)
11. [2023 Science] **Evolutionary-scale prediction of atomic-level protein structure with a language model** [[paper]](https://www.science.org/doi/abs/10.1126/science.ade2574)[[code]](https://github.com/facebookresearch/esm)
12. [2022 Nature Communications] **ProtGPT2 is a deep unsupervised language model for protein design** [[paper]](https://www.nature.com/articles/s41467-022-32007-7)[[code]](https://huggingface.co/docs/transformers/main_classes/trainer)
13. [2023 bioRxiv] **xTrimoPGLM: Unified 100B-Scale Pre-trained Transformer for Deciphering the Language of Protein** [[paper]](https://www.biorxiv.org/content/10.1101/2023.07.05.547496v3)
14. [2023 arXiv] **Generative Pretrained Autoregressive Transformer Graph Neural Network applied to the Analysis and Discovery of Novel Proteins** [[paper]](https://arxiv.org/pdf/2305.04934.pdf)[[code]](https://github.com/lamm-mit/MateriomicTransformer)
15. [2023 bioRxiv] **Pretrainable Geometric Graph Neural Network for Antibody Affinity Maturation** [[paper]](https://www.biorxiv.org/content/10.1101/2023.08.10.552845v1.full.pdf)
16. [2023 Openreview] **Pre-training Sequence, Structure, and Surface Features for Comprehensive Protein Representation Learning** [[paper]](https://openreview.net/forum?id=BEH4mGo7zP)
17. [2023 ICLR] **Protein Representation Learning by Geometric Structure Pretraining** [[paper]](https://arxiv.org/abs/2203.06125)[[code]](https://github.com/DeepGraphLearning/GearNet)

## Protein Evolution 
1. [2023 Nature] **Clustering-predicted structures at the scale of the known protein universe** [[paper]](https://www.nature.com/articles/s41586-023-06510-w)

## Protein Protein Docking Model
1. [2020 Sturcture] **Performance and its limits in rigid body protein-protein docking** [[paper]](https://www.cell.com/structure/pdf/S0969-2126(20)30209-4.pdf)[[web-link]](https://cluspro.bu.edu/login.php)
2. [2020 Nature Protocols] **The HDOCK server for integrated protein–protein docking** [[paper]](https://www.nature.com/articles/s41596-020-0312-x)[[web-link]](http://hdock.phys.hust.edu.cn/)
3. [2021 bioRxiv] **Improved docking of protein models by a combination of alphafold2 and cluspro** [[paper]](https://www.biorxiv.org/content/10.1101/2021.09.07.459290v2.full.pdf)
4. [2022 ICLR] **Independent SE(3)-Equivariant Models for End-to-End Rigid Protein Docking** [[paper]](https://arxiv.org/pdf/2111.07786.pdf)[[code]](https://github.com/octavian-ganea/equidock_public)
## Protein Generative Model

1. [2023 ICLR] **Learning Hierarchical Protein Representations via Complete 3D Graph Networks** [[paper]](https://openreview.net/forum?id=9X-hgLDLYkQ)[[code]](https://github.com/divelab/DIG)
2. [2023 ICML] **Se(3) diffusion model with application to protein backbone generation** [[paper]](https://arxiv.org/pdf/2302.02277.pdf)[[code]](https://github.com/jasonkyuyim/se3_diffusion)
3. [2023 ICLR] **Diffusion probabilistic modeling of protein backbones in 3d for the motif- scaffolding problem** [[paper]](https://openreview.net/forum?id=6TxBxqNME1Y)[[code]](https://github.com/blt2114/ProtDiff_SMCDiff)
4. [2023 ICLR] **Protein sequence and structure co-design with equivariant translation** [[paper]](https://arxiv.org/pdf/2210.08761.pdf)
5. [2023 ICML] **SE(3) diffusion model with application to protein backbone generation** [[paper]](https://arxiv.org/pdf/2302.02277.pdf)[[code]](https://github.com/jasonkyuyim/se3_diffusion)
6. [2023 arXiv] **DiffPack: A Torsional Diffusion Model for Autoregressive Protein Side-Chain Packing** [[paper]](https://arxiv.org/pdf/2306.01794.pdf)
7. [2023 bioRxiv] **Protein generation with evolutionary diffusion: sequence is all you need** [[paper]](https://www.biorxiv.org/content/10.1101/2023.09.11.556673v1.abstract)
8. [2023 Openreview] **SE(3)-Stochastic Flow Matching for Protein Backbone Generation** [[paper]](https://openreview.net/forum?id=kJFIH23hXb)
9. [2023 Nature] **De novo design of protein structure and function with RFdiffusion** [[paper]](https://www.nature.com/articles/s41586-023-06415-8)[[code]](https://github.com/RosettaCommons/RFdiffusion)

## Protein Dataset

# 3D Model

## Equivariant Model

1. [2013 Doc] **Lie groups for 2d and 3d transformations** [[paper]](https://ethaneade.org/lie.pdf)
2. [2018 arXiv] **Tensor field networks: Rotation- and translation-equivariant neural networks for 3D point clouds** [[paper]](https://arxiv.org/pdf/1802.08219.pdf)[[code]](https://github.com/tensorfieldnetworks/tensorfieldnetworks)
3. [2019 NIPS] **Cormorant: Covariant Molecular Neural Networks** [[paper]](https://arxiv.org/abs/1906.04015)[[code]](https://github.com/risilab/cormorant)
4. [2020 NIPS] **SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks** [[paper]](https://arxiv.org/abs/2006.10503)[[code]](https://github.com/FabianFuchsML/se3-transformer-public)
5. [2021 ICML] **E(n) Equivariant Graph Neural Networks** [[paper]](http://proceedings.mlr.press/v139/satorras21a/satorras21a.pdf)[[code]](https://github.com/vgsatorras/egnn)
6. [2021 Nature Communications] **E(3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials** [[paper]](https://www.nature.com/articles/s41467-022-29939-5)[[code]](https://github.com/mir-group/nequip)
7. [2022 ICLR] **Geometric and Physical Quantities Improve E(3) Equivariant Message Passing** [[paper]](https://arxiv.org/abs/2110.02905)
8. [2022 ICLR workshop] **Denoising diffusion probabilistic models on so (3) for rotational alignment** [[paper]](https://openreview.net/pdf?id=BY88eBbkpe5)
9. [2022 arXiv] **e3nn: Euclidean Neural Networks** [[paper]](https://arxiv.org/pdf/2207.09453.pdf)
10. [2023 ICLR] **Equiformer: Equivariant Graph Attention Transformer for 3D Atomistic Graphs** [[paper]](https://arxiv.org/pdf/2206.11990.pdf)[[code]](https://github.com/atomicarchitects/equiformer)
11. [2024 ICLR] **Hybrid Directional Graph Neural Network for Molecules** [[paper]](https://openreview.net/forum?id=BBD6KXIGJL)[[code]](https://github.com/AnonymousACode/HDGNN)
