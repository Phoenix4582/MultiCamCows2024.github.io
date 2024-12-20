# MultiCamCows2024 - A multi-view image dataset for indoor Holstein-Friesian cow (re-)identification

## Authors
Phoenix Yu (Junjie Yu); Tilo Burghardt; Andrew Dowsey, Neill Campbell

## Overview
MultiCamCows2024 is a multi-view image set for individual identification of Holstein-Friesian cows first available. Captured by three different cameras over seven days on a working farm, the dataset comprises 101,329 images from 90 unique cows. Pre-trained a species identifier based on RetinaNet, raw tracklets of cow individuals were extracted from monitored videos. After noises filtering and tracklet merging across each camera, both supervised and self-supervised learning frameworks were employed for individual cow identification. Utilising the dataset, it can be concluded that perfect tracklets with extra supervision signals can be used to build an automatic cow identifier with no human input. Furthermore, the self-supervised framework not only improves identification accuracy but also lays the groundwork for addressing open-set challenges in future research endeavours and opportunities for accurate individual cow identification, with implications for livestock management, behaviour analysis, and agricultural monitoring. The GitHub repository for our individual cow identifiers is also available at [https://github.com/Phoenix4582/CowIDentifier](https://github.com/Phoenix4582/CowIDentifier). 

Dataset is available for download from [here](https://data.bris.ac.uk/data/dataset/2inu67jru7a6821kkgehxg3cv2).

## Citations
```
@misc{yu2024multicamcows2024multiviewimage,
      title={MultiCamCows2024 -- A Multi-view Image Dataset for AI-driven Holstein-Friesian Cattle Re-Identification on a Working Farm}, 
      author={Phoenix Yu and Tilo Burghardt and Andrew W Dowsey and Neill W Campbell},
      year={2024},
      eprint={2410.12695},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2410.12695}, 
}
```

## Acknowledgements
We thank Dr Neill Campbell and Dr Tilo Burghardt for their tireless efforts of educating the art of starting and maintaining a PhD research project from scratch. We thank Andrew Drowsey for his continuous support for hardware management and occasional checkups for the progress of PhD students. We thank the members of John Oldacre Center AI meeting for their lasting passion of innovations and interdiscipinary communication. We thank the University of Bristol for the many aspects of opportunity, the School of Computer Science for professional knowledge and the Veterinary School for providing a healthy testing farm. We thank all the loved ones who provided us with support from many aspects within our group. 
