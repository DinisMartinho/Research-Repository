# ARCADE-MICCAI2023

I had the privilege of participating in the ARCADE-MICCAI2023 (Automatic Region-based Coronary Artery Disease Diagnostics using X-ray Angiography Images) challenge, an event of paramount importance in the realm of coronary artery disease diagnosis. This challenge aims to revolutionize the field by benchmarking innovative solutions for the accurate segmentation of multivessel coronary arteries and the localization of potential stenotic lesions in X-ray coronary angiograms.

The journey was far from easy, as the task presented numerous complexities. Analyzing coronary angiograms is not only vital but also inherently challenging due to the variability often encountered in medical imaging procedures. Our team dedicated itself to addressing these challenges, which are crucial for improving the accuracy of coronary artery disease diagnosis, guiding medical interventions, and enhancing the precision of stent injections in clinical settings.

We adopted a five-stage approach, which included binary class pretraining, multivessel segmentation, fine-tuning with class frequency weighted dataloaders, employing an F1-based curriculum learning strategy, and finally, adapting to multi-target angiogram views using a classifier-based approach. This comprehensive approach was our answer to the intricate nature of the task, allowing us to overcome interobserver variability and deliver results with profound implications for healthcare.

Our final solution was an ensemble model that combined the outputs of six baseline models using a weighted ensembling approach, effectively doubling the predictive accuracy of our proposed solution. To further refine our predictions, we concentrated on correcting misclassified anomalies, ultimately achieving a mean F1 score of 37.69% for coronary artery segmentation and 39.41% for stenosis localization. These remarkable achievements secured our team's fifth position on both leaderboards.

I want to express my gratitude to the dedicated and talented team I had the privilege to work with. Their collective effort and expertise were instrumental in our success, and I am immensely thankful for the invaluable knowledge and experience I gained from this endeavor.

**● [Arxiv Paper](https://arxiv.org/abs/2310.17954)**

```bibtex
@misc{bilal2023multivessel,
      title={Multivessel Coronary Artery Segmentation and Stenosis Localisation using Ensemble Learning}, 
      author={Muhammad Bilal and Dinis Martinho and Reiner Sim and Adnan Qayyum and Hunaid Vohra and Massimo Caputo and Taofeek Akinosho and Sofiat Abioye and Zaheer Khan and Waleed Niaz and Junaid Qadir},
      year={2023},
      eprint={2310.17954},
      archivePrefix={arXiv},
      primaryClass={eess.IV}
}
