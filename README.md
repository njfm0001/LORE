# LOcative Reference Extractor (LORE)
## Introduction
LORE, our rule-based model, and nLORE, its neural counterpart nLORE, are locative reference extractors designed to detect and extract any kind of locative references (e.g. geopolitical entities, landforms, points of interests, traffic ways, etc.) and their surrounding locative markers (e.g. directional, distance and temporal markers) from tweets or any other piece of microtext. LORE works with English, Spanish and French texts whereas nLORE only works with English texts.

This tool and associated research papers (see below) are the result of my my PhD thesis project, titled [*A linguistically-aware computational approach to microtext location detection*](https://digibug.ugr.es/handle/10481/64577), defended on October 21 2020 at the University of Granada (UGR) and obtaining *cum laude distinction*, under the PhD programme of Languages, Texts and Contexts (*Programa de Doctorado en Lenguajes, Textos y Contextos*).

Further information about the components, pipeline, application and evaluation of LORE and nLORE can be found in the references cited below. Should you wish to have access to the datasets used in our experiments (for research purposes only), please refer to the authors to request private access to them.

## How to use this tool

1. Download the precompiled application by requesting access to the file [here](https://drive.google.com/file/d/1yWs-eeP5_23eu1aNrZWnmIWKiVgMdupI/view?usp=sharing) and decompress the zip file into a folder. Execute the exe file.

2.  Using it is fairly intuitive: the main app window lets you upload a dataset of tweets or any other kind of dataset in txt format by clicking on the File icon and perform locative reference extraction. You can select either LORE or nLORE and the language of the dataset. Also, you can select the output format: token-based format (typically used in NER) or entity-based format. The extracted locative references will be saved onto the data/output folder in a txt file.

## How to cite this work
Whenever you use this tool, please include the following citation(s) and add a reference to their authors:

If you use LORE in your research or use our knowledge-based rules for location extraction, please cite the following:
- Fernández-Martínez, Nicolás José & Periñán-Pascual, Carlos. (2021). LORE: A model for the detection of fine-grained locative references in tweets. *Onomazein* 52, 195–225. https://doi.org/10.7764/onomazein.52.11
- Fernández-Martínez, Nicolás José & Periñán-Pascual, Carlos. (2020). Knowledge-based rules for the extraction of complex, fine-grained locative references from tweets. *Revista Electrónica de Lingüística Aplicada* 19(1), 136-163.


If you use nLORE in your research, please provide the following citation:
- Fernández-Martínez, Nicolás José & Periñán-Pascual, Carlos (2021). nLORE: A Linguistically Rich Deep-Learning System for Locative-Reference Extraction in Tweets. In Engie Bashir and Mitja Luštrek (eds.), *Intelligent Environments 2021: Workshop Proceedings of the 1st International Workshop on Artificial Intelligence and Machine Learning for Emerging Topics (ALLEGET ’21)*, 243-254. IOS Press. https://doi.org/10.3233/aise210103

If you use our datasets in your research, please cite the following:
- Fernández-Martínez, Nicolás José (2022). The FGLOCTweet Corpus: An English tweet-based corpus for fine-grained location-detection tasks. *Research in Corpus Linguistics* 10(1), 117–133. https://doi.org/10.32714/ricl.10.01.06

## Applications
Our work (tools and datasets) has already been used and cited by the following research work:

- Hu, X., Zhou, Z., Sun, Y., Kersten, J., Klan, F., Fan, H., & Wiegmann, M. (2022). GazPNE2: A general place name extractor for microblogs fusing gazetteers and pretrained transformer models. *IEEE Internet of Things Journal*, 1. https://doi.org/10.1109/JIOT.2022.3150967
- Hu, X., Zhou, Z., Li, H., Hu, Y., Gu, F., Kersten, J., Fan, H., & Klan, F. (2022). Location reference recognition from texts: A survey and comparison. ArXiv, abs/2207.01683.
- Suwaileh, R., Elsayed, T., & Imran, M. (2023). IDRISI-RE: A generalizable dataset with benchmarks for location mention recognition on disaster tweets. *Information Processing & Management*, 60(3), 103340. https://doi.org/10.1016/J.IPM.2023.103340
- Yu, L., & Li, D. (2022). Road-Related Information Mining from Social Media Data: A Joint Relation Extraction and Entity Recognition Approach. *Buildings*, 13(1), 104. https://doi.org/10.3390/buildings13010104
- Zhou, S., Thomas Ng, S., Huang, G., Dao, J., & Li, D. (2022). Extracting interrelated information from road-related social media data. *Advanced Engineering Informatics*, 54, 101780. https://doi.org/10.1016/J.AEI.2022.101780

## Funding
Results from this PhD thesis project are associated with the development of the social sensor module in the research project "Planificación y gestión de recursos hídricos a partir de análisis de datos de IoT (WATERoT)" (RTC 2017-6389-5), funded by the *Ministerio de Economía, Industria y Competitividad* (MINECO), *Agencia Estatal de Investigación* (AEI) and the *Fondo Europeo de Desarrollo Regional* (FEDER).
![logo](https://user-images.githubusercontent.com/45042730/158458975-d0554557-82c3-40c6-bb08-b68a38115268.png)
