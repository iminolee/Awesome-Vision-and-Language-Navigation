# Awesome-Vision-and-Language-Navigation

`Updated on 2025.03.10`

This repo tracks the research papers and codes related to **Vision-and-Language Navigation (VLN)**. The repository will be continuously updated to keep up with the advancements in VLN. Feel free to follow and star!

## Table of Contents
- [News](#news)
- [Surveys](#surveys)
- [Datasets and Simulators](#datasets-and-simulators)
- [Papers and Codes](#papers-and-codes)
   - [2025](#2025)
   - [2024](#2024)
   - [2023](#2023)
   - [2022](#2022)
   - [2021](#2021)
- [Foundation Models](#visual-language-foundation-models)
- [Tools and Libraries](#tools-and-libraries)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## News
* **Workshop on Foundation Models and Neuro-Symbolic AI for Robotics** is held at the 2025 IEEE International Conference on Robotics and Automation (ICRA 2025), in Atlanta, USA on May.19, 2025. <br>
[[Official Website]](https://sairlab.org/icra25/)

* **AI Meets Autonomy: Vision, Language, and Autonomous Systems Workshop** is held at the 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2024), in Abu Dhabi, UAE on Oct.14, 2024. <br>
[[Official Website]](https://www.ai-meets-autonomy.com/iros-workshop)

* **Vision-Language Models for Navigation and Manipulation (VLMNM)** is held at 2024 IEEE International Conference on Robotics and Automation (ICRA 2024), in Yokohaba, Japan on May.17, 2024. <br>
[[Official Website]](https://vlmnm-workshop.github.io/)

## Survey
- **Vision-and-Language Navigation Today and Tomorrow: A Survey in the Era of Foundation Models** <br>
   *Yue Zhang, Ziqiao Ma, Jialu Li, Yanyuan Qiao, Zun Wang, Joyce Chai, Qi Wu, Mohit Bansal, Parisa Kordjamshidi* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2407.07035)

- **Large Language Models for Robotics: Opportunities, Challenges, and Perspectives** <br>
   *Jiaqi Wang, Zihao Wu, Yiwei Li, Hanqi Jiang, Peng Shu, Enze Shi, Huawen Hu, Chong Ma, Yiheng Liu, Xuhui Wang, Yincheng Yao, Xuan Liu, Huaqin Zhao, Zhengliang Liu, Haixing Dai, Lin Zhao, Bao Ge, Xiang Li, Tianming Liu, Shu Zhang* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2401.04334)

- **Large Language Models for Robotics: Opportunities, Challenges, and Perspectives** <br>
   *Jiaqi Wang, Zihao Wu, Yiwei Li, Hanqi Jiang, Peng Shu, Enze Shi, Huawen Hu, Chong Ma, Yiheng Liu, Xuhui Wang, Yincheng Yao, Xuan Liu, Huaqin Zhao, Zhengliang Liu, Haixing Dai, Lin Zhao, Bao Ge, Xiang Li, Tianming Liu, Shu Zhang* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2401.04334)

## Datasets and Simulators
In VLN tasks, the utilized datasets provide visual assets and scenes, and simulators render these visual assets and provide an environment for the VLN agent. This section will introduce some VLN datasets and simulators commonly used in VLN research.

### Datasets
- **[Matterport3D dataset] Learning from RGB-D Data in Indoor Environments** <br>
   *Angel Chang, Angela Dai, Thomas Funkhouser, Maciej Halber, Matthias Nießner, Manolis Savva, Shuran Song, Andy Zeng, Yinda Zhang* <br>
   3DV, 2017. [[Paper]](https://arxiv.org/pdf/1709.06158) [[GitHub]](https://github.com/niessner/Matterport)[[Project Page]](https://bringmeaspoon.org/)

- **[R2R dataset] Vision-and-Language Navigation: Interpreting visually-grounded navigation instructions in real environments** <br>
   *Peter Anderson, Qi Wu, Damien Teney, Jake Bruce, Mark Johnson, Niko Sunderhauf, Ian Reid, Stephen Gould, Anton van den Hengel* <br>
   CVPR, 2018. [[Paper]](https://arxiv.org/pdf/1711.07280) [[GitHub]](https://github.com/peteanderson80/Matterport3DSimulator/tree/master/tasks/R2R)

- **[RxR dataset] Multilingual Vision-and-Language Navigation with Dense Spatiotemporal Grounding** <br>
   *Alexander Ku, Peter Anderson, Roma Patel, Eugene le, Jason Baldridge* <br>
   EMNLP, 2020. [[Paper]](https://arxiv.org/pdf/2010.07954) [[GitHub]](https://github.com/google-research-datasets/RxR)

- **[HM3D-OVON] A Dataset and Benchmark for Open-Vocabulary Object Goal Navigation** <br>
   *Naoki Yokoyama, Ram Ramrakhya, Abhishek Das, Dhruv Batra, Sehoon Ha* <br>
   IROS, 2024. [[Paper]](https://arxiv.org/pdf/2409.14296) [[GitHub]](https://github.com/naokiyokoyama/ovon)

### Simulators
- **Habitat 3.0: A CO-HABITAT for Humans, Avatars and Robots** <br>
   *Xavi Puig, Eric Undersander, Andrew Szot, Mikael Dallaire Cote
, Tsung-Yen Yang, Ruslan Partsey, Ruta Desai, Alexander William Clegg, Michal Hlavac, So Yeon Min, Vladimír Vondruš, Theophile Gervet, Vincent-Pierre Berges, John M. Turner, Oleksandr Maksymets, Zsolt Kira, Mrinal Kalakrishnan, Jitendra Malik, Devendra Singh Chaplot, Unnat Jain, Dhruv Batra, Akshara Rai, Roozbeh Mottaghi* <br>
   arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2310.13724) [[GitHub]](https://github.com/facebookresearch/habitat-sim/) [[Project Page]](https://aihabitat.org/habitat3/)

- **Vision-Language Navigation Benchmark in Isaac Lab** <br>
   *An-Chieh Cheng, Yandong Ji, Zhaojing Yang, Zaitian Gongye, Xueyan Zou, Jan Kautz, Erdem Bıyık, Hongxu Yin, Sifei Liu, Xiaolong Wang*
   [[GitHub]](https://github.com/yang-zj1026/VLN-CE-Isaac) [[Project Page]](https://navila-bot.github.io/)

- **UnralZoo: Enriching Photo-realistic Virtual Worlds for Embodied AI** <br>
   *Fangwei Zhong, Kui Wu, Churan Wang, Hao Chen, Hai Ci, Zhoujun Li, Yizhou Wang* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2412.20977) [[GitHub]](https://github.com/UnrealZoo/unrealzoo-gym) [[Project Page]](http://unrealzoo.site/)

- **Genesis: A Generative and Universal Physics Engine for Robotics and Beyond** <br>
   *Genesis Authors* <br>
   2024. [[Paper]]() [[GitHub]](https://github.com/Genesis-Embodied-AI/Genesis) [[Project Page]](https://genesis-embodied-ai.github.io/)

- **Cosmos World Foundation Model Platform for Physical AI** <br>
   *NVIDIA* <br>
   arXiv, 2025. [[Paper]](https://arxiv.org/pdf/2501.03575) [[GitHub]](https://github.com/NVIDIA/Cosmos) [[HuggingFace]](https://huggingface.co/collections/nvidia/cosmos-6751e884dc10e013a0a0d8e6)

## Papers and Codes
### 2025
- **3D-Mem: 3D Scene Memory for Embodied Exploration and Reasoning** <br>
   *Yuncong Yang, Han Yang, Jiachen Zhou, Peihao Chen, Hongxin Zhang, Yilun Du, Chuang Gan* <br>
   CVPR, 2025. [[Paper]](https://arxiv.org/pdf/2411.17735) [[GitHub]](https://github.com/UMass-Embodied-AGI/3D-Mem)

- **EfficientEQA: An Efficient Approach for Open Vocabulary Embodied Question Answering** <br>
   *Kai Cheng, Zhengyuan Li, Xingpeng Sun, Byung-Cheol Min, Amrit Singh Bedi, Aniket Bera* <br>
   IROS, 2025. [[Paper]](https://arxiv.org/pdf/2410.20263)

### 2024
- **E2Map: Experience-and-Emotion Map for Self-Reflective Robot Navigation with Language Models** <br>
   *Chan Kim, Keonwoo Kim, Mintaek Oh, Hanbi Baek, Jiyang Lee, Donghwi Jung, Soojin Woo, Younkyung Woo, John Tucker, Roya Firoozi, Seung-Woo Seo, Mac Schwager, Seong-Woo Kim* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2409.10027) [[GitHub]](https://github.com/knwoo/e2map)

- **Autonomous Exploration and Semantic Updating of Large-Scale Indoor Environments with Mobile Robots** <br>
   *Sai Haneesh Allu, Itay Kadosh, Tyler Summers, Yu Xiang* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2409.15493) [[GitHub]](https://github.com/IRVLUTD/AutoX-SemMap)

- **Bridging Zero-shot Object Navigation and Foundation Models through Pixel-Guided Navigation Skill** <br>
   *Cai, Wenzhe; Huang, Siyuan; Cheng, Guangran; Long, Yuxing; Gao, Peng; Sun, Changyin; Dong, Hao* <br>
   ICRA, 2024. [[Paper]](https://arxiv.org/pdf/2309.10309) [[GitHub]](https://github.com/wzcai99/Pixel-Navigator)

- **InstructNav: Zero-shot System for Generic Instruction Navigation in Unexplored Environment** <br>
   *Yuxing Long, Wenzhe Cai, Hongcheng Wang, Guanqi Zhan, Hao Dong* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2406.04882) [[GitHub]](https://github.com/LYX0501/InstructNav)

- **NaVILA: Legged Robot Vision-Language-Action Model for Navigation** <br>
   *An-Chieh Cheng, Yandong Ji, Zhaojing Yang, Xueyan Zou, Jan Kautz, Erdem Bıyık, Hongxu Yin, Sifei Liu, Xiaolong Wang* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2412.04453) [[GitHub]](https://navila-bot.github.io/)

- **ReMEmbR: Building and Reasoning Over Long-Horizon Spatio-Temporal Memory for Robot Navigation** <br>
   *Abrar Anwar, John Welsh, Joydeep Biswas, Soha Pouya, Yan Chang* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2409.13682) [[GitHub]](https://github.com/NVIDIA-AI-IOT/remembr)

- **Aim My Robot: Precision Local Navigation to Any Object** <br>
   *Xiangyun Meng, Xuning Yang, Sanghun Jung, Fabio Ramos, Srid Sadhan Jujjavarapu, Sanjoy Paul, Dieter Fox*
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2411.14770)

- **Tag Map: A Text-Based Map for Spatial Reasoning and Navigation with Large Language Models** <br>
   *Mike Zhang, Kaixian Qu, Vaishakh Patil, Cesar Cadena, Marco Hutter* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2409.15451) [[Project Page]](https://tag-mapping.github.io/)

- **Adaptive Zone-aware Hierarchical Planner for Vision-Language Navigation** <br>
   *Chen Gao, Xingyu Peng, Mi Yan, He Wang, Lirong Yang, Haibing Ren, Hongsheng Li, Si Liu* <br>
   CVPR, 2023. [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Adaptive_Zone-Aware_Hierarchical_Planner_for_Vision-Language_Navigation_CVPR_2023_paper.pdf) [[GitHub]](https://github.com/chengaopro/AZHP)

- **MapGPT: Map-Guided Prompting with Adaptive Path Planning for Vision-and-Language Navigation** <br>
   *Jiaqi Chen, Bingqian Lin, Ran Xu, Zhenhua Chai, Xiaodan Liang, Kwan-Yee K. Wong* <br>
   ACL, 2024. [[Paper]](https://arxiv.org/pdf/2401.07314) [[GitHub]](https://github.com/chen-judge/MapGPT/)

- **CANVAS: Commonsense-Aware Navigation System for Intuitive Human-Robot Interaction** <br>
   *Suhwan Choi, Yongjun Cho, Minchan Kim, Jaeyoon Jung, Myunchul Joe, Yubeen Park, Minseo Kim, Sungwoong Kim, Sungjae Lee, Hwiseong Park, Jiwan Chung, Youngjae Yu* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2410.01273) [[GitHub]](https://worv-ai.github.io/canvas/)

- **VLFM: Vision-Language Frontier Maps for Zero-Shot Semantic Navigation** <br>
   *Naoki Yokoyama, Sehoon Ha, Dhruv Batra, Jiuguang Wang, Bernadette Bucher* <br>
   ICRA, 2024. [[Paper]](https://arxiv.org/pdf/2312.03275) [[GitHub]](https://github.com/bdaiinstitute/vlfm)

- **Mind the Error! Detection and Localization of Instruction Errors in Vision-and-Language Navigation** <br>
   *Francesco Taioli, Stefano Rosa, Alberto Castellini, Lorenzo Natale, Alessio Del Bue, Alessandro Farinelli, Marco Cristani, Yiming Wang* <br>
   IROS, 2024. [[Paper]](https://arxiv.org/pdf/2403.10700) [[GitHub]](https://github.com/intelligolabs/R2RIE-CE)

- **Planning from Imagination: Episodic Simulation and Episodic Memory for Vision-and-Language Navigation** <br>
   *Yiyuan Pan, Yunzhe Xu, Zhe Liu, Hesheng Wang* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2412.01857)

- **MC-GPT: Empowering Vision-and-Language Navigation with Memory Map and Reasoning Chains** <br>
   *Zhaohuan Zhan, Lisha Yu, Sijie Yu, Guang Tan* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2405.10620)

- **Continual Vision-and-Language Navigation** <br>
   *Seongjun Jeong, Gi-Cheon Kang, Seongho Choi, Joochan Kim, Byoung-Tak Zhang* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2403.15049)

- **Open-Nav: Exploring Zero-Shot Vision-and-Language Navigation in Continuous Environment with Open-Source LLMs** <br>
   *Yanyuan Qiao, Wenqi Lyu, Hui Wang, Zixu Wang, Zerui Li, Yuan Zhang, Mingkui Tan, Qi Wu* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2409.18794)

- **Find Everything: A General Vision Language Model Approach to Multi-Object Search** <br>
   *Daniel Choi, Angus Fung, Haitong Wang, Aaron Hao Tan* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2410.00388) [[GitHub]](https://find-all-my-things.github.io/)

- **NavGPT: Explicit Reasoning in Vision-and-Language Navigation with Large Language Models** <br>
   *Gengze Zhou, Yicong Hong, Qi Wu* <br>
   AAAI, 2024. [[Paper]](https://arxiv.org/pdf/2305.16986) [[GitHub]](https://github.com/GengzeZhou/NavGPT)

- **NavGPT-2: Unleashing Navigational Reasoning Capability for Large Vision-Language Models** <br>
   *Gengze Zhou, Yicong Hong, Zun Wang, Xin Eric Wang, Qi Wu* <br>
   arXiv, 2024. [[Paper]](https://arxiv.org/pdf/2407.12366) [[GitHub]](https://github.com/GengzeZhou/NavGPT-2)

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
- **GrASPE: Graph based Multimodal Fusion for Robot Navigation in Outdoor Environments** <br>
   *Kasun Weerakoon, Adarsh Jagan Sathyamoorthy, Jing Liang, Tianrui Guan, Utsav Patel, Dinesh Manocha* <br>
   RA-L, 2023. [[Paper]](https://arxiv.org/pdf/2209.05722)

- **LANA: A Language-Capable Navigator for Instruction Following and Generation** <br>
   *Xiaohan Wang, Wenguan Wang, Jiayi Shao, Yi Yang* <br>
   CVPR, 2023. [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_LANA_A_Language-Capable_Navigator_for_Instruction_Following_and_Generation_CVPR_2023_paper.pdf) [[GitHub]](https://github.com/wxh1996/LANA-VLN)

- **Dreamwalker: Mental planning for continuous vision-language navigation** <br>
   *Hanqing Wang, Wei Liang, Luc Van Gool, Wenguan Wang* <br>
   CVPR, 2023. [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_DREAMWALKER_Mental_Planning_for_Continuous_Vision-Language_Navigation_ICCV_2023_paper.pdf) [[GitHub]](https://github.com/HanqingWangAI/Dreamwalker)

- **A2Nav: Action-Aware Zero-Shot Robot Navigation by Exploiting Vision-and-Language Ability of Foundation Models** <br>
   *Peihao Chen, Xinyu Sun, Hongyan Zhi, Runhao Zeng, Thomas H. Li, Gaowen Liu, Mingkui Tan, Chuang Gan* <br>
   arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2308.07997)

- **How To Not Train Your Dragon: Training-free Embodied Object Goal Navigation with Semantic Frontiers** <br>
   *Junting Chen, Guohao Li, Suryansh Kumar, Bernard Ghanem, Fisher Yu* <br>
   arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2305.16925)

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
   ICCV, 2021. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Think_Global_Act_Local_Dual-Scale_Graph_Transformer_for_Vision-and-Language_Navigation_CVPR_2022_paper.pdf) [[GitHub]](https://github.com/cshizhe/VLN-DUET) *Winner of the ICCV 2021 Workshop Human Interaction for Robotic Navigation REVERIE & SOON Challenges*

- **History Aware Multimodal Transformer for Vision-and-Language Navigation** <br>
   *Shizhe Chen, Pierre-Louis Guhur, Cordelia Schmid, Ivan Laptev* <br>
   NIPS, 2021. [[Paper]](https://arxiv.org/pdf/2110.13309) [[GitHub]](https://github.com/cshizhe/VLN-HAMT)

## Visual-Language Foundation Models
- **VILA: On Pre-training for Visual Language Models** <br>
   *Ji Lin, Hongxu Yin, Wei Ping, Pavlo Molchanov, Mohammad Shoeybi, Song Han* <br>
   CVPR, 2024. [[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Lin_VILA_On_Pre-training_for_Visual_Language_Models_CVPR_2024_paper.pdf) [[GitHub]](https://github.com/NVlabs/VILA) [[HuggingFace]](https://huggingface.co/collections/Efficient-Large-Model/vila-on-pre-training-for-visual-language-models-65d8022a3a52cd9bcd62698e)

- **BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding** <br>
   *Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova* <br>
   arXiv, 2018. [[Paper]](https://arxiv.org/pdf/1810.04805) [[GitHub]](https://github.com/google-research/bert) [[Official Website]](https://research.google/blog/open-sourcing-bert-state-of-the-art-pre-training-for-natural-language-processing/)

- **CLIP: Learning Transferable Visual Models From Natural Language Supervision** <br>
   *Alec Radford, Jong Wook Kim, Chris Hallacy, Aditya Ramesh, Gabriel Goh, Sandhini Agarwal, Girish Sastry, Amanda Askell, Pamela Mishkin, Jack Clark, Gretchen Krueger, Ilya Sutskever* <br>
   arXiv, 2021. [[Paper]](https://arxiv.org/pdf/2103.00020) [[GitHub]](https://github.com/openai/CLIP) [[Official Website]](https://openai.com/index/clip/)

- **InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning** <br>
   *Wenliang Dai, Junnan Li, Dongxu Li, Anthony Meng Huat Tiong, Junqi Zhao, Weisheng Wang, Boyang Li, Pascale Fung, Steven Hoi* <br>
   arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2305.06500) [[GitHub]](https://github.com/salesforce/LAVIS) [[Project Page]](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)

- **BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models** <br>
   *Junnan Li, Dongxu Li, Silvio Savarese, Steven Hoi* <br>
   arXiv, 2023. [[Paper]](https://arxiv.org/pdf/2301.12597) [[GitHub]](https://github.com/salesforce/LAVIS) [[Project Page]](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)

- **ViNT: A Foundation Model for Visual Navigation** <br>
   *Dhruv Shah, Ajay Sridhar, Nitish Dashora, Kyle Stachowicz, Kevin Black, Noriaki Hirose, Sergey Levine* <br>
   CoRL, 2023. [[Paper]](https://arxiv.org/pdf/2306.14846) [[GitHub]](https://github.com/robodhruv/visualnav-transformer) [[Project Page]](https://general-navigation-models.github.io/vint/index.html)

## Tools and Libraries
- **[Transformers] State-of-the-art Machine Learning for JAX, PyTorch and TensorFlow** <br>
   [[GitHub]](https://github.com/huggingface/transformers) [[Official Website]](https://huggingface.co/docs/transformers/index)

- **[LangChain] A framework for developing applications powered by large language models (LLMs)** <br>
   [[GitHub]](https://github.com/langchain-ai/langchain) [[Official Website]](https://python.langchain.com/v0.1/docs/get_started/introduction)

## Acknowledgements
I would like to thank all the researchers and developers who have contributed to the field of Vision-and-Language Navigation.

## Contact
If you have any suggestions for this repository, please create an issue or email **mino@inha.edu**.
