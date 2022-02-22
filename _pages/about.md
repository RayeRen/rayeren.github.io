---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I was graduated from [Chu Kochen Honors College](http://ckc.zju.edu.cn/ckcen/main.htm), Zhejiang University (浙江大学竺可桢学院). Currently I am a second year master's student in the Department of Computer Science and Technology, Zhejiang University (浙江大学计算机科学与技术学院), advised by [Zhao Zhou (赵洲)](https://person.zju.edu.cn/zhaozhou). I also collaborate with [Xu Tan (谭旭)](https://www.microsoft.com/en-us/research/people/xuta/), [Tao Qin (秦涛)](https://www.microsoft.com/en-us/research/people/taoqin/) and [Tie-yan Liu (刘铁岩)](https://www.microsoft.com/en-us/research/people/tyliu/) from [Microsoft Research Asia](https://www.microsoft.com/en-us/research/group/machine-learning-research-group/) <img src='./images/microsoft_logo.svg' style="width: 4em;"> closely. 

I won the [Baidu Scholarship](https://baike.baidu.com/item/%E7%99%BE%E5%BA%A6%E5%A5%96%E5%AD%A6%E9%87%91/9929412) (10 candidates worldwide each year) and ByteDance Scholars Program (10 candidates worldwide each year) in 2020 and was selected as one of [the top 100 AI Chinese new stars](https://mp.weixin.qq.com/s?__biz=MzA4NzQ5MTA2NA==&mid=2653639431&idx=1&sn=25b6368c1954419b9090840347d9a27d&chksm=8be75b90bc90d286a5af3ef8e610e822d705dc3cf4382b45e3f14489f3e7ec4fd8c95ed0eceb&mpshare=1&scene=2&srcid=0511LMlj9Qv9DeIZAjMjYAU9&sharer_sharetime=1620731348139&sharer_shareid=631c113940cb81f34895aa25ab14422a#rd) and AI Chinese New Star Outstanding Scholar (10 candidates worldwide each year). 

My research interest includes speech synthesis, neural machine translation and automatic music generation.I have published more than 20 papers at the top international AI conferences such as NeurIPS, ICML, ICLR, KDD with total <a href='https://scholar.google.com/citations?user=4FA6C0AAAAAJ'>google scholar citations <strong><span id='total_cit'>1000+</span></strong></a>. 

To promote the communication among the Chinese ML & NLP community, we (along with other 11 young scholars worldwide) founded the [MLNLP community](https://space.bilibili.com/168887299) in 2021. I am honored to be one of the chairs of the MLNLP committee.


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 My [google scholar](https://scholar.google.com/citations?user=4FA6C0AAAAAJ) citations have exceeded 1000!
- *2022.02*: We public a Non-Autoregressive Text-to-Speech (NAR-TTS) framework [NATSpeech ![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social)](https://github.com/NATSpeech/NATSpeech), including official PyTorch implementation of PortaSpeech (NeurIPS 2021) and DiffSpeech (AAAI 2022). 🎉🎉 It was shown on the [Github Daily Trending List](https://github.motakasoft.com/trending/?d=2022-02-19&l=all) on 19 Feb 2022!


# 📝 Publications 
## 🎙 Speech Synthesis


<div class='paper-box'><div class='paper-box-image'><img src='images/fs.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[FastSpeech: Fast, Robust and Controllable Text to Speech](https://papers.nips.cc/paper/8580-fastspeech-fast-robust-and-controllable-text-to-speech.pdf), **Yi Ren**, Yangjun Ruan, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

**NeurIPS 2019** \| [**Project**](https://speechresearch.github.io/fastspeech/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- FastSpeech is the first fully parallel end-to-end speech synthesis model.
- **Academic Impact**: This work is included by many famous speech synthesis open-source projects, such as [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet). Our work are promoted by more than 20 media and forums, such as [机器之心](https://mp.weixin.qq.com/s/UkFadiUBy-Ymn-zhJ95JcQ)、[InfoQ](https://www.infoq.cn/article/tvy7hnin8bjvlm6g0myu).
- **Industry Impact**: FastSpeech has been deployed in [Microsoft Azure TTS service](https://techcommunity.microsoft.com/t5/azure-ai/neural-text-to-speech-extends-support-to-15-more-languages-with/ba-p/1505911) and supports 49 more languages with state-of-the-art AI quality. It was also shown as a text-to-speech system acceleration example in [NVIDIA GTC2020](https://resources.nvidia.com/events/GTC2020s21420).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/fs2.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[FastSpeech 2: Fast and High-Quality End-to-End Text to Speech](https://arxiv.org/abs/2006.04558) **Yi Ren**, Chenxu Hu, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

**ICLR 2021** \| [**Project**](https://speechresearch.github.io/fastspeech2/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong>
  - FastSpeech 2 addresses the issues in FastSpeech and better solves the one-to-many mapping problem in TTS by introducing more variation information of speech as conditional inputs. 
  - We further design FastSpeech 2s, which is the first attempt to generate speech waveform from text in parallel directly.
  - **Academic Impact**: This work is included by many famous speech synthesis open-source projects, such as [PaddlePaddle/Parakeet ![](https://img.shields.io/github/stars/PaddlePaddle/PaddleSpeech?style=social)](https://github.com/PaddlePaddle/PaddleSpeech), [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet) and [fairseq ![](https://img.shields.io/github/stars/pytorch/fairseq?style=social)](https://github.com/pytorch/fairseq).
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><img src='images/portaspeech.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[PortaSpeech: Portable and High-Quality Generative Text-to-Speech](https://arxiv.org/abs/2109.15166), **Yi Ren**, Jinglin Liu, Zhou Zhao

**NeurIPS 2021** \| [**Project**](https://portaspeech.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=Code Stars)](https://github.com/NATSpeech/NATSpeech) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/PortaSpeech)
- We propose PortaSpeech, a portable and high-quality generative text-to-speech model.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/diffsinger.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[DiffSinger: Singing Voice Synthesis via Shallow Diffusion Mechanism](https://arxiv.org/abs/2105.02446), Jinglin Liu, Chengxi Li, **Yi Ren**, Feiyang Chen, Zhou Zhao

**AAAI 2022** \| [**Project**](https://diffsinger.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=DiffSpeech Stars)](https://github.com/NATSpeech/NATSpeech) \| [![](https://img.shields.io/github/stars/MoonInTheRiver/DiffSinger?style=social&label=DiffSinger Stars)](https://github.com/MoonInTheRiver/DiffSinger) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/DiffSpeech)

- We propose DiffSinger, an acoustic model for SVS based on the diffusion probabilistic model. 
</div>
</div>



- [ProsoSpeech: Enhancing Prosody With Quantized Vector Pre-training in Text-to-Speech](https://prosospeech.github.io/), **Yi Ren**, Ming Lei, Zhiying Huang,  Shiliang Zhang, Qian Chen, Zhijie Yan, Zhou Zhao, **ICASSP 2022**
- [EMOVIE: A Mandarin Emotion Speech Dataset with a Simple Emotional Text-to-Speech Model](https://arxiv.org/abs/2106.09317), Chenye Cui, **Yi Ren**, Jinglin Liu, Feiyang Chen, Rongjie Huang, Ming Lei and Zhou Zhao, **INTERSPEECH 2021**
- [WSRGlow: A Glow-based Waveform Generative Model for Audio Super-Resolution](https://arxiv.org/abs/2106.08507), Kexun Zhang, **Yi Ren**, Changliang Xu and Zhou Zhao, **INTERSPEECH 2021** <span style="color:red">(best student paper award candidate)</span>
- [Denoising Text to Speech with Frame-Level Noise Modeling](https://arxiv.org/abs/2012.09547), Chen Zhang, **Yi Ren**, Xu Tan, Jinglin Liu, Kejun Zhang, Tao Qin, Sheng Zhao, Tie-Yan Liu, **ICASSP 2021** \| [**Project**](https://speechresearch.github.io/denoispeech/)
- [Multi-Singer: Fast Multi-Singer Singing Voice Vocoder With A Large-Scale Corpus](https://arxiv.org/pdf/2112.10358), Rongjie Huang, Feiyang Chen, **Yi Ren**, Jinglin Liu, Chenye Cui, Zhou Zhao, **ACM-MM 2021** <span style="color:red">(Oral)</span>
- [FedSpeech: Federated Text-to-Speech with Continual Learning](https://www.ijcai.org/proceedings/2021/527), Ziyue Jiang, **Yi Ren**, Ming Lei and Zhou Zhao, **IJCAI 2021**
- [DeepSinger: Singing Voice Synthesis with Data Mined From the Web](https://dl.acm.org/doi/abs/10.1145/3394486.3403249), **Yi Ren**, Xu Tan, Tao Qin, Jian Luan, Zhou Zhao, Tie-Yan Liu, **KDD 2020** \| [**Project**](https://speechresearch.github.io/deepsinger/)
- [LRSpeech: Extremely Low-Resource Speech Synthesis and Recognition](https://dl.acm.org/doi/abs/10.1145/3394486.3403331), Jin Xu, Xu Tan, **Yi Ren**, Tao Qin, Jian Li, Sheng Zhao, Tie-Yan Liu, **KDD 2020** \| [**Project**](https://speechresearch.github.io/lrspeech/)
- [MultiSpeech: Multi-Speaker Text to Speech with Transformer](https://www.isca-speech.org/archive/Interspeech_2020/pdfs/3139.pdf), Mingjian Chen, Xu Tan, **Yi Ren**, Jin Xu, Hao Sun, Sheng Zhao, Tao Qin, **INTERSPEECH 2020** \| [**Project**](https://speechresearch.github.io/multispeech/)
- [Almost Unsupervised Text to Speech and Automatic Speech Recognition](https://pdfs.semanticscholar.org/9075/a3e6271e5ef4953491488d1776527e632408.pdf), **Yi Ren**, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu, **ICML 2019** <span style="color:red">(Oral)</span> \| [**Project**](https://speechresearch.github.io/unsuper/) 

## 👄 Lip Generation/Understanding
- [Parallel and High-Fidelity Text-to-Lip Generation](https://arxiv.org/abs/2107.06831), Jinglin Liu, Zhiying Zhu, **Yi Ren**, Wencan Huang, Baoxing Huai, Nicholas Yuan, Zhou Zhao, **AAAI 2022**
- Flow-based Unconstrained Lip to Speech Generation, Jinzheng He, Zhou Zhao, **Yi Ren**, Jinglin Liu, Baoxing Huai, Nicholas Yuan, **AAAI 2022**
- [FastLR: Non-Autoregressive Lipreading Model with Integrate-and-Fire](https://dl.acm.org/doi/10.1145/3394171.3413740), Jinglin Liu, **Yi Ren**, Zhou Zhao, Chen Zhang, Baoxing Huai, Jing Yuan, **ACM-MM 2020**

## 📚 Machine Translation 
- [UWSpeech: Speech to Speech Translation for Unwritten Languages](https://arxiv.org/abs/2006.07926), Chen Zhang, Xu Tan, **Yi Ren**, Tao Qin, Kejun Zhang, Tie-Yan Liu, **AAAI 2021** \| [**Project**](https://speechresearch.github.io/uwspeech/)
- [Task-Level Curriculum Learning for Non-Autoregressive Neural Machine Translation](https://www.ijcai.org/Proceedings/2020/0534.pdf), Jinglin Liu, **Yi Ren**, Xu Tan, Chen Zhang, Tao Qin, Zhou Zhao and Tie-Yan Liu, **IJCAI 2020**
- [SimulSpeech: End-to-End Simultaneous Speech to Text Translation](https://www.aclweb.org/anthology/2020.acl-main.350), **Yi Ren**, Jinglin Liu, Xu Tan, Chen Zhang, Qin Tao, Zhou Zhao, Tie-Yan Liu, **ACL 2020**
- [A Study of Non-autoregressive Model for Sequence Generation](https://arxiv.org/abs/2004.10454), **Yi Ren**, Jinglin Liu, Xu Tan, Zhou Zhao, Sheng Zhao, Tie-Yan Liu, **ACL 2020**
- [Multilingual Neural Machine Translation with Knowledge Distillation](https://openreview.net/forum?id=S1gUsoR9YX), Xu Tan, **Yi Ren**, Di He, Tao Qin, Zhou Zhao, Tie-Yan Liu, **ICLR 2019**

## 🎼 Music Generation 
- [SongMASS: Automatic Song Writing with Pre-training and Alignment Constraint](https://arxiv.org/abs/2012.05168), Zhonghao Sheng, Kaitao Song, Xu Tan, **Yi Ren**, Wei Ye, Shikun Zhang, Tao Qin, **AAAI 2021**
- [PopMAG: Pop Music Accompaniment Generation](https://dl.acm.org/doi/10.1145/3394171.3413721), **Yi Ren**, Jinzheng He, Xu Tan, Tao Qin, Zhou Zhao, Tie-Yan Liu, **ACM-MM 2020** <span style="color:red">(Oral)</span> \| [**Project**](https://speechresearch.github.io/popmag/)

## 🧑‍🎨 Generative Model
- [Pseudo Numerical Methods for Diffusion Models on Manifolds](https://openreview.net/forum?id=PlKWVd2yBkY), Luping Liu, **Yi Ren**, Zhijie Lin, Zhou Zhao, **ICLR 2022** \| [![](https://img.shields.io/github/stars/luping-liu/PNDM?style=social&label=Code Stars)](https://github.com/luping-liu/PNDM) \| [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/pseudo-numerical-methods-for-diffusion-models/image-generation-on-celeba-64x64)](https://paperswithcode.com/sota/image-generation-on-celeba-64x64?p=pseudo-numerical-methods-for-diffusion-models)


# 🎖 Honors and Awards
- *2021.10* Tencent Scholarship (Top 1%)
- *2021.10* National Scholarship (Top 1%)
- *2020.12* [Baidu Scholarship](https://baike.baidu.com/item/%E7%99%BE%E5%BA%A6%E5%A5%96%E5%AD%A6%E9%87%91/9929412) (10 students in the world each year)
- *2020.12* [AI Chinese new stars](https://mp.weixin.qq.com/s?__biz=MzA4NzQ5MTA2NA==&mid=2653639431&idx=1&sn=25b6368c1954419b9090840347d9a27d&chksm=8be75b90bc90d286a5af3ef8e610e822d705dc3cf4382b45e3f14489f3e7ec4fd8c95ed0eceb&mpshare=1&scene=2&srcid=0511LMlj9Qv9DeIZAjMjYAU9&sharer_sharetime=1620731348139&sharer_shareid=631c113940cb81f34895aa25ab14422a#rd) (100 worldwide each year)
- *2020.12* [AI Chinese New Star Outstanding Scholar](https://mp.weixin.qq.com/s?__biz=MzA4NzQ5MTA2NA==&mid=2653639431&idx=1&sn=25b6368c1954419b9090840347d9a27d&chksm=8be75b90bc90d286a5af3ef8e610e822d705dc3cf4382b45e3f14489f3e7ec4fd8c95ed0eceb&mpshare=1&scene=2&srcid=0511LMlj9Qv9DeIZAjMjYAU9&sharer_sharetime=1620731348139&sharer_shareid=631c113940cb81f34895aa25ab14422a#rd) (10 candidates worldwide each year)
- *2020.12* ByteDance Scholars Program (10 students in China each year)
- *2020.10* Tianzhou Chen Scholarship (Top 1%)
- *2020.10* National Scholarship (Top 1%)
- *2015.10* National Scholarship (Undergraduate) (Top 1%)

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Master, Zhejiang Univeristy, Hangzhou.
- *2015.09 - 2019.06*, Undergraduate, Chu Kochen Honors College, Zhejiang Univeristy, Hangzhou.
- *2012.09 - 2015.06*, Luqiao Middle School, Taizhou.

# 💬 Invited Talks
- *2021.06*, Audio & Speech Synthesis, Huawei internal talk
- *2021.03*, Non-autoregressive Speech Synthesis, PaperWeekly & biendata \| [\[video\]](https://www.bilibili.com/video/BV1uf4y1t7Hr/)
- *2020.12*, Non-autoregressive Speech Synthesis, Huawei Noah's Ark Lab internal talk

# 💻 Internships
- *2019.05 - 2020.02*, [EnjoyMusic](https://enjoymusic.ai/), Hangzhou.
- *2019.02 - 2019.05*, [YiWise](https://www.yiwise.com/), Hangzhou.
- *2018.08 - 2019.02*, [MSRA, machine learning Group](https://www.microsoft.com/en-us/research/group/machine-learning-research-group/), Beijing.
- *2018.01 - 2018.06*, [NetEase, AI department](https://hr.163.com/zc/12-ai/index.html), Hangzhou.
- *2017.08 - 2018.12*, DashBase (acquired by [Cisco](https://blogs.cisco.com/news/349511)), Hangzhou.
