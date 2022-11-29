# AACL-IJCNLP2022_Efficient_Robust_KGC_Tutorial

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

Materials for [AACL2022](https://www.aacl2022.org/Program/tutorials) tutorial: Efficient and Robust Knowledge Graph Construction


## Tutorial abstract [\[PDF\]](/files/tutorial.pdf)

Knowledge graph construction which aims to extract knowledge from the text corpus has appealed to the NLP community researchers. Previous decades have witnessed the remarkable progress of knowledge graph construction on the basis of neural models; however,  those models often cost massive computation or labeled data resources and suffer from unstable inference accounting for biased or adversarial samples. Recently, numerous approaches have been explored to mitigate the efficiency and robustness issues for knowledge graph construction, such as prompt learning and adversarial training. In this tutorial, we aim at bringing interested NLP researchers up to speed about the recent and ongoing techniques for efficient and robust knowledge graph construction. Additionally, our goal is to provide a systematic and up-to-date overview of these methods and reveal new research opportunities to the audience.


#### If you find this tutorial helpful for your work, please kindly cite our paper.

```
@inproceedings{zhang-etal-2022-efficient-robust,
    title = "Efficient and Robust Knowledge Graph Construction",
    author = "Zhang, Ningyu  and
      Gui, Tao  and
      Nan, Guoshun",
    booktitle = "Proceedings of the 2nd Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics and the 12th International Joint Conference on Natural Language Processing: Tutorial Abstracts",
    month = nov,
    year = "2022",
    address = "Taipei",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.aacl-tutorials.1",
    pages = "1--7",
    abstract = "Knowledge graph construction which aims to extract knowledge from the text corpus, has appealed to the NLP community researchers. Previous decades have witnessed the remarkable progress of knowledge graph construction on the basis of neural models; however, those models often cost massive computation or labeled data resources and suffer from unstable inference accounting for biased or adversarial samples. Recently, numerous approaches have been explored to mitigate the efficiency and robustness issues for knowledge graph construction, such as prompt learning and adversarial training. In this tutorial, we aim to bring interested NLP researchers up to speed on the recent and ongoing techniques for efficient and robust knowledge graph construction. Additionally, our goal is to provide a systematic and up-to-date overview of these methods and reveal new research opportunities to the audience.",
}
```
## Tutorial Materials

**1. Slides** [\[Introduction\]](/files/PART1_Introduction.pdf) [\[EfficientKGC\]](/files/PART2_Efficient_KGC.pdf) [\[RobustKGC\]](/files/PART3_Robust_KGC.pdf) [\[Conclusion\]](/files/PART4_Conclusion.pdf)

**2. Video** [\[AllParts\]](https://underline.io/events/373/sessions?eventSessionId=13783)

**3. Related Tutorials:**

- New Frontiers of Information Extraction. NAACL 2022 Tutorial \[[ppt](https://cogcomp.seas.upenn.edu/page/tutorial.202207/)\] 
- Less Data, More ___? Data Augmentation and Semi-Supervised Learning for Natural Language Processing. ACL 2022 Tutorial  \[[ppt](https://github.com/diyiy/ACL2022_Limited_Data_Learning_Tutorial)\] 
- Zero- and Few-Shot NLP with Pretrained Language Models. AACL 2022 Tutorial  \[[ppt](https://github.com/allenai/acl2022-zerofewshot-tutorial)\] 
- Data-Efficient Knowledge Graph Construction. CCKS2022 Tutorial  \[[ppt](https://drive.google.com/drive/folders/1xqeREw3dSiw-Y1rxLDx77r0hGUvHnuuE)\] 
- Knowledge Informed Prompt Learning. MLNLP 2022 Tutorial (Chinese) \[[ppt](https://person.zju.edu.cn/person/attachments/2022-11/01-1668830598-859129.pdf)\] 

**4. Survey:** 

*Knowledge Graph Construction*
* A Survey on Deep Learning for Named Entity Recognition (TKDE, 2022) \[[paper](https://ieeexplore.ieee.org/abstract/document/9039685)\]
* A Survey on Recent Advances in Named Entity Recognition from Deep Learning Models (COLING 2018) \[[paper](https://aclanthology.org/C18-1182.pdf)\]
* A Survey on Neural Relation Extraction (Science China Technological Sciences, 2020) \[[paper](https://link.springer.com/article/10.1007/s11431-020-1673-6)\]
* What is Event Knowledge Graph: A Survey (TKDE, 2022) \[[paper](https://arxiv.org/abs/2112.15280)\]
* Knowledge Extraction in Low-Resource Scenarios: Survey and Perspective (on arxiv, 2022) \[[paper](https://arxiv.org/abs/2202.08063)\]
* Generative Knowledge Graph Construction: A Review (EMNLP, 2022) \[[paper](https://arxiv.org/pdf/2210.12714.pdf)\]

*Efficient NLP*
* A Survey on Recent Approaches for Natural Language Processing in Low-Resource Scenarios (NAACL 2021) \[[paper](https://aclanthology.org/2021.naacl-main.201.pdf)\]
* Few-Shot Named Entity Recognition: An Empirical Baseline Study (EMNLP 2021) \[[paper](https://aclanthology.org/2021.emnlp-main.813.pdf)\]
* A Survey on Low-Resource Neural Machine Translation (IJCAI 2021) \[[paper](https://www.ijcai.org/proceedings/2021/0629.pdf)\]
* Efficient Methods for Natural Language Processing: A Survey (on arxiv 2022) \[[paper](https://arxiv.org/pdf/2209.00099.pdf)\]
* Delta Tuning: A Comprehensive Study of Parameter Efficient Methods for Pre-trained Language Models  (on arxiv 2021) \[[paper](https://arxiv.org/abs/2203.06904)\]
* Pre-train, Prompt, and Predict: A Systematic Survey of Prompting Methods in Natural Language Processing  (ACM Computing Surveys 2021) \[[paper](https://arxiv.org/abs/2107.13586)\]

*Low-resource Learning*
* Generalizing from a Few Examples: A Survey on Few-shot Learning (ACM Computing Surveys, 2021) \[[paper](https://dl.acm.org/doi/10.1145/3386252)\]
* Knowledge-aware Zero-Shot Learning: Survey and Perspective (IJCAI 2021) \[[paper](https://www.ijcai.org/proceedings/2021/0597.pdf)\]
* Low-resource Learning with Knowledge Graphs: A Comprehensive Survey (2021) \[[paper](https://arxiv.org/abs/2112.10006)\]


**5. Reading list:**

- Template-free prompt tuning for few-shot NER, in NAACL 2022. [\[pdf\]](https://arxiv.org/abs/2109.13532)
- Reasoning with Latent Structure Refinement for Document-Level Relation Extraction, in ACL 2020. [\[pdf\]](https://arxiv.org/abs/2005.06312)
- Making Pre-trained Language Models Better Few-shot Learners, in ACL 2022. [\[pdf\]](https://aclanthology.org/2021.acl-long.295/)
- PTR: Prompt Tuning with Rules for Text Classification, in Arxiv 2021. [\[pdf\]](https://arxiv.org/pdf/2105.11259.pdf)
- Label Verbalization and Entailment for Effective Zero- and Few-Shot Relation Extraction, in EMNLP 2021. [\[pdf\]](https://aclanthology.org/2021.emnlp-main.92.pdf)
- RelationPrompt: Leveraging Prompts to Generate Synthetic Data for Zero-Shot Relation Triplet Extraction, in EMNLP 2022 (Findings). [\[pdf\]](https://arxiv.org/abs/2203.09101)
- KnowPrompt: Knowledge-aware Prompt-tuning with Synergistic Optimization for Relation Extraction, in WWW 2022. [\[pdf\]](https://arxiv.org/abs/2104.07650)
- Towards Realistic Low-resource Relation Extraction: A Benchmark with Empirical Baseline Study, in EMNLP 2022 (Findings). [\[pdf\]](https://arxiv.org/pdf/2210.10678.pdf)
- Decoupling Knowledge from Memorization: Retrieval-augmented Prompt Learning, in NeurIPS 2022. [\[pdf\]](https://arxiv.org/abs/2205.14704)
- AliCG: Fine-grained and Evolvable Conceptual Graph Construction for Semantic Search at Alibaba, in KDD 2021. [\[pdf\]](https://arxiv.org/pdf/2106.01686.pdf)
- Relation Extraction as Open-book Examination: Retrieval-enhanced Prompt Tuning, in SIGIR 2022. [\[pdf\]](https://arxiv.org/abs/2205.02355)
- LightNER: A Lightweight Tuning Paradigm for Low-resource NER via Pluggable Prompting, in COLING 2022. [\[pdf\]](https://aclanthology.org/2022.coling-1.209/)
- PALT: Parameter-Lite Transfer of Language Models for Knowledge Graph Completion, in EMNLP 2022. [\[pdf\]](https://arxiv.org/abs/2210.13715)
- Unified Structure Generation for Universal Information Extraction, in ACL 2022. [\[pdf\]](https://aclanthology.org/2022.acl-long.395/)
- LasUIE: Unifying Information Extraction with Latent Adaptive Structure-aware Generative Language Model, in NeurIPS 2022. [\[pdf\]](https://openreview.net/forum?id=a8qX5RG36jd) 
- Sequence-to-Sequence Knowledge Graph Completion and Question Answering, in ACL 2022. [\[pdf\]](https://arxiv.org/abs/2203.10321) 
- From Discrimination to Generation: Knowledge Graph Completion with Generative Transformer, in WWW 2022 (Poster) [\[pdf\]](https://arxiv.org/abs/2202.02113)
- Generative Knowledge Graph Construction: A Review, in EMNLP 2022. [\[pdf\]](https://arxiv.org/pdf/2210.12714.pdf) 
- FastRE: Towards Fast Relation Extraction with Convolutional Encoder and Improved Cascade Binary Tagging Framework, in IJCAI 2022.  [\[pdf\]](https://www.ijcai.org/proceedings/2022/0583.pdf)
- Long-tail relation extraction via knowledge graph embeddings and graph convolution networks, in NAACL 2019. [\[pdf\]](https://arxiv.org/abs/2205.14704)
- Document-level Relation Extraction as Semantic Segmentation, in IJCAI 2021. [\[pdf\]](https://arxiv.org/abs/2205.14704)
- Hybrid Transformer with Multi-level Fusion for Multimodal Knowledge Graph Completion, in SIGIR 2022. [\[pdf\]](https://arxiv.org/pdf/2205.02357.pdf)
- Good Visual Guidance Makes A Better Extractor: Hierarchical Visual Prefix for Multimodal Entity and Relation Extraction, in NAACL 2022 (Findings). [\[pdf\]](https://arxiv.org/pdf/2205.03521.pdf)
- Neuralizing Regular Expressions for Slot Filling, in EMNLP 2021.  [\[pdf\]](https://aclanthology.org/2021.emnlp-main.747/)   
- Event Extraction as Machine Reading Comprehension, in EMNLP 2020. [\[pdf\]](https://aclanthology.org/2020.emnlp-main.128/)  
- RESIN: A Dockerized Schema-Guided Cross-document Cross-lingual Cross-media Information Extraction and Event Tracking System, in NAACL 2021 (demo). [\[pdf\]](https://aclanthology.org/2021.naacl-demos.16/)  
- TextFlint: Unified Multilingual Robustness Evaluation Toolkit for Natural Language Processing, in ACL 2021.  [\[pdf\]](https://aclanthology.org/2021.acl-demo.41/)
- DeepKE: A Deep Learning Based Knowledge Extraction Toolkit for Knowledge Base Population, in EMNLP 2022 (Demo). [\[pdf\]](https://arxiv.org/abs/2201.03335)
- OpenNRE: An Open and Extensible Toolkit for Neural Relation Extraction, in EMNLP 2019 (demo). [\[pdf\]](https://aclanthology.org/D19-3029/)
- OpenPrompt: An Open-source Framework for Prompt-learning, in ACL 2021 (demo). [\[pdf\]](https://aclanthology.org/2022.acl-demo.10/)
- ZS4IE: A toolkit for Zero-Shot Information Extraction with simple Verbalizations, in NAACL 2022 (demo). [\[pdf\]](https://aclanthology.org/2022.naacl-demo.4.pdf)

## Tutorial schedule

| Local time (GMT) | Content | Presenter | Slides |
| :---: | :---: | :---: | :---: |
| 09:00-10:00 | Introduction and Applications | Guoshun Nan | [\[Slides\]](/files/PART1_Introduction.pdf) |
| 10:00-11:00 | Efficient Knowledge Graph Construction | Ningyu Zhang | [\[Slides\]](/files/PART2_Efficient_KGC.pdf) |
| 11:00-11:50 | Robust Knowledge Graph Construction | Tao Gui | [\[Slides\]](/files/PART3_Robust_KGC.pdf) |
| 11:50-12:00 |Summary | Ningyu Zhang | [\[Slides\]](/files/PART4_Conclusion.pdf) |


## Presenters

## &nbsp; <img src="imgs/ningyu.jpg" width="120" height = "150" align=center> &nbsp; <img src="imgs/guitao.jpg" width="120" height = "150" align=center> &nbsp;  <img src="imgs/guoshun.jpg" width="120" height = "150" align=center> 

Ningyu Zhang &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Tao Gui &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Guoshun Nan

**[Ningyu Zhang](https://person.zju.edu.cn/en/ningyu)** is an associate professor at Zhejiang University, his main research interests are knowledge graph, NLP, etc. He has published  papers in top international academic conferences and journals such as NeurIPS/ICLR/WWW/KDD/WSDM/AAAI/IJCAI/ACL/ENNLP/NAACL/COLING/SIGIR/TASLP/ESWA/KBS/Journal of Software/Nature Communications. Three paper has been selected as Paper Digest Most Influential Papers (**KnowPrompt**'WWW22、**DocuNet**'IJCAI21、**AliCG**'KDD21). He has served as a PC for NeurIPS/ICLR/ICML/KDD/AAAI/IJCAI/ACL/EMNLP/NAACL, and reviewer of TKDE/WWWJ/JWS/TALLIP/IEEE Transactions on Cybernetics/ESWA.

**[Tao Gui](https://guitaowufeng.github.io)** is an associate professor in Institute of Modern Languages and Linguistics of Fudan University. He is the key member of FudanNLP group. He is a member of ACL, a member of the Youth Working Committee of the Chinese Information Processing Society of China, the member of the Language and Knowledge Computing Professional Committee of the Chinese Information Processing Society of China. He has published more than 30 papers in top international academic conferences and journals such as ACL, ENNLP, AAAI, IJCAI, SIGIR, and so on. He has served as Editor-in-Chief of the NLPR Information Extraction Special Issue, PCs for SIGIR, AAAI, IJCAI, and reviewer for TPAMI and ARR. He has received the Outstanding Doctoral Dissertation Award of the Chinese Information Processing Society of China, the area chair favorite Award of COLING 2018, the outstanding Paper Award of NLPCC 2019, and scholar of young talent promoting project of CAST. 


**[Guoshun Nan]()** is a tenure-track professor in School of Cyber Science and Engineering, Beijing University of Posts and Telecommunications (BUPT). He is the key member of National Engineering Research Center of Mobile Network Security, and a member of Wireless Technology Innovation Institute of BUPT. Before starting academic career, he also worked in Hewlett-Packard Company (China) for more than 4 years as an engineer. He is a member of ACL. His has broad interest in information extraction, model robustness, multimodal retrieval, cyber security and the next generation wireless networks. He has published more than 10 papers in top-tier conferences such as ACL, CVPR, EMNLP, SIGIR, IJCAI, CKIM and Sigcomm. He served as a reviewer for ACL, EMNLP, AAAI, IJCAI, Neurocomputing and IEEE Transaction on Image Processing. 


