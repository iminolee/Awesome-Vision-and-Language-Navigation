# Awesome-Vision-and-Language-Navigation

`Updated on 2024.07.11`

This repo tracks the research papers and codes related to **Vision-and-Language Navigation (VLN)**. The repository will be continuously updated to keep up with the advancements in VLN. Feel free to follow and star!

## Table of Contents
- [Introduction](#introduction)
- [Datasets and Simulators](#datasets-and-simulators)
- [Papers and Codes](#papers-and-codes)
   - [2024](#2024)
   - [2023](#2023)
   - [2022](#2022)
   - [2021](#2021)
- [Foundation Models](#foundation-models)
- [Tools and Libraries](#tools-and-libraries)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Introduction
This repository aims to provide a comprehensive and up-to-date list of resources for Vision-and-Language (VLN). VLN is an emerging field that integrates computer vision, natural language processing, and robotics to enable agents to navigate environments using linguistic instructions.

## Datasets and Simulators
In VLN tasks, the utilized datasets provide visual assets and scenes, and simulators render these visual assets and provide an environment for the VLN agent. This section will introduce some VLN datasets and simulators commonly used in VLN research.

### Datasets
- **[Matterport3D dataset] Learning from RGB-D Data in Indoor Environments** <br>
   *Angel Chang, Angela Dai, Thomas Funkhouser, Maciej Halber, Matthias Nießner, Manolis Savva, Shuran Song, Andy Zeng, Yinda Zhang* <br>
   3DV, 2017. [[Paper]](https://arxiv.org/pdf/1709.06158) [[GitHub]](https://github.com/niessner/Matterport)[[Project Page]](https://bringmeaspoon.org/)

- **[R2R dataset] Vision-and-Language Navigation: Interpreting visually-grounded
navigation instructions in real environments** <br>
   *Peter Anderson, Qi Wu, Damien Teney, Jake Bruce, Mark Johnson, Niko Sunderhauf, Ian Reid, Stephen Gould, Anton van den Hengel* <br>
   CVPR, 2018. [[Paper]](https://arxiv.org/pdf/1711.07280) [[GitHub]](https://github.com/peteanderson80/Matterport3DSimulator/tree/master/tasks/R2R)

- **[RxR dataset] Multilingual Vision-and-Language Navigation with Dense Spatiotemporal Grounding** <br>
   *Alexander Ku, Peter Anderson, Roma Patel, Eugene le, Jason Baldridge* <br>
   EMNLP, 2020. [[Paper]](https://arxiv.org/pdf/2010.07954) [[GitHub]](https://github.com/google-research-datasets/RxR)

### Simulators
- **[Habitat3.0 simulator] HABITAT 3.0: A CO-HABITAT FOR HUMANS, AVATARS AND ROBOTS** <br>
   *Xavi Puig, Eric Undersander, Andrew Szot, Mikael Dallaire Cote
, Tsung-Yen Yang, Ruslan Partsey, Ruta Desai, Alexander William Clegg, Michal Hlavac, So Yeon Min, Vladimír Vondruš, Theophile Gervet, Vincent-Pierre Berges, John M. Turner, Oleksandr Maksymets, Zsolt Kira, Mrinal Kalakrishnan, Jitendra Malik, Devendra Singh Chaplot, Unnat Jain, Dhruv Batra, Akshara Rai, Roozbeh Mottaghi* <br>
   arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2310.13724) [[GitHub]](https://github.com/facebookresearch/habitat-sim/) [[Project Page]](https://aihabitat.org/habitat3/)

## Papers and Codes
### 2024
- **NavGPT: Explicit Reasoning in Vision-and-Language Navigation with Large Language Models** <br>
   *Gengze Zhou, Yicong Hong, Qi Wu* <br>
   AAAI, 2024. [[Paper]](https://arxiv.org/pdf/2305.16986) [[GitHub]](https://github.com/GengzeZhou/NavGPT)

- **Lookahead Exploration with Neural Radiance Representation for Continuous Vision-Language Navigation** <br>
   *Zihan Wang, Xiangyang Li, Jiahao Yang, Yeqi Liu, Junjie Hu, Ming Jiang, Shuqiang Jiang* <br>
   CVPR, 2024. [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Wang_Lookahead_Exploration_with_Neural_Radiance_Representation_for_Continuous_Vision-Language_Navigation_CVPR_2024_paper.pdf) [[GitHub]](https://github.com/MrZihan/HNR-VLN)

- **Sim-to-Real Transfer via 3D Feature Fields for Vision-and-Language Navigation** <br>
   *Zihan Wang, Xiangyang Li, Jiahao Yang, Yeqi Liu, Shuqiang Jiang* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2406.09798) [[GitHub]](https://github.com/MrZihan/Sim2Real-VLN-3DFF)

- **LangNav: Language as a Perceptual Representation for Navigation** <br>
   *Bowen Pan, Rameswar Pandam, SouYoung Jin, Rogerio Feris, Aude Oliva, Phillip Isola, Yoon Kim* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2310.07889) [[GitHub]](https://github.com/pbw-Berwin/LangNav)

- **Building Cooperative Embodied Agents Modularly with Large Language Models** <br>
   *Bowen Pan, Rameswar Pandam, SouYoung Jin, Rogerio Feris, Aude Oliva, Phillip Isola, Yoon Kim* <br>
   ICRL, 2024. [[Paper]](https://openreview.net/pdf?id=EnXJfQqy0K) [[GitHub]](https://github.com/UMass-Foundation-Model/Co-LLM-Agents)

### 2023
- **LANA: A Language-Capable Navigator for Instruction Following and Generation** <br>
   *Xiaohan Wang, Wenguan Wang, Jiayi Shao, Yi Yang* <br>
   CVPR, 2023. [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_LANA_A_Language-Capable_Navigator_for_Instruction_Following_and_Generation_CVPR_2023_paper.pdf) [[GitHub]](https://github.com/wxh1996/LANA-VLN)

- **Dreamwalker: Mental planning for continuous vision-language navigation** <br>
   *Hanqing Wang, Wei Liang, Luc Van Gool, Wenguan Wang* <br>
   CVPR, 2023. [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_DREAMWALKER_Mental_Planning_for_Continuous_Vision-Language_Navigation_ICCV_2023_paper.pdf) [[GitHub]](https://github.com/HanqingWangAI/Dreamwalker)

- **A2Nav: Action-Aware Zero-Shot Robot Navigation by Exploiting
Vision-and-Language Ability of Foundation Models** <br>
   *Peihao Chen, Xinyu Sun, Hongyan Zhi, Runhao Zeng, Thomas H. Li, Gaowen Liu, Mingkui Tan, Chuang Gan* <br>
   arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2308.07997)

### 2022
- **Sim-2-Sim for Vision-and-Language Navigation in Continuous Environments** <br>
   *Jacob Krantz, Stefan Lee* <br>
   ECCV, 2022. [[Paper]](https://arxiv.org/pdf/2204.09667) [[GitHub]](https://github.com/jacobkrantz/Sim2Sim-VLNCE)

- **Bridging the Gap Between Learning in Discrete and Continuous Environments for Vision-and-Language Navigation** <br>
   *Yicong Hong, Zun Wang, Qi Wu, Stephen Gould* <br>
   CVPR, 2022. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Hong_Bridging_the_Gap_Between_Learning_in_Discrete_and_Continuous_Environments_CVPR_2022_paper.pdf) [[GitHub]](https://github.com/YicongHong/Discrete-Continuous-VLN)

- **ETPNav: Evolving Topological Planning for Vision-Language Navigation in Continuous Environments** <br>
   *Dong An, Hanqing Wang, Wenguan Wang, Zun Wang, Yan Huang, Keji He, Liang Wang* <br>
   CVPR, 2022. [[Paper]](https://arxiv.org/pdf/2304.03047) [[GitHub]](https://github.com/MarSaKi/ETPNav) **Winner of the RxR-Habitat Challenge in CVPR 2022**

- **Cross-modal map learning for vision and language navigation** <br>
   *Georgios Georgakis, Karl Schmeckpeper, Karan Wanchoo, Soham Dan,
Eleni Miltsakaki, Dan Roth, Kostas Daniilidis* <br>
   CVPR, 2022. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Georgakis_Cross-Modal_Map_Learning_for_Vision_and_Language_Navigation_CVPR_2022_paper.pdf) [[GitHub]](https://github.com/ggeorgak11/CM2)

### 2021
- **SOON: Scenario Oriented Object Navigation with Graph-based Exploration** <br>
   *Fengda Zhu, Xiwen Liang, Yi Zhu, Qizhi Yu, Xiaojun Chang1, Xiaodan Liang* <br>
   CVPR, 2021. [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhu_SOON_Scenario_Oriented_Object_Navigation_With_Graph-Based_Exploration_CVPR_2021_paper.pdf) [[GitHub]](https://github.com/ZhuFengdaaa/SOON) [[Project Page]](https://scenario-oriented-object-navigation.github.io/)

- **Waypoint Models for Instruction-guided Navigation in Continuous Environments** <br>
   *Fengda Zhu, Xiwen Liang, Yi Zhu, Qizhi Yu, Xiaojun Chang1, Xiaodan Liang* <br>
   ICCV, 2021. [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Krantz_Waypoint_Models_for_Instruction-Guided_Navigation_in_Continuous_Environments_ICCV_2021_paper.pdf) [[GitHub]](https://github.com/jacobkrantz/VLN-CE) [[Project Page]](https://jacobkrantz.github.io/waypoint-vlnce/)

- **Think global, act local: Dual-scale graph transformer for vision-and-language navigation** <br>
   *Shizhe Chen, Pierre-Louis Guhur, Makarand Tapaswi, Cordelia Schmid, Ivan Laptev* <br>
   ICCV, 2021. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Think_Global_Act_Local_Dual-Scale_Graph_Transformer_for_Vision-and-Language_Navigation_CVPR_2022_paper.pdf) [[GitHub]](https://github.com/cshizhe/VLN-DUET) **Winner of the ICCV 2021 Workshop Human Interaction for Robotic Navigation REVERIE & SOON Challenges**

## Foundation Models
- **ViNT: A Foundation Model for Visual Navigation** <br>
   *Dhruv Shah, Ajay Sridhar, Nitish Dashora, Kyle Stachowicz, Kevin Black, Noriaki Hirose, Sergey Levine* <br>
   CoRL, 2023. [[Paper]](https://arxiv.org/pdf/2306.14846) [[GitHub]](https://github.com/robodhruv/visualnav-transformer) [[Project Page]](https://general-navigation-models.github.io/vint/index.html)

## Tools and Libraries
A list of tools and libraries that can aid in VLN research and development.

- **[LangChain] A framework for developing applications powered by large language models (LLMs)** <br>
[[GitHub]](https://github.com/langchain-ai/langchain)[[Official Website]](https://python.langchain.com/v0.1/docs/get_started/introduction)

## Acknowledgements
I would like to thank all the researchers and developers who have contributed to the field of Vision-and-Language Navigation.

## Contact
If you have any suggestions for this repository, please create an issue or email **mino@inha.edu**.
