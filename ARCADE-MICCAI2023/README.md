# ARCADE-MICCAI2023

I took part in the **[ARCADE-MICCAI2023](https://arcade.grand-challenge.org/)** challenge (Automatic Region-based Coronary Artery Disease Diagnostics using X-ray Angiography Images). The task was to build methods for segmenting coronary arteries and detecting stenosis in angiograms-problems that are both important in the clinic and technically difficult.

Angiography data is tricky to work with because of differences in image quality and interpretation. Our team approached this with a five-stage pipeline: binary class pretraining, multivessel segmentation, class-frequency weighted training, curriculum learning based on F1 scores, and a classifier-guided step for handling multiple views.

In the end, we combined six baseline models in an ensemble. Weighted averaging and case refinements gave us a mean F1 score of 37.69% for artery segmentation and 39.41% for stenosis localization. This placed us 5th on both leaderboards.

Big thanks to my teammates for their hard work-this project sharpened my technical skills and gave me a clearer sense of how machine learning can support medical decision-making.

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
```
