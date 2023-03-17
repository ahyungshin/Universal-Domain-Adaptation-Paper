# Universal Domain Adaptation

Domain adaptation aims to minimize the domain gap and successfully transfer the model trained on the labeled source domain to the unlabeled target domain. They suppose that label sets are identical across domains (***closed set domain adaptation***). Recent works try to relax the assumption by proposing ***open-set, partial, open-partial domain adaptation***. However, in the general scenario, we cannot select the proper domain adaptation method because no prior knowledge about the target domain label set is given. 

***Universal domain adaptation*** is a generalized setting. Given a labeled source domain, for any related target domain, regardless of how its label set differs from that of the source domain, we need to classify its samples correctly if it belongs to any class in the source label set, or mark it as “unknown” otherwise.

## 2023
- Upcycling Models under Domain and Category Shift (CVPR 2023) [[paper]](https://arxiv.org/pdf/2303.07110.pdf) [[code]](https://github.com/ispc-lab/GLC)

## 2022
- Subsidiary Prototype Alignment for Universal Domain Adaptation (NeurIPS 2022) [[paper]](https://arxiv.org/abs/2210.15909)
- Unified Optimal Transport Framework for Universal Domain Adaptation (NeurIPS 2022) [[paper]](https://arxiv.org/abs/2210.17067) [[code]](https://github.com/changwxx/uniot-for-unida)

## 2021
- Divergence Optimization for Noisy Universal Domain Adaptation (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yu_Divergence_Optimization_for_Noisy_Universal_Domain_Adaptation_CVPR_2021_paper.pdf) [[code]](https://github.com/YU1ut/Divergence-Optimization)
- Active Universal Domain Adaptation (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ma_Active_Universal_Domain_Adaptation_ICCV_2021_paper.pdf)
- OVANet: One-vs-All Network for Universal Domain Adaptation (ICCV 2021) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Saito_OVANet_One-vs-All_Network_for_Universal_Domain_Adaptation_ICCV_2021_paper.pdf) [[code]](https://github.com/VisionLearningGroup/OVANet)
- Domain Consensus Clustering for Universal Domain Adaptation (CVPR 2021) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Domain_Consensus_Clustering_for_Universal_Domain_Adaptation_CVPR_2021_paper.pdf) [[code]](https://github.com/Solacex/Domain-Consensus-Clustering)

## 2020
- Universal Source-Free Domain Adaptation (CVPR 2020) [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kundu_Universal_Source-Free_Domain_Adaptation_CVPR_2020_paper.pdf) [[code]](https://sites.google.com/view/usfda-cvpr2020?pli=1)
- Learning to Detect Open Classes for Universal Domain Adaptation (ECCV 2020) [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600562.pdf) [[code]](https://github.com/thuml/Calibrated-Multiple-Uncertainties)
- Universal Domain Adaptation through Self Supervision (NeurIPS 2020) [[paper]](https://proceedings.neurips.cc/paper/2020/file/bb7946e7d85c81a9e69fee1cea4a087c-Paper.pdf) [[code]](https://github.com/VisionLearningGroup/DANCE)

## 2019
- Universal domain adaptation (CVPR 2019) [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/You_Universal_Domain_Adaptation_CVPR_2019_paper.pdf) [[code]](https://github.com/thuml/Universal-Domain-Adaptation)
