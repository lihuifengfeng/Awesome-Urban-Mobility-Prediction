This is a list of useful information about urban mobility prediction. Related papers, datasets and codes are included.

### Dataset
1. [Foursquare](https://sites.google.com/site/yangdingqi/home/foursquare-dataset?authuser=0)
2. [Gowalla](https://snap.stanford.edu/data/loc-gowalla.html)
3. [Yelp](https://www.yelp.com/dataset)
4. [Brightkite](https://snap.stanford.edu/data/loc-Brightkite.html)
5. [Weeplaces](https://www.yongliu.org/datasets/)
6. [Instagram](https://data.world/datasets/instagram)

### Next Place Recommendation
Papers | Authors | Code | Year | Venue | Performance |
-------|-------|------|------|----------|----------|
A recurrent model with spatial and temporal contexts.(ST-RNN)([Paper](https://ojs.aaai.org/index.php/AAAI/article/view/9971)) | Qiang Liu(CAS), Shu Wu, Liang Wang, Tieniu Tan | [Code](https://github.com/yongqyu/STRNN) | 2016 | AAAI | **Gowalla:** <br>Rec@5 =0.1524, Rec@10=0.2714.<br>**GTD:** <br>Rec@5=0.4986, Rec@10=0.6812. |
Geo-teaser: Geo-temporal sequential embedding rank for point-of-interest recommendation.(Geo-teaser)([Paper](https://dl.acm.org/doi/abs/10.1145/3041021.3054138)) | Shenglin Zhao(CUHK), Tong Zhao, Irwin King, and Michael R. Lyu | [Code](https://github.com/JasonLiu-THU/geo_teaser) | 2017 | WWW | **Foursquare:** <br>Prec@5=0.13, Prec@10=0.1, Rec@5=0.15, Rec@10=0.2<br>**Gowalla:** <br>Prec@5=0.16, Prec@10=0.13, Rec@5=0.07, Rec@10=0.1 |
Next point-of-interest recommendation with temporal and multi-level context attention.(TMCA)([Paper](https://ieeexplore.ieee.org/abstract/document/8594953)) | Ranzhen Li(SJTU), Yanyan Shen, Yanmin Zhu | [Code](https://github.com/zhenql/TMCA) | 2018 | ICDM | **Gowalla:** <br>Rec@5=0.21926, Rec@10=0.27725.<br>**Foursquare:** <br>Rec@5=0.02870, Rec@10=0.04809. |
HST-LSTM: A Hierarchical Spatial-Temporal Long-Short Term Memory Network for Location Prediction.(HST-LSTM)([Paper](https://www.ijcai.org/Proceedings/2018/0324.pdf)) | Dejiang Kong(ZJU), Fei Wu | None | 2018 | IJCAI | **Baidu Map:** <br>Acc@10=0.4847, Acc@20=0.5657. |
Content-aware hierarchical point-of-interest embedding model for successive poi recommendation.(CAPE)([Paper](https://www.ijcai.org/Proceedings/2018/0458.pdf)) | Buru Chang(KU), Yonggyu Park, Donghyeon Park, Seongsoon Kim, Jaewoo Kang | [Code](https://github.com/qnfnwkd/CAPE) | 2018 | IJCAI |**With STELLAR:** <br>Rec@5=0.2384, Rec@10=0.2989.<br>**With LSTM:** <br>Rec@5=0.2412, Rec@10=0.3054.<br>**With GRU:** <br>Rec@5=0.2433, Rec@10=0.3079.<br>**With ST-RNN:** <br>Rec@5=0.2239, Rec@10=0.2601. |
DeepMove: Predicting Human Mobility with Attentional Recurrent Networks.(DeepMove)([Paper](https://dl.acm.org/doi/abs/10.1145/3178876.3186058)) | Jie Feng(THU), Yong Li, Chao Zhang, Funing Sun, Fanchao Meng, Ang Guo, Depeng Jin | [Code](https://github.com/vonfeng/DeepMove) | 2018 | WWW | **Foursquare (NY):** <br>Rec@5=0.3372, Rec@10=0.4091.<br>**Gowalla:** <br>Rec@5=0.2021, Rec@10=0.2510. |
Long-and short-term preference learning for next poi recommendation.(LSPL)([Paper](https://dl.acm.org/doi/abs/10.1145/3357384.3358171)) | Yuxia Wu(XJTU), Ke Li, Guoshuai Zhao, Xueming Qian| None | 2019 | CIKM | **Foursquare (NYC):** <br>Prec3@10=0.3901, Prec@20=0.4461.<br>**Foursquare (TKY):** <br>Prec@10=0.3986, Prec@20=0.4596. |
Where to go next: A spatio-temporal gated network for next poi recommendation.(STGN)([Paper19](https://ojs.aaai.org//index.php/AAAI/article/view/4950), [Paper20](https://ieeexplore.ieee.org/abstract/document/9133505)) | Pengpeng Zhao(SUDA), Haifeng Zhu, Yanchi Liu, Jiajie Xu, Zhixu Li, Fuzhen Zhuang, Victor S. Sheng, Xiaofang Zhou | None | 2019 | AAAI (2020 TKDE) | **Foursquare (CA):** <br>Acc@5=0.1308, Acc@10=0.1612.<br>**Foursquare (SIN):** <br>Acc@5=0.2737, Acc@10=0.3017.<br>**Gowalla:** <br>Acc@5=0.1644, Acc@10=0.2020.<br>**Brightkite:** <br>Acc@5=0.4953, Acc@10=0.5231. |
Topic-Enhanced Memory Networks for Personalised Point-of-Interest Recommendation.(TEMN)([Paper](https://dl.acm.org/doi/abs/10.1145/3292500.3330781)) | Xiao Zhou(Cambridge), Cecilia Mascolo, Zhongxiang Zhao | [Code](https://github.com/XiaoZHOUCAM/Topic-Enhanced-Memory-Networks-for-Personalised-Point-of-Interest-Recommendation) | 2019 | KDD |**WeChat (GPR):**<br>TEMN (GPR): Acc@5=0.70389, Acc@10=0.81752.<br>TEMN (CPR): Acc@5=0.72876, Acc@10=0.83398. |
Location prediction over sparse user mobility traces using rnns: Flashback in hidden states!(Flashback)([Paper](https://www.ijcai.org/Proceedings/2020/0302.pdf)) | Dingqi Yang(UM), Benjamin Fankhauser, Paolo Rosso, Philippe Cudre-Mauroux | [Code](https://github.com/eXascaleInfolab/Flashback_code) | 2020 | IJCAI | **Foursquare:** <br>Acc2@5=0.5399, Acc@10=0.6236.<br>**Gowalla:** <br>Acc@5=0.2754, Acc@10=0.3479. |
Discovering subsequence patterns for next poi recommendation!(ASPPA)([Paper](https://www.ijcai.org/Proceedings/2020/0445.pdf)) | Kangzhi Zhao(THU) | None | 2020 | IJCAI | **Foursquare (US):** <br>Acc@10=0.3371, Acc@20=0.3950.<br>**Gowalla:** <br>Acc@10=0.2947, Acc@20=0.3573. |
Next Point-of-Interest Recommendation on Resource-Constrained Mobile Devices.(LLRec)([Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380170)) | Qinyong Wang(UQ) | None | 2020 | WWW | **Foursquare:** <br>Acc@10=0.3542, Acc@20=0.4594.<br>**Gowalla:** <br>Acc@10=0.3874, Acc@20=0.4781. |
Personalized Long- and Short-term Preference Learning for Next POI Recommendation.(PLSPL)([Paper](https://ieeexplore.ieee.org/abstract/document/9117156)) | Yuxia Wu(XJTU), Ke Li, Guoshuai Zhao, Xueming Qian | None | 2020 | TKDE | **Foursquare (NYC):** <br>Prec@10=0.3953, Prec@20=0.4475<br>**Foursquare (TKY):** <br>Prec@10=0.4020, Prec@20=0.4664. |
Where to go next: Modeling long-and short-term user preferences for point-ofinterest recommendation.(LSTPM)([Paper](https://ojs.aaai.org/index.php/AAAI/article/view/5353)) | Ke Sun(WHU), Tieyun Qian, Tong Chen, Yile Liang, Quoc Viet Hung Nguyen, Hongzhi Yin | [Code](https://github.com/NLPWM-WHU/LSTPM) | 2020 | AAAI | **Foursquare (NY):** <br>Rec@5=0.3372, Rec@10=0.4091.<br>**Gowalla:** <br>Rec@5=0.2021, Rec@10=0.2510. |
An Interactive Multi-Task Learning Framework for Next POI Recommendation with Uncertain Check-ins.(iMTL)([Paper](https://www.ijcai.org/Proceedings/2020/0491.pdf)) | Lu Zhang( NTU) | None | 2020 | IJCAI | **Foursquare (CLT):** <br>Rec@10=0.0534, Map4@10=0.0238.<br>**Foursquare (CAL):** <br>Rec@10=0.0691, Map@10=0.0443.<br>**Foursquare (PHO):** <br>Rec@10=0.0769, Map@10=0.0352. |
A Category-Aware Deep Model for Successive POI Recommendation on Sparse Check-in Data.(CatDM)([Paper](https://dl.acm.org/doi/abs/10.1145/3366423.3380202)) | Fuqiang Yu(SDU), Lizhen Cui, Wei Guo, Xudong Lu, Qingzhong Li, Hua Lu | [Code](https://github.com/fqyuu/CatDM) | 2020 | WWW | **Foursquare (NYC):** Rec@5=0.2407, Rec@10=0.3113.<br>**Foursquare (TKY):** <br>Rec@5=0.2148, Rec@10=0.2739. |
An attentional recurrent neural network for personalized next location recommendation.(ARNN)([Paper](https://ojs.aaai.org/index.php/AAAI/article/view/5337)) | Qing Guo(NTU), Zhu Sun, Jie Zhang, Yin-Leng Theng | None | 2020 | WWW | **Foursquare (NY):** <br>Acc@10=0.4162, Acc@20=0.4393<br>**Foursquare (TK):** <br>Acc@10=0.4285, Acc@20=0.4864<br>**Gowalla (SF):** <br>Acc@10=0.2336, Acc@20=0.2530. |
Exploiting geographical-temporal awareness attention for next point-of-interest recommendation.(GT-HAN)([Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231220300680)) | Tongcun Liu(BUPT), Jianxin Liao, Zhigen Wu, Yulong Wang, Jingyu Wang | None | 2020 | Neurocomputing | **Foursquare:** <br>AUC8=0.9661, acc@5: 0.13-0.15, acc@10: 0.17-0.19, acc@20: 0.23-0.25 (depending on latent dimensionality). |
Time-Aware Location Prediction by Convolutional Area-of-Interest Modeling and Memory-Augmented Attentive LSTM.(t-LocPred)([Paper](https://ieeexplore.ieee.org/abstract/document/9128016)) | Chi Harold Liu(BIT), Yu Wang, Chengzhe Piao, Zipeng Dai, Ye Yuan, Guoren Wang, Dapeng Wu | None | 2020 | TKDE | **Gowalla:** <br>MRR5=0.247 (C=6, all),<br>**Weeplaces:** <br>MRR=0.277 (C=6, all),<br>**Brightkite:** <br>MRR=0.388 (C=4, all). |
Content-Aware Successive Point-of-Interest Recommendation.(CAPRE)([Paper](https://epubs.siam.org/doi/abs/10.1137/1.9781611976236.12)) | Buru Chang(KU), Yookyung Koh, Donghyeon Park, Jaewoo Kang | None | 2020 | SDM | **Foursquare:** <br>Rec@5=0.1724, Rec@10=0.2084<br>**Instagram:** <br>Rec@5=0.2934, Rec@10=0.3588. |
Geography-Aware Sequential Location Recommendation.(GeoSAN)([Paper](https://dl.acm.org/doi/abs/10.1145/3394486.3403252)) | Defu Lian(USTC), Yongji Wu, Yong Ge, Xing Xie, Enhong Chen | [Code](https://github.com/libertyeagle/GeoSAN) | 2020 | KDD | **Foursquare:** <br>Acc@5=0.3735, Acc@10=0.4867.<br>**Gowalla:** <br>Acc@5=0.4951, Acc@10=0.6028.<br>**Brightkite:** <br>Acc@5=0.5258, Acc@10=0.6425. |
Modeling hierarchical category transition for next POI recommendation with uncertain check-ins.(HCT)([Paper](https://www.sciencedirect.com/science/article/abs/pii/S0020025519311144)) | Lu Zhang(NTU), Zhu Sun, Jie Zhang, Horst Kloeden, Felix Klanner | None | 2020 | Information Sciences, Elsevier | **Foursquare(SIN):** <br>Prec@5=0.613 Rec@5=0.0403<br>**Foursquare(NYC):** <br>Prec@5=0.0585, Rec@5=0.0352<br>**Foursquare(LA):** Prec@5=0.0653, Rec@5=0.0305. |
HME: A Hyperbolic Metric Embedding Approach for Next-POI Recommendation.(HME)([Paper](https://dl.acm.org/doi/abs/10.1145/3397271.3401049)) | Shanshan Feng(Abu Dhabi, UAE), Lucas Vinh Tran, Gao Cong, Lisi Chen, Jing Li, Fan Li | None | 2020 | SIGIR | **Foursquare (NYC):** <br>Rec@5=0.0962, Rec@10=0.1371.<br>**Foursquare (TKY):** <br>Rec@5=0.1527, Rec@10=0.2172.<br>**Gowalla (Houston):** <br>Rec@5=0.1533, Rec@10=0.2318. |
Location Prediction via Bi-direction Speculation and Dual-level Association.([paper](https://arxiv.org/abs/2106.15070))|Xixi Li(WHU),Ruimin Hu, Zheng Wang,Toshihiko Yamasaki | None | 2021 | ijcai | **Gowalla:** <br> Acc@1=0.1454,<br> Acc@5=0.3531,<br> Acc@10=0.4192,<br> MRR=0.2431.<br> **Foursquare:** <br> Acc@1=0.3068,<br> Acc@5=0.6612,<br> Acc@10=0.7136,<br> MRR=0.4505. |
SNPR A Serendipity-Oriented Next POI Recommendation Model.(SNPR)([paper](https://dl.acm.org/doi/10.1145/3459637.3482394)) | Mingwei Zhang(Northeastern University Shenyang, China),Yang Yang,Rizwan Abbas,Ke Deng,Jianxin Li,Bin Zhang | None | 2021 | CIKM | **Foursquare(NewYork):** <br> Prec@3=0.05695,<br> Prec@5=0.05325,<br> Prec@10=0.04829,<br> Prec@20=0.03425.<br> **Foursquare(United Kingdom):** <br> Prec@3=0.04346,<br> Prec@5=0.03842,<br> Prec@10=0.03651,<br> Prec@20=0.02502.|
LightMove: A Lightweight Next-POI Recommendation forTaxicab Rooftop Advertising.(LightMove)([paper](https://dl.acm.org/doi/abs/10.1145/3459637.3481935)) | Jinsung Jeon(Yonsei University,Seoul, South Korea),Soyoung Kang,Minju Jo, Seunghyeon Cho,Noseong Park,Seonghoon Kim,Chiyoung Song | [code](https://github.com/Jinsung-Jeon/LightMove) | 2021 | CIKM | **Texi:** <br> Hits@1=0.9988,<br> Hits@5=1.0000,<br> Hits@10=1.0000,<br> MRR=0.9994.<br> **Foursquare:** <br> Hits@1=0.1545,<br> Hits@5=0.3203,<br> Hits@10=0.3656,<br> MRR=0.2288. <br> **LA:** <br> Hits@1=0.3209,<br> Hits@5=0.4431,<br> Hits@10=0.4758,<br> MRR=0.0.3756.|
ST-PIL: Spatial-Temporal Periodic Interest Learning for Next Point-of-Interest Recommendation.(ST-PIL) ([paper](https://arxiv.org/abs/2104.02262)) | Qiang Cui(Meituan, Beijing, China), Chenrui Zhang, Yafeng Zhang, Jinpeng Wang, Mingchen Cai | None | 2021 | CIKM | **NYC:** <br> Acc@1=0.3807,<br>  Acc@5=0.5850,<br>  Acc@10=0.6454,<br> MRR@5=0.4584,<br> MRR@10=0.4666.<br> **TKY:** <br> Acc@1=0.3523,<br> Acc@5=0.5963,<br> Acc@10=0.6772,<br> MRR@5=0.4455，<br> MRR@10=0.4564.|
STAN: Spatio-Temporal Attention Network for Next Location Recommendation.(STAN)([paper](https://dl.acm.org/doi/fullHtml/10.1145/3442381.3449998)) | Yingtao Luo(University of Washington),Qiang Liu,Zhaocheng Liu | [code](https://github.com/yingtaoluo/Spatial-Temporal-Attention-Network-for-POI-Recommendation) | 2021 | www | **Gowalla:** <br> Recall@5 =0.3016,<br> Recall@10=0.3998.<br> **TKY:** <br> Recall@5 =0.3461,<br> Recall@10=0.4264. <br> **SIN:** <br> Recall@5 =0.3751,<br> Recall@10=0.4301.<br> **NYC:** <br> Recall@5 =0.4669,<br> Recall@10=0.5962.|
Predicting Destinations by a Deep Learning based Approach(LATL)([paper](https://ieeexplore.ieee.org/document/8787889))|Jiajie Xu(Soochow University),Jing Zhao,Rui Zhou,Chengfei Liu,Pengpeng Zhao,Lei Zhao|None|2021|TKDE|**Beijing trajectory datasets:**<br>Acc@1=0.3570,<br>Acc@5=0.6444,<br>Acc@10=0.7165,<br>Acc@20=0.8001.<br>**Chengdu trajectory datasets:**<br>Acc@1=0.3354,<br>Acc@5=0.5344,<br>Acc@10=0.6251,<br>Acc@20=0.7163.|
PREMERE: Meta-Reweighting via Self-Ensembling for Point-of-Interest Recommendation(PREMERE)([paper](https://ojs.aaai.org/index.php/AAAI/article/view/16539))|Minseok Kim(KAIST), Hwanjun Song, Doyoung Kim, Kijung Shin, Jae-Gil Lee|[code](https://github.com/kaist-dmlab/PREMERE)|2021|AAAI|**Gowalla:**<br>Precision@5=0.1389.<br>**Foursquare:**<br>Precision@5=0.0911.<br>**Yelp:**<br>Precision@5=0.0545.|
Discovering Collaborative Signals for Next POI Recommendation with Iterative Seq2Graph Augmentation(SGRec)([paper](https://arxiv.org/abs/2106.15814))|Yang Li(The University of Queensland) , Tong Chen , Yadan Luo , Hongzhi Yin , Zi Huang|None|2021|ijcai|**Foursquare:**<br>HR@1=0.195,<br>HR@5=0.362,<br>HR@10=0.402,<br>HR@20=0.465.<br>**Gowalla:**<br>HR@1=0.067,<br>HR@5=0.118,<br>HR@10=0.137,<br>HR@20=0.151.|
Graph-Flashback Network for Next Location Recommendation([paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539383))|Xuan Rao(University of Electronic Science and Technology of China),Lisi Chen,Yong Liu,Shuo Shang, Bin Yao, Peng Han|[code](https://github.com/kevin-xuan/Graph-Flashback)|2022|KDD|**Gowalla:**<br>Acc@1=0.1512,<br>Acc@5=0.3425,<br>Acc@10=0.4256,<br>MRR=0.2422.<br>**Foursquare:**<br>Acc@1=0.2805,<br>Acc@5=0.5757,<br>Acc@10=0.6514,<br>MRR=0.4136.|
MetaPTP: An Adaptive Meta-optimized Model for Personalized Spatial Trajectory Prediction(MetaPTP)([paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539360))|Yuan Xu(Soochow University),Jiajie Xu,Jing Zhao,Kai Zheng,An Liu,Lei Zhao|None|2022|KDD|**Taxi trajectories in Beijing:**<br>Acc@1=0.6186,<br>Acc@2=0.7864,<br>Acc@3=0.8578,<br>MRR=0.7467.<br>**Taxi trajectories in Porto:**<br>Acc@1=0.5310,<br>Acc@2=0.7233,<br>Acc@3=0.8176,<br>MRR=0.6832.|
Modeling Spatio-temporal Neighbourhood for Personalized Point-of-interest Recommendation(STGCAN)([paper](https://www.ijcai.org/proceedings/2022/490))|Xiaolin Wang(Donghua University),Guohao Sun,Xiu Fang,Jian Yang, Shoujin Wang|[code](https://github.com/greenwangzero/STGCAN)|2022|ijcai|**NYC:**<br>Recall@1=0.257,<br>Recall@5=0.544,<br>Recall@10=0.629.<br>**TKY:**<br>Recall@1=0.171,<br>Recall@5=0.384,<br>Recall@10=0.457.<br>**Gowalla:**<br>Recall@1=0.129,<br>Recall@5=0.343,<br>Recall@10=0.414.|
Next Point-of-Interest Recommendation with Inferring Multi-step Future Preferences(CFPRec)([paper](https://www.ijcai.org/proceedings/2022/0521.pdf))|Lu Zhang(Nanyang Technological University, Singapore),Zhu Sun,Ziqing Wu,Jie Zhang,Yew Soon Ong,Xinghua Qu|[code](https://github.com/wuziqi2/CFPRec)|2022|ijcai|**SIN:**<br>HR@5=0.2310,<br>HR@10=0.3085,<br>NDCG@5=0.1588,<br>NDCG@10=0.1836.<br>**NYC:**<br>HR@5=0.2771,<br>HR@10=0.3606,<br>NDCG@5=0.1971,<br>NDCG@10=0.2190.<br>**PHO:**<br>HR@5=0.3421,<br>HR@10=0.4253,<br>NDCG@5=0.2432,<br>NDCG@10=0.2730.|
Where to Go Next: A Spatio-Temporal Gated Network for Next POI Recommendation(NeuNext)(https://ieeexplore.ieee.org/document/9133505)|Pengpeng Zhao( Soochow University),Anjing Luo,Yanchi Liu,Jiajie Xu,Zhixu Li,Fuzhen Zhuang|None|2022|TKDE|**Foursquare(CA):**<br>Acc@1=0.0890,<br>Acc@5=0.1421,<br>Acc@10=0.1748,<br>MAP=0.2736.<br>**Foursquare(SIN):**<br>Acc@1=0.2284,<br>Acc@5=0.2768,<br>Acc@10=0.3022,<br>MAP=0.3704.<br>**Gowalla:**<br>Acc@1=0.0930,<br>Acc@5=0.1689,<br>Acc@10=0.2034,<br>MAP=0.2685.<br>**Brightkite:**<br>Acc@1=0.4567,<br>Acc@5=0.5109,<br>Acc@10=0.5422,<br>MAP=0.5683.|
Personalized Long- and Short-term Preference Learning for Next POI Recommendation(PLSPL)([paper](https://ieeexplore.ieee.org/document/9117156))|Yuxia Wu(Xi’an Jiaotong University),KeLI,Guoshuai Zhao,Xueming Qian | None | 2022 |TKDE|**Foursquare(NYC):**<br>Recall@1=0.1559,<br>Recall@5=0.3252,<br>Recall@10=0.3953,<br>Recall@20=0.4475,<br>MAP@5=0.2172,<br>MAP@10=0.2266,<br>MAP@20=0.2302.<br>**Foursquare(TKY):**<br>Recall@1=0.1571,<br>Recall@5=0.3321,<br>Recall@10=0.4020,<br>Recall@20=0.4664,<br>MAP@5=0.2212,<br>MAP@10=0.2307,<br>MAP@20=0.2352.|
Time-Aware Location Prediction by Convolutional Area-of-Interest Modeling and Memory-Augmented Attentive LSTM(t-LocPred)([paper](https://ieeexplore.ieee.org/document/9128016))|Chi Harold Liu(Beijing Institute of Technology),Yu Wang,Chengzhe Piao,Zipeng Dai, Ye Yuan,Guoren Wang, and Dapeng Wu|None|2022|TKDE|**Weeplaces:**<br>Acc@1=0.277.<br>**Gowalla:**<br>Acc@1=0.247.<br>**Brightkite:**<br>Acc@1=0.380.|
SPATM: A Social Period-Aware T opic Model for Personalized Venue Recommendation(SPATM)([paper](https://ieeexplore.ieee.org/document/9214846))|Weiyu Ji(Beijing University of Posts and Tele-communications),Xiangwu Meng,Yujie Zhang|None|2022|TKDE|**Foursquare:**<br>Recall@1=0.0683,<br>Recall@5=0.157,<br>Recall@10=0.222,<br>Recall@15=0.273,<br>NDCG@1=0.0683,<br>NDCG@5=0.0374,<br>NDCG@10=0.0297,<br>NDCG@15=0.0255.<br>**Yelp:**<br>Recall@1=0.0243,<br>Recall@5=0.0918,<br>Recall@10=0.161,<br>Recall@15=0.2432,<br>NDCG@1=0.0243,<br>NDCG@5=0.0196,<br>NDCG@10=0.0173,<br>NDCG@15=0.0168.|
Learning Graph-based Disentangled Representations for Next POI Recommendation(DRAN)([paper](https://dl.acm.org/doi/abs/10.1145/3477495.3532012))|Zhaobo Wang(Shanghai Jiao Tong University),Yanmin Zhu∗,Haobing Liu,Chunyang Wang|None|2022|sigir|**Foursquare:**<br>Recall@2=0.3551,<br>Recall@5=0.4092,<br>Recall@10=0.4512.<br>**Gowalla:**<br>Recall@2=0.2288,<br>Recall@5=0.2832,<br>Recall@10=0.3291.|
GETNext: Trajectory Flow Map Enhanced Transformer for Next POI Recommendation(GETNext)([paper](https://dl.acm.org/doi/abs/10.1145/3477495.3531983))|Song Yang(The University of Auckland),Jiamou Liu,Kaiqi Zhao|[code](https://github.com/songyangco/GETNext)|2022|sigir|**FourSquare(NYC):**<br>Acc@1=0.2435,<br>Acc@5=0.5089,<br>Acc@10=0.6143,<br>Acc@20=0.6880,<br>MRR=0.3621.<br>**FourSquare(TKY):**<br>Acc@1=0.2254,<br>Acc@5=0.4417,<br>Acc@10=0.5287,<br>Acc@20=0.5829,<br>MRR=0.3262.<br>**Gowalla(CA):**<br>Acc@1=0.1357,<br>Acc@5=0.2852,<br>Acc@10=0.3590,<br>Acc@20=0.4241,<br>MRR=0.2103.|
Empowering Next POI Recommendation with Multi-Relational Modeling(MEMO)([paper](https://arxiv.org/abs/2204.12288))|Zheng Huang(University of Virginia), Jing Ma,Yushun Dong,Natasha Zhang Foutz,Jundong Li|None|2022|sigir|**Baltimore July:**<br>Recall@10=0.891,<br>MRR@10=0.446.<br>**DC July:**<br>Recall@10=0.831,<br>MRR@10=0.380.<br>**DC August:**<br>Recall@10=0.840,<br>MRR@10=0.435.|
Next Point-of-Interest Recommendation with Auto-Correlation Enhanced Multi-Modal Transformer Network([paper](https://dl.acm.org/doi/abs/10.1145/3477495.3531905))|Yanjun Qin(Beijing University of Posts and Telecommunications),Yuchen Fang,Haiyong Luo, Fang Zhao,Chenxing Wang|None|2022|sigir|**NYC:**<br>Acc@5=0.4370,<br>Acc@10=0.5289,<br>MRR@5=0.2742,<br>MRR@10=0.2867.<br>**TKY:**<br>Acc@5=0.3802,<br>Acc@10=0.4687,<br>MRR@5=0.2434,<br>MRR@10=0.2553|
Predicting Human Mobility via Graph Convolutional Dual-attentive Networks(GCDAN)([paper](https://dl.acm.org/doi/abs/10.1145/3488560.3498400))|Weizhen Dang(Tsinghua University),Haibo Wang, Shirui Pan,Pei Zhang, Chuan Zhou,Xin Chen,Jilong Wang|[code](https://github.com/GCDAN/GCDAN)|2022|wsdm|**Gowalla:**<br>Acc@1=0.1377,<br>Acc@5=0.3086,<br>Acc@10=0.3780.<br>**Foursquare:**<br>Acc@1=0.1613,<br>Acc@5=0.3417,<br>Acc@10=0.4093.<br>**WiFi-Trace:**<br>Acc@1=0.5912,<br>Acc@5=0.8064,<br>Acc@10=0.8726.|
RLMob: Deep Reinforcement Learning for Successive Mobility Prediction(RLMob)([paper](https://dl.acm.org/doi/abs/10.1145/3488560.3498438))|Ziyan Luo(McGill University),Congcong Miao|[code](https://github.com/SunsetRay/RLMob)|2022|wsdm|**Foursquare(TKY):**<br>Acc@1=0.4150.<br>**Foursquare(NYK):**<br>Acc@1=0.4401.<br>**Univ-WIFI:**<br>Acc@1=0.2291.|
