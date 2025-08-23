# ARCADE-MICCAI2023

I had the opportunity to participate in the **[ARCADE-MICCAI2023](https://arcade.grand-challenge.org/)** (Automatic Region-based Coronary Artery Disease Diagnostics using X-ray Angiography Images), a competition focused on advancing diagnostic tools for coronary artery disease. The goal was to develop methods for segmenting multivessel coronary arteries and detecting stenotic lesions in angiograms, tasks that are both clinically critical and technically complex.

Working with angiography data is particularly challenging due to variability in imaging quality and interpretation. Our team tackled this by designing a five-stage pipeline: binary class pretraining, multivessel segmentation, fine-tuning with class frequency–weighted dataloaders, curriculum learning based on F1 scores, and adaptation to multi-view angiograms using a classifier-guided approach.

We ultimately built an ensemble of six baseline models, combining their outputs through weighted ensembling to boost performance. By refining misclassified cases, we achieved a mean F1 score of 37.69% for artery segmentation and 39.41% for stenosis localization, earning 5th place on both leaderboards.

I’m deeply grateful to my teammates for their dedication and expertise. This project not only strengthened my technical skills but also gave me invaluable insight into how machine learning can directly impact clinical decision-making.

**[● Arxiv Paper](https://arxiv.org/abs/2310.17954)**

```bibtex
@misc{bilal2023multivessel,
      title={Multivessel Coronary Artery Segmentation and Stenosis Localisation using Ensemble Learning}, 
      author={Muhammad Bilal and Dinis Martinho and Reiner Sim and Adnan Qayyum and Hunaid Vohra and Massimo Caputo and Taofeek Akinosho and Sofiat Abioye and Zaheer Khan and Waleed Niaz and Junaid Qadir},
      year={2023},
      eprint={2310.17954},
      archivePrefix={arXiv},
      primaryClass={eess.IV}
}
