# Selected Summarization Papers in NAACL 2021

[1] [A New Approach to Overgenerating and Scoring Abstractive Summaries](https://www.aclweb.org/anthology/2021.naacl-main.110/) *Kaiqiang Song, Bingqing Wang, Zhe Feng, Fei Liu* 

>  This paper proposed two stage methods (over-generate and select) with a series of methods to control the generation of abstractive summary: 1) a confidence-driven generator with given length which is beyond left-to-right order. 2) a position-aware beam search algorithm; 3) select with overall quality measure model; 4) select with suitable length reward function.

[2] [Attention Head Masking for Inference Time Content Selection in Abstractive Summarization](https://www.aclweb.org/anthology/2021.naacl-main.397/) *Shuyang Cao, Lu Wang* [[code]](https://github.com/ShuyangCao/inference_head_masking)

> This paper proposed a head mask method to select salient information from the encoder. The mask is generated by a fine-tuned RoBERTa model. 

[3] [Inference Time Style Control for Summarization](https://www.aclweb.org/anthology/2021.naacl-main.476/) *Shuyang Cao, Lu Wang* 

[4] [Annotating and Modeling Fine-grained Factuality in Summarization](https://www.aclweb.org/anthology/2021.naacl-main.114/)](https://www.aclweb.org/anthology/2020.findings-emnlp.322.pdf) *Tanya Goyal, Greg Durrett* [[code]](https://github.com/tagoyal/factuality-datasets)

> The application of[ Evaluating Factuality in Generation with Dependency-level Entailment (aclweb.org)](https://www.aclweb.org/anthology/2020.findings-emnlp.322.pdf) in Summarization. This paper analyzed the factuality in summarization and applied their DAE model with sentence level factuality model to improve the factuality of the generated summary.

[5] [AdaptSum: Towards Low-Resource Domain Adaptation for Abstractive Summarization](https://www.aclweb.org/anthology/2021.naacl-main.471/) *Tiezheng Yu, Zihan Liu, Pascale Fung* [[code]](https://github.com/TysonYu/AdaptSum)

> This paper highlights the research questions and challenges in the low-resource abstractive summarization task, which we hope will catalyze research in this area.

[6] [Hie-BART: Document Summarization with Hierarchical BART](https://www.aclweb.org/anthology/2021.naacl-srw.20/) *Kazuku Akiyama, Akihiro Tamura, Takashi Ninomiya* 

> This paper adds sentence-level attention into BART encoder layers.

[7] [D2S: Document-to-Slide Generation Via Query-Based Text Summarization](https://www.aclweb.org/anthology/2021.naacl-main.111/) *Edward Sun, Yufang Hou, Dakuo Wang, Yunfeng Zhang, Nancy X.R. Wang*

> This paper contributed a new dataset SciDuet for Slide Generation task with text summarization.

[8] [Efficient Attentions for Long Document Summarization](https://www.aclweb.org/anthology/2021.naacl-main.112.pdf) *Luyang Huang, Shuyang Cao, Nikolaus Parulian, Heng ji, Lu Wang* [[code]](https://github.com/luyang-huang96/LongDocSum)

> This paper proposed an efficient encoder-decoder attention with head-wise positional strides to extract salient information from the source and contributed a new dataset for long document summarization.

[9] [Enriching Transformers with Structured Tensor-Product Representations for Abstractive Summarization](https://www.aclweb.org/anthology/2021.naacl-main.381/) *Yichen Jiang, Asli Celikyilmaz, Paul Smolensky, Paul Soulos, Sudha Rao, Hamid Palangi, Roland Fernandez, Caitlin Smith, Mohit Bansal, Jianfeng Gao* [[code]](https://github.com/jiangycTarheel/TPT-Summ)

[10] [RefSum: Refactoring Neural Summarization](https://www.aclweb.org/anthology/2021.naacl-main.113.pdf) *Yixin Liu, Zi-Yi Dou, Pengfei Liu* [[code]](https://github.com/yixinL7/Refactoring-Summarization)

[11] [Structure-Aware Abstractive Conversation Summarization via Discourse and Action Graphs](https://www.aclweb.org/anthology/2021.naacl-main.109/) *Jiaao Chen, Diyi Yang* [[code]](https://github.com/GT-SALT/Structure-Aware-BART)

[12] [Extending Multi-Document Summarization Evaluation to the Interactive Setting](https://www.aclweb.org/anthology/2021.naacl-main.54/) *Ori Shapira, Ramakanth Pasunuru, Hadar Ronen, Mohit Bansal, Yael Amsterdamer, Ido Dagan*

[13] [Noisy Self-Knowledge Distillation for Text Summarization](https://www.aclweb.org/anthology/2021.naacl-main.56/) *Yang Liu, Sheng Shen, Mirella Lapata*

[14] [Improving Zero and Few-Shot Abstractive Summarization with Intermediate Fine-tuning and Data Augmentation](https://www.aclweb.org/anthology/2021.naacl-main.57/) *Alexander Fabbri, Simeng Han, Haoyuan Li, Haoran Li, Marjan Ghazvininejad, Shafiq Joty, Dragomir Radev, Yashar Mehdad*

[15] [Enhancing Factual Consistency of Abstractive Summarization](https://www.aclweb.org/anthology/2021.naacl-main.58/) *Chenguang Zhu, William Hinthorn, Ruochen Xu, Qingkai Zeng, Michael Zeng, Xuedong Huang, Meng Jiang*

[16] [Looking Beyond Sentence-Level Natural Language Inference for Question Answering and Text Summarization](https://www.aclweb.org/anthology/2021.naacl-main.104/) *Anshuman Mishra, Dhruvesh Patel, Aparna Vijayakumar, Xiang Lorraine Li, Pavan Kapanipathi, Kartik Talamadupula*

[17] [Predicting Discourse Trees from Transformer-based Neural Summarizers](https://www.aclweb.org/anthology/2021.naacl-main.326/) *Wen Xiao, Patrick Huber, Giuseppe Carenini*

[18] [Efficiently Summarizing Text and Graph Encodings of Multi-Document Clusters](https://www.aclweb.org/anthology/2021.naacl-main.380/) *Ramakanth Pasunuru, Mengwen Liu, Mohit Bansal, Sujith Ravi, Markus Dreyer*

[19] [Understanding Factuality in Abstractive Summarization with FRANK: A Benchmark for Factuality Metrics](https://www.aclweb.org/anthology/2021.naacl-main.383/) *Artidoro Pagnoni, Vidhisha Balachandran, Yulia Tsvetkov*

[20] [GSum: A General Framework for Guided Neural Abstractive Summarization](https://www.aclweb.org/anthology/2021.naacl-main.384/) *Zi-Yi Dou, Pengfei Liu, Hiroaki Hayashi, Zhengbao Jiang, Graham Neubig*

[21] [Nutri-bullets Hybrid: Consensual Multi-document Summarization](https://www.aclweb.org/anthology/2021.naacl-main.411/) *Darsh Shah, Lili Yu, Tao Lei, Regina Barzilay*

[22] [Sliding Selector Network with Dynamic Memory for Extractive Summarization of Long Documents](https://www.aclweb.org/anthology/2021.naacl-main.470/) *Peng Cui, Le Hu*

[23] [QMSum: A New Benchmark for Query-based Multi-domain Meeting Summarization](https://www.aclweb.org/anthology/2021.naacl-main.472/) *Ming Zhong, Da Yin, Tao Yu, Ahmad Zaidi, Mutethia Mutuma, Rahul Jha, Ahmed Hassan Awadallah, Asli Celikyilmaz, Yang Liu, Xipeng Qiu, Dragomir Radev*

[24] [MM-AVS: A Full-Scale Dataset for Multi-modal Summarization](https://www.aclweb.org/anthology/2021.naacl-main.473/) *Xiyan Fu, Jun Wang, Zhenglu Yang*

[25] [MediaSum: A Large-scale Media Interview Dataset for Dialogue Summarization](https://www.aclweb.org/anthology/2021.naacl-main.474/) *Chenguang Zhu, Yang Liu, Jie Mei, Michael Zeng*

[26] [Improving Faithfulness in Abstractive Summarization with Contrast Candidate Generation and Selection](https://www.aclweb.org/anthology/2021.naacl-main.475/) *Sihao Chen, Fan Zhang, Kazoo Sone, Dan Roth*
