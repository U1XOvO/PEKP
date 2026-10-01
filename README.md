# PEKP

Collection of models, methods, and resources for predicting enzyme kinetic parameters (PEKP).

Literature cutoff: **2026-09-30**. Selected source and repository checks: **2026-10-01**.

The four sections group methods by their reported targets. Methods can appear in more than one section; this is intentional. Derived ratios, relative changes, and range classification are marked explicitly. Years follow the linked journal publication where available, otherwise the manuscript/resource year. **Preprint** and **under review** do not imply peer-reviewed publication.

Links distinguish papers, preprints, repositories, data, and notebooks where checked in this update. A repository link does not imply a complete release or verified reproducibility; an omitted code link does not establish that no code exists. Older bare links are retained from the original collection. See the [static audit and availability notes](docs/audit-2026-09-30.md).

Ki denotes the inhibition constant; it is not Kd or IC50. Availability notes describe the inspected repository tree, not a model execution test.

## kcat

| Model / Method | Year | Links / notes |
| --- | ---: | --- |
| Heckmann et al. | 2018 | https://doi.org/10.1038/s41467-018-07652-6 |
| DLKcat | 2022 | https://github.com/SysBioChalmers/DLKcat |
| UniKP | 2023 | https://github.com/Luo-SynBioLab/UniKP |
| TurNuP | 2023 | https://github.com/AlexanderKroll/kcat_prediction |
| DeepEnzyme | 2024 | https://github.com/hongzhonglu/DeepEnzyme |
| DLTKcat | 2024 | https://github.com/SizheQiu/DLTKcat |
| EITLEM-Kinetics | 2024 | https://github.com/XvesS/EITLEM-Kinetics |
| MPEK | 2024 | [Paper](https://doi.org/10.1093/bib/bbae387) · [Repository](https://github.com/kotori-y/mpek) |
| ECEP | 2024 | https://github.com/misharisaud/ECEP |
| ENKIE | 2024 | https://gitlab.com/csb.ethz/enkie |
| PreTKcat | 2025 | [Paper](https://doi.org/10.1016/j.compbiolchem.2024.108327) · [Repository](https://github.com/MrVincentCai/PreTKcat) |
| NNKcat | 2025 | [Repository](https://github.com/Jiczh/NNKcat); no README; some referenced assets absent from checked tree |
| GELKcat | 2025 | https://doi.org/10.1016/j.ymeth.2025.02.010 |
| MMKcat | 2025 | [Paper](https://www.sciencedirect.com/science/article/pii/S0010482525006997) · [Repository](https://github.com/ProEcho1/MMKcat) |
| ProKcat | 2025 | [Preprint](https://arxiv.org/abs/2509.11782) · [Repository](https://github.com/bozhenhhu/ProKcat); withdrawn from IJCAI 2025 proceedings (see arXiv comments) |
| TCNeKP | 2025 | [Paper](https://doi.org/10.1021/acs.jcim.5c01830) · [Repository](https://github.com/YuanyuanLei-TCNeKP/TCNeKP) |
| CatPred | 2025 | [Paper](https://doi.org/10.1038/s41467-025-57215-9) · [Repository](https://github.com/maranasgroup/CatPred) |
| EnzyCLIP | 2025 | [Preprint](https://arxiv.org/abs/2512.00379) |
| OmniESI | 2025 | [Preprint](https://arxiv.org/abs/2506.17963) · [Repository](https://github.com/Hong-yu-Zhang/OmniESI); former repository name: MESI |
| DEKP | 2025 | https://github.com/wang-yi-zhen/DEKP |
| CataPro | 2025 | https://github.com/zchwang/CataPro |
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

## Km

| Model / Method | Year | Links / notes |
| --- | ---: | --- |
| Kroll-KM | 2021 | https://github.com/AlexanderKroll/KM_prediction |
| MLAGO | 2022 | https://doi.org/10.1186/s12859-022-05009-x |
| UniKP | 2023 | https://github.com/Luo-SynBioLab/UniKP |
| GraphKM | 2024 | https://github.com/realHXiao/GraphKM |
| EITLEM-Kinetics | 2024 | https://github.com/XvesS/EITLEM-Kinetics |
| MPEK | 2024 | [Paper](https://doi.org/10.1093/bib/bbae387) · [Repository](https://github.com/kotori-y/mpek) |
| ProSmith | 2024 | https://github.com/AlexanderKroll/ProSmith |
| ENKIE | 2024 | https://gitlab.com/csb.ethz/enkie |
| DLERKm | 2025 | https://github.com/kaiwang-group/DLERKm |
| TCNeKP | 2025 | [Paper](https://doi.org/10.1021/acs.jcim.5c01830) · [Repository](https://github.com/YuanyuanLei-TCNeKP/TCNeKP) |
| CatPred | 2025 | [Paper](https://doi.org/10.1038/s41467-025-57215-9) · [Repository](https://github.com/maranasgroup/CatPred) |
| EnzyCLIP | 2025 | [Preprint](https://arxiv.org/abs/2512.00379) |
| OmniESI | 2025 | [Preprint](https://arxiv.org/abs/2506.17963) · [Repository](https://github.com/Hong-yu-Zhang/OmniESI); former repository name: MESI |
| DEKP | 2025 | https://github.com/wang-yi-zhen/DEKP |
| CataPro | 2025 | https://github.com/zchwang/CataPro |
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

## kcat/Km

| Model / Method | Year | Links / notes |
| --- | ---: | --- |
| UniKP | 2023 | https://github.com/Luo-SynBioLab/UniKP |
| EITLEM-Kinetics | 2024 | https://github.com/XvesS/EITLEM-Kinetics |
| MPEK | 2024 | [Paper](https://doi.org/10.1093/bib/bbae387) · [Repository](https://github.com/kotori-y/mpek); ratio derived from predicted kcat and Km and evaluated in case studies; not an independently trained ratio model |
| IECata | 2025 | https://github.com/zhaoyanpeng208/IECata |
| CataPro | 2025 | https://github.com/zchwang/CataPro |
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
