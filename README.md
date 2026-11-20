# PEKP

Collection of models, methods, and resources for predicting enzyme kinetic parameters (PEKP).

**Last literature update: 2026-11-20.** Earlier repository availability notes reflect inspections through 2026-10-01.

The four tables group methods by their reported targets: turnover number (kcat), Michaelis constant (Km), catalytic efficiency (kcat/Km), and inhibition constant (Ki). A method appears under each target it covers. Row notes identify derived ratios, mutation effects, and range classification. Years follow the journal publication where available, or the preprint or resource otherwise. The Ki table covers inhibition constants and excludes Kd and IC50 measurements.

Links identify papers, preprints, code, and data. Repository availability notes describe file inspections only. [Databases, benchmarks, and prediction services](#databases-benchmarks-and-prediction-services) are listed after the model tables.

## kcat

| Model / Method | Year | Links / notes |
| --- | ---: | --- |
| Heckmann et al. | 2018 | https://doi.org/10.1038/s41467-018-07652-6 |
| DLKcat | 2022 | [Paper](https://doi.org/10.1038/s41929-022-00798-z) · [Repository](https://github.com/SysBioChalmers/DLKcat) |
| UniKP | 2023 | [Paper](https://doi.org/10.1038/s41467-023-44113-1) · [Repository](https://github.com/Luo-SynBioLab/UniKP) |
| TurNuP | 2023 | [Paper](https://doi.org/10.1038/s41467-023-39840-4) · [Repository](https://github.com/AlexanderKroll/kcat_prediction) |
| DeepEnzyme | 2024 | [Paper](https://doi.org/10.1093/bib/bbae409) · [Repository](https://github.com/hongzhonglu/DeepEnzyme) |
| DLTKcat | 2024 | [Paper](https://doi.org/10.1093/bib/bbad506) · [Repository](https://github.com/SizheQiu/DLTKcat) |
| EITLEM-Kinetics | 2024 | [Paper](https://doi.org/10.1016/j.checat.2024.101094) · [Repository](https://github.com/XvesS/EITLEM-Kinetics) |
| MPEK | 2024 | [Paper](https://doi.org/10.1093/bib/bbae387) · [Repository](https://github.com/kotori-y/mpek) |
| ECEP | 2024 | [Paper](https://doi.org/10.3389/frai.2024.1446063) · [Repository](https://github.com/misharisaud/ECEP) |
| ENKIE | 2024 | [Paper](https://doi.org/10.1093/bioinformatics/btae652) · [Repository](https://gitlab.com/csb.ethz/enkie) |
| PreTKcat | 2025 | [Paper](https://doi.org/10.1016/j.compbiolchem.2024.108327) · [Repository](https://github.com/MrVincentCai/PreTKcat) |
| NNKcat | 2025 | [Paper](https://doi.org/10.1093/bib/bbaf212) · [Repository](https://github.com/Jiczh/NNKcat); no README; some referenced assets absent from checked tree |
| GELKcat | 2025 | https://doi.org/10.1016/j.ymeth.2025.02.010 |
| MMKcat | 2025 | [Paper](https://www.sciencedirect.com/science/article/pii/S0010482525006997) · [Repository](https://github.com/ProEcho1/MMKcat) |
| ProKcat | 2025 | [Preprint](https://arxiv.org/abs/2509.11782) · [Repository](https://github.com/bozhenhhu/ProKcat); withdrawn from IJCAI 2025 proceedings (see arXiv comments) |
| TCNeKP | 2025 | [Paper](https://doi.org/10.1021/acs.jcim.5c01830) · [Repository](https://github.com/YuanyuanLei-TCNeKP/TCNeKP) |
| CatPred | 2025 | [Paper](https://doi.org/10.1038/s41467-025-57215-9) · [Repository](https://github.com/maranasgroup/CatPred) |
| EnzyCLIP | 2025 | [Preprint](https://arxiv.org/abs/2512.00379) |
| OmniESI | 2025 | [Preprint](https://arxiv.org/abs/2506.17963) · [Repository](https://github.com/Hong-yu-Zhang/OmniESI); former repository name: MESI |
| DEKP | 2025 | [Paper](https://doi.org/10.1093/bib/bbaf187) · [Repository](https://github.com/wang-yi-zhen/DEKP) |
| CataPro | 2025 | [Paper](https://doi.org/10.1038/s41467-025-58038-4) · [Repository](https://github.com/zchwang/CataPro) |
| CPI-Pred | 2025 | [Preprint](https://doi.org/10.1101/2025.01.16.633372) · [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC11785036/) |
| SAKPE | 2025 | [Preprint](https://doi.org/10.1101/2025.04.30.651216) · [Placeholder repository](https://github.com/HGzyme/SAKPE); title-only README, no code in checked tree |
| CatRange (formerly RealKcat) | 2026 | [Paper](https://doi.org/10.1093/pnasnexus/pgag309) · [Repository](https://github.com/TKAI-LAB-Mali/CatRange); kinetic-range classification (2025 RealKcat preprint) |
| KinForm | 2026 | [Paper](https://doi.org/10.1038/s41540-026-00692-5) · [Repository](https://github.com/Digital-Metabolic-Twin-Centre/KinForm) |
| ERBA | 2026 | [CVPR 2026 paper](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Multimodal_Protein_Language_Models_for_Enzyme_Kinetic_Parameters_From_Substrate_CVPR_2026_paper.html) · [arXiv](https://arxiv.org/abs/2603.12845) |
| O2DENet | 2026 | [Paper](https://doi.org/10.1021/acs.jcim.5c03204) · [Repository](https://github.com/blackjack534/O2DENet) (formerly AuESINet); referenced requirements.txt absent from checked tree |
| EnzymePlex | 2026 | [Preprint](https://doi.org/10.64898/2026.03.04.709726); full source not reverified in this update |
| UniKineG | 2026 | [Paper](https://doi.org/10.3390/ijms27041731) · [Data](https://zenodo.org/records/18125285) |
| PMAK | 2026 | [Paper](https://doi.org/10.1038/s42003-026-09551-9) · [Repository](https://github.com/MrVincentCai/PMAK); referenced supplement directory absent from checked tree |
| KcatNet | 2026 | [Paper](https://doi.org/10.1186/s13059-026-03986-3) · [Repository](https://github.com/BioColLab/KcatNet) |
| GraphKcat | 2026 | [Paper](https://doi.org/10.1021/acscatal.6c03874) · [Repository](https://github.com/ld139/GraphKcat) |
| GO-HKP | 2026 | [Paper](https://doi.org/10.1016/j.simpa.2025.100803) · [Repository](https://github.com/tibbdc/GO-HKP) |
| EnzCast | 2026 | [Preprint](https://doi.org/10.64898/2026.04.28.721430) |
| ENZYME-UNIFIED | 2026 | [Manuscript](https://openreview.net/pdf?id=oTnFATrtCD); marked under review, acceptance not verified |
| KcatNeuroCortex | 2026 | [Paper](https://doi.org/10.1016/j.enzmictec.2026.110915) · [Colab](https://colab.research.google.com/drive/11QqYBL1Csyyu-uRX4b-LsceaeVRR7TeF); historical notebook: required Drive download links not found in the cutoff review; not rechecked on 2026-10-01 |
| DeltaKcat | 2026 | [Preprint](https://doi.org/10.65215/LTSpreprints.2026.05.19.000247) · [Original repository link](https://github.com/LiLabTsinghua/DeltaKcat) (unavailable when checked); relative changes between enzyme–substrate pairs |
| iESC | 2026 | https://doi.org/10.1016/j.biortech.2026.134067 |
| CatESO | 2026 | [Paper](https://doi.org/10.1021/jacs.6c14365) · [Repository](https://github.com/zhenjiagan/CatESO) · [Earlier preprint](https://doi.org/10.64898/2026.07.04.736506) |
| EnzGFM (UniKP downstream) | 2026 | [Paper](https://doi.org/10.1038/s41467-026-75283-3) · [Repository](https://github.com/DeepBxM/EnzGFM); enzyme-specific backbone with downstream kinetic regressors |
| GAPEK / GAPEK+ | 2026 | [Paper](https://doi.org/10.1021/acs.jcim.6c02546) · [Repository](https://github.com/Zach-NTU/GAPEK); repository marked pre-release; code present, referenced inference checkpoint not found in checked tree |
| KinEAGER | 2026 | [Paper](https://doi.org/10.1021/acs.jcim.6c02075); official code attribution not verified |
| Interkcat | 2026 | [Preprint](https://arxiv.org/abs/2609.24157) · [Repository](https://github.com/ZWR0/Interkcat); code present, referenced inference checkpoint not found in checked tree |
| MCKcat | 2026 | [Paper](https://doi.org/10.1002/advs.77789) · [Repository](https://github.com/gefengya/MCKcat) |
| PIMetaKcat | 2026 | [Paper](https://doi.org/10.1021/acs.jcim.6c00032) · [Paper-linked repository](https://github.com/QiTiaotiao2/PIMetaKcat) (404 when checked); temperature-dependent kcat |
| AUKAT | 2026 | [Paper](https://doi.org/10.3390/biom16071049) · [Repository](https://github.com/MengLiu90/AUKCAT-Neural-Network-Model-for-Kcat-Prediction); repository spells AUKCAT; Git LFS checkpoints, full payloads not verified |
| Katalyst | 2026 | [Paper](https://doi.org/10.1093/bioinformatics/btag709) · [Repository](https://github.com/liruilin-SUAT/Katalyst) · Predicts kcat from enzyme sequences, protein descriptions, substrates, and products. |
| DeltaCata | 2026 | [Paper](https://doi.org/10.1038/s41467-026-79287-x) · [Repository](https://github.com/biomed-AI/DeltaCata) · Predicts the change in kcat between a mutant and its wild type using paired measurements under matched conditions. |
| KineCouple | 2026 | [Preprint (v2)](https://arxiv.org/abs/2611.09377v2) · Uses substrate-conditioned pooling of protein residues to predict log(kcat). |
| SKiP | 2026 | [Paper](https://doi.org/10.1186/s13321-026-01333-z) · [Repository](https://github.com/Sowmya-R-Krishnan/SKiP) · Predicts turnover from enzyme–substrate complex structures, accounting for pH and cofactor interactions. |

## Km

| Model / Method | Year | Links / notes |
| --- | ---: | --- |
| Kroll-KM | 2021 | [Paper](https://doi.org/10.1371/journal.pbio.3001402) · [Repository](https://github.com/AlexanderKroll/KM_prediction) |
| MLAGO | 2022 | https://doi.org/10.1186/s12859-022-05009-x |
| UniKP | 2023 | [Paper](https://doi.org/10.1038/s41467-023-44113-1) · [Repository](https://github.com/Luo-SynBioLab/UniKP) |
| GraphKM | 2024 | [Paper](https://doi.org/10.1186/s12859-024-05746-1) · [Repository](https://github.com/realHXiao/GraphKM) |
| EITLEM-Kinetics | 2024 | [Paper](https://doi.org/10.1016/j.checat.2024.101094) · [Repository](https://github.com/XvesS/EITLEM-Kinetics) |
| MPEK | 2024 | [Paper](https://doi.org/10.1093/bib/bbae387) · [Repository](https://github.com/kotori-y/mpek) |
| ProSmith | 2024 | [Paper](https://doi.org/10.1371/journal.pcbi.1012100) · [Repository](https://github.com/AlexanderKroll/ProSmith) |
| ENKIE | 2024 | [Paper](https://doi.org/10.1093/bioinformatics/btae652) · [Repository](https://gitlab.com/csb.ethz/enkie) |
| DLERKm | 2025 | [Paper](https://doi.org/10.3390/app15074017) · [Repository](https://github.com/kaiwang-group/DLERKm) |
| TCNeKP | 2025 | [Paper](https://doi.org/10.1021/acs.jcim.5c01830) · [Repository](https://github.com/YuanyuanLei-TCNeKP/TCNeKP) |
| CatPred | 2025 | [Paper](https://doi.org/10.1038/s41467-025-57215-9) · [Repository](https://github.com/maranasgroup/CatPred) |
| EnzyCLIP | 2025 | [Preprint](https://arxiv.org/abs/2512.00379) |
| OmniESI | 2025 | [Preprint](https://arxiv.org/abs/2506.17963) · [Repository](https://github.com/Hong-yu-Zhang/OmniESI); former repository name: MESI |
| DEKP | 2025 | [Paper](https://doi.org/10.1093/bib/bbaf187) · [Repository](https://github.com/wang-yi-zhen/DEKP) |
| CataPro | 2025 | [Paper](https://doi.org/10.1038/s41467-025-58038-4) · [Repository](https://github.com/zchwang/CataPro) |
| CPI-Pred | 2025 | [Preprint](https://doi.org/10.1101/2025.01.16.633372) · [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC11785036/) |
| SAKPE | 2025 | [Preprint](https://doi.org/10.1101/2025.04.30.651216) · [Placeholder repository](https://github.com/HGzyme/SAKPE); title-only README, no code in checked tree |
| PreTKcat | 2025 | [Paper](https://doi.org/10.1016/j.compbiolchem.2024.108327) · [Repository](https://github.com/MrVincentCai/PreTKcat) |
| MMISA-KM | 2025 | [DDCLS 2025 paper](https://doi.org/10.1109/DDCLS66240.2025.11064981) · [Repository](https://github.com/kaiwang-group/MMISA-KM) |
| CatRange (formerly RealKcat) | 2026 | [Paper](https://doi.org/10.1093/pnasnexus/pgag309) · [Repository](https://github.com/TKAI-LAB-Mali/CatRange); kinetic-range classification (2025 RealKcat preprint) |
| KinForm | 2026 | [Paper](https://doi.org/10.1038/s41540-026-00692-5) · [Repository](https://github.com/Digital-Metabolic-Twin-Centre/KinForm) |
| GraphKcat | 2026 | [Paper](https://doi.org/10.1021/acscatal.6c03874) · [Repository](https://github.com/ld139/GraphKcat) |
| ERBA | 2026 | [CVPR 2026 paper](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Multimodal_Protein_Language_Models_for_Enzyme_Kinetic_Parameters_From_Substrate_CVPR_2026_paper.html) · [arXiv](https://arxiv.org/abs/2603.12845) |
| O2DENet | 2026 | [Paper](https://doi.org/10.1021/acs.jcim.5c03204) · [Repository](https://github.com/blackjack534/O2DENet) (formerly AuESINet); referenced requirements.txt absent from checked tree |
| EnzymePlex | 2026 | [Preprint](https://doi.org/10.64898/2026.03.04.709726); full source not reverified in this update |
| UniKineG | 2026 | [Paper](https://doi.org/10.3390/ijms27041731) · [Data](https://zenodo.org/records/18125285) |
| KmPred | 2026 | [Paper](https://doi.org/10.3389/frai.2026.1711471) · [Repository](https://github.com/misharisaud/KmPred) |
| EnzCast | 2026 | [Preprint](https://doi.org/10.64898/2026.04.28.721430) |
| ENZYME-UNIFIED | 2026 | [Manuscript](https://openreview.net/pdf?id=oTnFATrtCD); marked under review, acceptance not verified |
| DeltaKcat | 2026 | [Preprint](https://doi.org/10.65215/LTSpreprints.2026.05.19.000247) · [Original repository link](https://github.com/LiLabTsinghua/DeltaKcat) (unavailable when checked); relative changes between enzyme–substrate pairs |
| iESC | 2026 | https://doi.org/10.1016/j.biortech.2026.134067 |
| EnzGFM (UniKP downstream) | 2026 | [Paper](https://doi.org/10.1038/s41467-026-75283-3) · [Repository](https://github.com/DeepBxM/EnzGFM); enzyme-specific backbone with downstream kinetic regressors |
| GAPEK / GAPEK+ | 2026 | [Paper](https://doi.org/10.1021/acs.jcim.6c02546) · [Repository](https://github.com/Zach-NTU/GAPEK); repository marked pre-release; code present, referenced inference checkpoint not found in checked tree |
| KinEAGER | 2026 | [Paper](https://doi.org/10.1021/acs.jcim.6c02075); official code attribution not verified |
| AS4Km | 2026 | [Paper](https://doi.org/10.1039/D6DD00094K) · [Archived code](https://doi.org/10.5281/zenodo.20393126) · [Data](https://doi.org/10.5281/zenodo.20392157) · Uses residue-level active-site annotations to predict Km. |
| DeltaCata | 2026 | [Paper](https://doi.org/10.1038/s41467-026-79287-x) · [Repository](https://github.com/biomed-AI/DeltaCata) · Predicts the change in Km between a mutant and its wild type using paired measurements under matched conditions. |
| KineCouple | 2026 | [Preprint (v2)](https://arxiv.org/abs/2611.09377v2) · Trains a separate regression model for log(Km) using substrate-conditioned pooling. |
| SKiP | 2026 | [Paper](https://doi.org/10.1186/s13321-026-01333-z) · [Repository](https://github.com/Sowmya-R-Krishnan/SKiP) · Predicts Km from enzyme–substrate complex structures and estimates uncertainty for each prediction. |

## kcat/Km

| Model / Method | Year | Links / notes |
| --- | ---: | --- |
| UniKP | 2023 | [Paper](https://doi.org/10.1038/s41467-023-44113-1) · [Repository](https://github.com/Luo-SynBioLab/UniKP) |
| EITLEM-Kinetics | 2024 | [Paper](https://doi.org/10.1016/j.checat.2024.101094) · [Repository](https://github.com/XvesS/EITLEM-Kinetics) |
| MPEK | 2024 | [Paper](https://doi.org/10.1093/bib/bbae387) · [Repository](https://github.com/kotori-y/mpek); ratio derived from predicted kcat and Km and evaluated in case studies; not an independently trained ratio model |
| IECata | 2025 | [Paper](https://doi.org/10.1093/bib/bbaf283) · [Repository](https://github.com/zhaoyanpeng208/IECata) |
| CataPro | 2025 | [Paper](https://doi.org/10.1038/s41467-025-58038-4) · [Repository](https://github.com/zchwang/CataPro) |
| CPI-Pred | 2025 | [Preprint](https://doi.org/10.1101/2025.01.16.633372) · [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC11785036/) |
| EnzCast | 2026 | [Preprint](https://doi.org/10.64898/2026.04.28.721430) |
| ENZYME-UNIFIED | 2026 | [Manuscript](https://openreview.net/pdf?id=oTnFATrtCD); marked under review, acceptance not verified |
| DeltaKcat | 2026 | [Preprint](https://doi.org/10.65215/LTSpreprints.2026.05.19.000247) · [Original repository link](https://github.com/LiLabTsinghua/DeltaKcat) (unavailable when checked); relative changes between enzyme–substrate pairs |
| iESC | 2026 | https://doi.org/10.1016/j.biortech.2026.134067 |
| GraphKcat | 2026 | [Paper](https://doi.org/10.1021/acscatal.6c03874) · [Repository](https://github.com/ld139/GraphKcat); log-ratio derived as log(kcat) − log(Km) |
| UniKineG | 2026 | [Paper](https://doi.org/10.3390/ijms27041731) · [Data](https://zenodo.org/records/18125285) |
| EnzGFM (UniKP downstream) | 2026 | [Paper](https://doi.org/10.1038/s41467-026-75283-3) · [Repository](https://github.com/DeepBxM/EnzGFM); enzyme-specific backbone with downstream kinetic regressors |
| KinEAGER | 2026 | [Paper](https://doi.org/10.1021/acs.jcim.6c02075); official code attribution not verified; analytically derived from predicted kcat and Km |
| DLCatalysis | 2026 | [Paper (online accepted manuscript)](https://doi.org/10.1038/s41467-026-77406-2) · [Repository](https://github.com/wnkAI/DLcatalysis); direct kcat/Km prediction; source and data present, task checkpoint not found in checked tree |

## Ki

| Model / Method | Year | Links / notes |
| --- | ---: | --- |
| CatPred | 2025 | [Paper](https://doi.org/10.1038/s41467-025-57215-9) · [Repository](https://github.com/maranasgroup/CatPred) |
| OmniESI | 2025 | [Preprint](https://arxiv.org/abs/2506.17963) · [Repository](https://github.com/Hong-yu-Zhang/OmniESI); former repository name: MESI |
| CPI-Pred | 2025 | [Preprint](https://doi.org/10.1101/2025.01.16.633372) · [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC11785036/) |
| SAKPE | 2025 | [Preprint](https://doi.org/10.1101/2025.04.30.651216) · [Placeholder repository](https://github.com/HGzyme/SAKPE); title-only README, no code in checked tree |
| ERBA | 2026 | [CVPR 2026 paper](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Multimodal_Protein_Language_Models_for_Enzyme_Kinetic_Parameters_From_Substrate_CVPR_2026_paper.html) · [arXiv](https://arxiv.org/abs/2603.12845) |
| EnzCast | 2026 | [Preprint](https://doi.org/10.64898/2026.04.28.721430) |
| GAPEK / GAPEK+ | 2026 | [Paper](https://doi.org/10.1021/acs.jcim.6c02546) · [Repository](https://github.com/Zach-NTU/GAPEK); repository marked pre-release; code present, referenced inference checkpoint not found in checked tree |
| EnzGFM (CatPred downstream) | 2026 | [Paper](https://doi.org/10.1038/s41467-026-75283-3) · [Repository](https://github.com/DeepBxM/EnzGFM); enzyme-specific backbone evaluated with CatPred for Ki |

## Databases, benchmarks, and prediction services

| Resource | What it provides | Sources |
| --- | --- | --- |
| GotEnzymes2 | Database of precomputed kcat, Km, and kcat/Km predictions across species. Thermal property predictions are also available. | [Paper](https://doi.org/10.1093/nar/gkaf1053) · [Database](https://metabolicatlas.org/gotenzymes) · [Repository](https://github.com/LiLabTsinghua/GotEnzymes2) |
| SKiD | Pairs enzyme–substrate complex structures with experimental kcat or Km records for structure-based modeling. | [Paper](https://doi.org/10.1038/s41597-025-05829-5) · [Dataset](https://doi.org/10.5281/zenodo.15355030) · [Dataset preparation code](https://github.com/Sowmya-R-Krishnan/SKiD) |
| KcatTIE | External test set of 152 kcat measurements for 55 enzymes from studies published in 2023–2025. The accompanying benchmark also tests how models rank variants. | [Preprint](https://doi.org/10.21203/rs.3.rs-9154046/v1) · [Benchmark repository](https://github.com/zelixirSH/kcat_benchmark_2025) |
| EnzyArena | Groups variant measurements by experimental campaign so models can be evaluated on kcat, Km, or kcat/Km under matched assay conditions. | [Paper](https://doi.org/10.1021/acs.jcim.6c01200) · [Datasets](https://github.com/zishuozeng/EnzyArena) |
| OpenKinetics Predictor | Runs published predictors through a common interface. Users can select kcat, Km, or kcat/Km and compare methods available for that target. | [Web service](https://predictor.openkinetics.org/) · [Repository](https://github.com/openKinetics/webKinPred) · [Preprint](https://doi.org/10.64898/2026.09.25.751968) |
