---
permalink: /
title: "个人简介"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


- 本科毕业于浙江大学竺可桢学院15级混合班（计算机科学与技术专业），目前在浙江大学计算机科学与技术学院攻读硕士研究生二年级，导师：赵洲副教授；与微软亚洲研究院的谭旭、秦涛和刘铁岩老师等人有密切合作。
- 曾获2020年度[百度奖学金](http://scholarship.baidu.com/)（全球华人研究生10名）、2020年度字节奖学计划（全国10名）。
- 获2021年度人工智能全球高潜力华人学生——[AI华人新星百强榜单](https://mp.weixin.qq.com/s?__biz=MzA4NzQ5MTA2NA==&mid=2653639431&idx=1&sn=25b6368c1954419b9090840347d9a27d&chksm=8be75b90bc90d286a5af3ef8e610e822d705dc3cf4382b45e3f14489f3e7ec4fd8c95ed0eceb&mpshare=1&scene=2&srcid=0511LMlj9Qv9DeIZAjMjYAU9&sharer_sharetime=1620731348139&sharer_shareid=631c113940cb81f34895aa25ab14422a#rd)，同时入选\textbf{AI华人新星优秀学者}（全球华人研究生10名）。
- 兴趣方向是语音合成、机器翻译和自动作曲。
- 在NeurIPS、ICML、ICLR、KDD等国际人工智能顶级会议上发表论文15篇，其中第一作者7篇，担任ICML等会议的reviewer。
- 曾于微软亚洲研究院、网易人工智能事业部和Dashbase实习。
- 高中毕业于浙江省台州市路桥中学，曾获2013年全国青少年信息学奥林匹克联赛（浙江赛区）一等奖。

# Biography
- I was graduated from Chu Kochen Honors College, Zhejiang University (computer science and technology).
- Currently I am a second year master's student in the Department of Computer Science and Technology, Zhejiang University, advised by Zhao Zhou. I also collaborate with Xu Tan, Tao Qin and Tie-yan Liu from MSRA closely.
- I won the [Baidu Scholarship](http://scholarship.baidu.com/) (10 candidates worldwide each year) and ByteDance Scholars Program (10 candidates worldwide each year) in 2020.
- I was selected as one of [the top 100 AI Chinese new stars](https://mp.weixin.qq.com/s?__biz=MzA4NzQ5MTA2NA==&mid=2653639431&idx=1&sn=25b6368c1954419b9090840347d9a27d&chksm=8be75b90bc90d286a5af3ef8e610e822d705dc3cf4382b45e3f14489f3e7ec4fd8c95ed0eceb&mpshare=1&scene=2&srcid=0511LMlj9Qv9DeIZAjMjYAU9&sharer_sharetime=1620731348139&sharer_shareid=631c113940cb81f34895aa25ab14422a#rd) and AI Chinese New Star Outstanding Scholar (10 candidates worldwide each year).
- My research interest includes speech synthesis, neural machine translation and automatic music generation.
- I have published 15 papers at the top international AI conferences such as NeurIPS, ICML, ICLR, KDD.
- I used to be an intern at Microsoft Asia Research (MSRA), NetEase Artificial Intelligence Department and DashBase.
- I won the first prize of the NOIP 2013 (Zhejiang Province) in high school.


# Publications
### 🎙 Speech Synthesis
1. [FastSpeech: Fast, Robust and Controllable Text to Speech](https://papers.nips.cc/paper/8580-fastspeech-fast-robust-and-controllable-text-to-speech.pdf), **Yi Ren**, Yangjun Ruan, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu, Advances in Neural Information Processing Systems (NeurIPS), 2019
  - **学术影响** 谷歌学术引用过百。被多个知名语音项目收录，如百度的 [PaddlePaddle/Parakeet](https://github.com/PaddlePaddle/Parakeet)、[ESPNet](https://github.com/espnet/espnet) (Github Star 3.3k+) 等。被国内外二十多家知名媒体和论坛报道，如[机器之心](https://mp.weixin.qq.com/s/UkFadiUBy-Ymn-zhJ95JcQ)、[InfoQ](https://www.infoq.cn/article/tvy7hnin8bjvlm6g0myu)等。一年来，多个基于FastSpeech的歌声合成、情感化语音合成工作被提出，在泛娱乐领域展示出较大的应用价值。
  - **业界影响** FastSpeech已在微软Azure部署数十种语言的语音合成系统 [(官方报道链接)](https://techcommunity.microsoft.com/t5/azure-ai/neural-text-to-speech-extends-support-to-15-more-languages-with/ba-p/1505911)，相比旧模型节约一半以上的计算成本，降低推理数倍延迟；FastSpeech已在一知智能公司部署应用 [(官方报道链接)](https://zhuanlan.zhihu.com/p/144676195)，在CPU上的推理速度和稳定性相比Tacotron 2有极大提升，大幅节约计算成本；在英伟达开发者大会（GTC2020）上作为语音合成加速的范例展示 [(官方报道链接)](https://resources.nvidia.com/events/GTC2020s21420)
  - [**Demo**](https://speechresearch.github.io/fastspeech/)
1. [FastSpeech 2: Fast and High-Quality End-to-End Text to Speech](https://arxiv.org/abs/2006.04558), **Yi Ren**, Chenxu Hu, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu, International Conference on Learning Representations (ICLR), 2021
  - 第二代FastSpeech模型
  - [**Demo**](https://speechresearch.github.io/fastspeech2/)
1. [Almost Unsupervised Text to Speech and Automatic Speech Recognition](https://pdfs.semanticscholar.org/9075/a3e6271e5ef4953491488d1776527e632408.pdf), **Yi Ren**, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu, International Conference on Machine Learning (ICML) 2019
  - [**Demo**](https://speechresearch.github.io/unsuper/)
1. [DeepSinger: Singing Voice Synthesis with Data Mined From the Web](https://dl.acm.org/doi/abs/10.1145/3394486.3403249), **Yi Ren**, Xu Tan, Tao Qin, Jian Luan, Zhou Zhao, Tie-Yan Liu, 26th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD) 2020 
  - [**Demo**](https://speechresearch.github.io/deepsinger/)
1. [LRSpeech: Extremely Low-Resource Speech Synthesis and Recognition](https://dl.acm.org/doi/abs/10.1145/3394486.3403331), Jin Xu, Xu Tan, **Yi Ren**, Tao Qin, Jian Li, Sheng Zhao, Tie-Yan Liu, 26th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD) 2020 
  - [**Demo**](https://speechresearch.github.io/lrspeech/)
1. [MultiSpeech: Multi-Speaker Text to Speech with Transformer](https://www.isca-speech.org/archive/Interspeech_2020/pdfs/3139.pdf), Mingjian Chen, Xu Tan, **Yi Ren**, Jin Xu, Hao Sun, Sheng Zhao, Tao Qin, Conference of the International Speech Communication Association (INTERSPEECH) 2020
  - [**Demo**](https://speechresearch.github.io/multispeech/)
1. [Denoising Text to Speech with Frame-Level Noise Modeling](https://arxiv.org/abs/2012.09547), Chen Zhang, **Yi Ren**, Xu Tan, Jinglin Liu, Kejun Zhang, Tao Qin, Sheng Zhao, Tie-Yan Liu, International Conference on Acoustics, Speech, and Signal Processing (ICASSP) 2021
  - [**Demo**](https://speechresearch.github.io/denoispeech/)

### 📚 Machine Translation 
1. [SimulSpeech: End-to-End Simultaneous Speech to Text Translation](https://www.aclweb.org/anthology/2020.acl-main.350), **Yi Ren**, Jinglin Liu, Xu Tan, Chen Zhang, Qin Tao, Zhou Zhao, Tie-Yan Liu, Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics (ACL) 2020
1. [Task-Level Curriculum Learning for Non-Autoregressive Neural Machine Translation](https://www.ijcai.org/Proceedings/2020/0534.pdf), Jinglin Liu, **Yi Ren**, Xu Tan, Chen Zhang, Tao Qin, Zhou Zhao and Tie-Yan Liu, the 29th International Joint Conference on Artificial Intelligence (IJCAI) 2020
1. [Multilingual Neural Machine Translation with Knowledge Distillation](https://openreview.net/forum?id=S1gUsoR9YX), Xu Tan, **Yi Ren**, Di He, Tao Qin, Zhou Zhao, Tie-Yan Liu, Seventh International Conference on Learning Representations. (ICLR) 2019
1. [UWSpeech: Speech to Speech Translation for Unwritten Languages](https://arxiv.org/abs/2006.07926), Chen Zhang, Xu Tan, **Yi Ren**, Tao Qin, Kejun Zhang, Tie-Yan Liu, Thirty-Fifth AAAI Conference on Artificial Intelligence (AAAI) 2021
  - [**Demo**](https://speechresearch.github.io/uwspeech/)

### 🎼 Music Generation 
1. [SongMASS: Automatic Song Writing with Pre-training and Alignment Constraint](https://arxiv.org/abs/2012.05168), Zhonghao Sheng, Kaitao Song, Xu Tan, **Yi Ren**, Wei Ye, Shikun Zhang, Tao Qin, Thirty-Fifth AAAI Conference on Artificial Intelligence (AAAI) 2021
1. [PopMAG: Pop Music Accompaniment Generation](https://dl.acm.org/doi/10.1145/3394171.3413721), **Yi Ren**, Jinzheng He, Xu Tan, Tao Qin, Zhou Zhao, Tie-Yan Liu, 28th ACM International Conference on Multimedia (ACM-MM) 2020 
  - [**Demo**](https://speechresearch.github.io/popmag/)

### 💡 Other Sequence Generation Tasks 
1. [FastLR: Non-Autoregressive Lipreading Model with Integrate-and-Fire](https://dl.acm.org/doi/10.1145/3394171.3413740), Jinglin Liu, **Yi Ren**, Zhou Zhao, Chen Zhang, Baoxing Huai, Jing Yuan, 28th ACM International Conference on Multimedia (ACM-MM) 2020 
1. [A Study of Non-autoregressive Model for Sequence Generation](https://www.aclweb.org/anthology/2020.acl-main.15.pdf), **Yi Ren**, Jinglin Liu, Xu Tan, Sheng Zhao, Zhou Zhao, Tie-Yan Liu, Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics (ACL) 2020

# Honors and Awards
- *2020.12* Baidu Scholarship (10 students in the world)
- *2020.12* ByteDance Scholars Program (10 students in China)
- *2020.09* Tianzhou Chen Scholarship (Top 1%)
- *2020.09* National Scholarship (Top 1%)
- *2015.09* National Scholarship (Top 1%)

# Educations
- *2019.06 - Now* Master, Zhejiang Univeristy, Hangzhou.
- *2015.09 - 2019.06* Undergraduate, Chu Kochen Honors College, Zhejiang Univeristy, Hangzhou.
- *2012.09 - 2015.06* Luqiao Middle School, Taizhou.


# Internships
- *2019.02 - 2019.05* YiWise, Hangzhou.
- *2018.08 - 2019.02* MSRA, machine learning Group, Beijing.
- *2018.01 - 2018.06* NetEase, AI department, Hangzhou.
- *2017.08 - 2018.12* DashBase, Hangzhou.
