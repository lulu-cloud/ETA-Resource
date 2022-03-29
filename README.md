<!--
Copyright (c) 2022 lin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
-->

<h1 align="center">
    <p>Encrypted Traffic Analysis Resources</p>
</h1>

<p align="center">
    <a href="https://github.com/linwhitehat/ETA-Resource/blob/main/LICENSE">
        <img alt="GitHub" src="https://img.shields.io/github/license/linwhitehat/ETA-Resource.svg?color=blue">
    </a>
</p>

<h3 align="center">
    <img src="https://github.com/linwhitehat/ETA-Resource/blob/main/ETA.png">
</h3>

# Content
- [About](#about)
- [Dataset](#datasets)
- [Survey](#survey)
- [Encrypted Traffic Classification](#encrypted-traffic-classification)
- [IPv6](#ipv6)
- [Anonymous](#anonymous)
- [ETA with Pre-training](#eta-with-pre-training)
- [ETA with N-shot Learning](#eta-with-n-shot-learning)
- [Blogs](#blogs)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Following](#following)

# About
This is a current list of resources related to the research and development of encrypted traffic analysis.

# Datasets
* [Canadian Institute for Cybersecurity Datasets](https://www.unb.ca/cic/datasets/) (DNS, IDS, DoS, Darknet, Tor, VPN, Botnet, Malware)
* [Cross-Platform](https://recon.meddle.mobi/cross-market.html) (iOS and Android Apps)
* [Malware Capture Facility Project](https://www.stratosphereips.org/datasets-overview) (Malware)
* [CSTNET-TLS 1.3](https://drive.google.com/drive/folders/1JSsYmevkxQFanoKOi_i1ooA6pH3s9sDr?usp=sharing) (TLS 1.3 services)

# Survey
* [Deep Learning for Encrypted Traffic Classification: An Overview](https://ieeexplore.ieee.org/document/8713803/). Shahbaz Rezaei. IEEE Communications Magazine 2019.

# Encrypted Traffic Classification
* [Classifying encrypted traffic using adaptive fingerprints with multi-level attributes](https://link.springer.com/article/10.1007%2Fs11280-021-00940-0). Chang Liu. WWW Journal 2021.
* [FlowPrint: Semi-Supervised Mobile-App Fingerprinting on Encrypted Network Traffic](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24412.pdf). van Ede, Thijs. NDSS 2020. [[code]](https://github.com/Thijsvanede/FlowPrint)
* [FS-Net: A Flow Sequence Network For Encrypted Traffic Classification](https://ieeexplore.ieee.org/document/8737507). Chang Liu. INFOCOM 2019. [[code]](https://github.com/WSPTTH/FS-Net)
* [MaMPF: Encrypted Traffic Classification Based on Multi-Attribute Markov Probability Fingerprints](https://ieeexplore.ieee.org/abstract/document/8624124).  Chang Liu. IWQoS 2018. [[code]](https://github.com/WSPTTH/MaMPF)
* [AppScanner: Automatic Fingerprinting of Smartphone Apps from Encrypted Network Traffic](https://ieeexplore.ieee.org/abstract/document/7467370). Vincent F. Taylor. EuroS&P 2016. [[code]](https://github.com/vftaylor/appscanner)

# IPv6
* [6GAN: IPv6 Multi-Pattern Target Generation via Generative Adversarial Nets with Reinforcement Learning](https://ieeexplore.ieee.org/document/9488912). Tianyu Cui. INFOCOM 2021. [[code]](https://github.com/CuiTianyu961030/6GAN)
* [SiamHAN: IPv6 Address Correlation Attacks on TLS Encrypted Traffic via Siamese Heterogeneous Graph Attention Network](https://www.usenix.org/conference/usenixsecurity21/presentation/cui). Tianyu Cui. USENIX 2021. [[code]](https://github.com/CuiTianyu961030/SiamHAN)
* [6VecLM: Language Modeling in Vector Space for IPv6 Target Generation](https://link.springer.com/chapter/10.1007%2F978-3-030-67667-4_12). Tianyu Cui. ECML/PKDD 2020. [[code]](https://github.com/CuiTianyu961030/6VecLM)

# Anonymous
* [BAPM: Block Attention Profiling Model for Multi-tab Website Fingerprinting Attacks on Tor](https://dl.acm.org/doi/10.1145/3485832.3485891). Zhong Guan. ACSAC 2021.
* [Deep Fingerprinting: Undermining Website Fingerprinting Defenses with Deep Learning](https://dl.acm.org/doi/abs/10.1145/3243734.3243768). Payap Sirinam. CCS 2018. [[code]](https://github.com/deep-fingerprinting/df)

# ETA with Pre-training
* [ET-BERT: A Contextualized Datagram Representation with Pre-training Transformers for Encrypted Traffic Classification](https://arxiv.org/abs/2202.06335). Xinjie Lin. WWW 2022. [[code]](https://github.com/linwhitehat/et-bert)

# ETA with N-shot Learning
* [Triplet Fingerprinting: More Practical and Portable Website Fingerprinting with N-shot Learning](https://dl.acm.org/doi/abs/10.1145/3319535.3354217). Payap Sirinam. CCS 2019. [[code]](https://github.com/triplet-fingerprinting/tf)

# Blogs
## Network Traffic Knowledge
* [Icoding_F2014](https://blog.csdn.net/jmh1996)

## Network Traffic Analysis Tool Manual
* [Tshark](https://www.wireshark.org/docs/man-pages/tshark.html)
<!--
https://dilidonglong.com/2019/04/26/tshark%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95/
-->
* 

# Libraries and Frameworks
* [flowcontainer](https://github.com/jmhIcoding/flowcontainer)
* [scapy](https://scapy.net/)
* [wireshark](https://www.wireshark.org/)
* [Cisco Talos](https://talosintelligence.com/software)

# Following
* [CETAnalytics: Comprehensive effective traffic information analytics for encrypted traffic classification](https://www.sciencedirect.com/science/article/pii/S1389128619309466) (ETA-generalization)
