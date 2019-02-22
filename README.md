# QE-reading-list
A brief list about quality estimation in machine translation maintained by Jinliang Lu
*  [Word Level QE](#word_level_quality_estimation)
    * [Traditional method](#word_traditional_method)
    * [Nerual method](#word_neural_method)
*  [Phrase Level QE](#phrase_level_qualtiy_estimation)
    * [Traditional method](#phrase_traditional_method)
    * [Nerual method](#phrase_neural_method)
*  [Sentence Level QE](#sentence_level_quality_estimation)
    * [Traditional method](#sentence_traditional_method)
    * [Neural aware method](#sentence_neural_aware_method)
    * [Pure neural method](#sentence_pure_neural_method)
*  [Document Level QE](#document_level_quality_estimation)
    * [Traditional method](#document_traditional_method)
    * [Nerual method](#document_neural_method)

<h2 id="word_level_quality_estimation">Word Level Quality Estimation</h2>
<h3 id="word_traditional_method">Traditional QE Method</h3>

* Lucia Specia, Gustavo Henrique Paetzold and Carolina Scarton. 2015. [Multi-level Translation Quality Prediction with QUEST++](http://www.aclweb.org/anthology/P15-4020). *In Proceedings of ACL-IJCNLP 2015 System Demonstrations.*
<h3 id="word_neural_method">Neural QE Method</h3>

* Hyun Kim, Jong-Hyeok Lee. 2016. [Recurrent Neural Network based Translation Quality Estimation](http://www.aclweb.org/anthology/W16-2384). *In Proceedings of the First Conference on Machine Translation, Volume 2: Shared Task Papers, pages 787–792.*

* André F. T. Martins, Fabio Kepler, José L. Monteiro. 2017. [Unbabel’s Participation in the WMT17 Translation Quality Estimation Shared Task](http://www.aclweb.org/anthology/W17-4764). *In Proceedings of the Conference on Machine Translation (WMT), Volume 2: Shared Task Papers, pages 569–574.*
* André F. T. Martins, Marcin Junczys-Dowmunt, Fabio Kepler, Ramon Astudillo, Chris Hokamp, and Roman Grundkiewicz. 2017. [Pushing the limits of translation quality estimation](https://www.transacl.org/ojs/index.php/tacl/article/download/1113/237). *Transactions of the Association for Computational Linguistics, vol. 5, pp. 205–218, 2017..*
* Miquel Esplà-Gomis, Felipe Sánchez-Martínez, Mikel L. Forcada. [UAlacant machine translation quality estimation at WMT 2018: a simple approach using phrase tables and feed-forward neural networks](http://www.aclweb.org/anthology/W18-6464). *In Proceedings of the Third Conference on Machine Translation (WMT), Volume 2: Shared Task Papers, pages 801–808*
* Jiayi Wang, Kai Fan, Bo Li, Fengming Zhou, Boxing Chen, Yangbin Shi, Luo Si. 2018. [Alibaba Submission for WMT18 Quality Estimation Task](http://www.statmt.org/wmt18/pdf/WMT093.pdf). *In Proceedings of the Third Conference on Machine Translation (WMT), Volume 2: Shared Task Papers, pages 822–828.*
* Kai Fan, Jiayi Wang, Bo Li, Fengming Zhou, Boxing Chen, Luo Si. 2019. ["Bilingual Expert" Can Find Translation Errors](https://arxiv.org/pdf/1807.09433.pdf). *In Proceedings of The Thirty-Third AAAI Conference on Artificial Intelligence (AAAI-19).*

<h2 id="phrase_level_qualtiy_estimation">Phrase Level Quality Estimation</h2>
<h3 id="phrase_traditional_method">Traditional QE method</h3>

* Lucia Specia, Gustavo Henrique Paetzold and Carolina Scarton. 2015. [Multi-level Translation Quality Prediction with QUEST++](http://www.aclweb.org/anthology/P15-4020). *In Proceedings of ACL-IJCNLP 2015 System Demonstrations.*

<h3 id="phrase_neural_method">Neural QE Method</h3>

* Hyun Kim, Jong-Hyeok Lee. 2016. [Recurrent Neural Network based Translation Quality Estimation](http://www.aclweb.org/anthology/W16-2384). *In Proceedings of the First Conference on Machine Translation, Volume 2: Shared Task Papers, pages 787–792.*

<h2 id="sentence_level_quality_estimation">Sentence Level Quality Estimation</h2>

<h3 id="sentence_traditional_method">Traditional QE Method</h3>


* Lucia Specia, Kashif Shah, Jose G.C.de Souza and Trevor Cohn. 2013. [QuEst - A translation quality estimation framework](http://www.aclweb.org/anthology/P13-4014). *In Proceedings of the 51st Annual Meeting of the Association for Computational Linguistics.   2013.* 
* Lucia Specia, Gustavo Henrique Paetzold and Carolina Scarton. 2015. [Multi-level Translation Quality Prediction with QUEST++](http://www.aclweb.org/anthology/P15-4020). *In Proceedings of ACL-IJCNLP 2015 System Demonstrations.*
  *   `This two methods which have been famous were used as the baseline of WMT-QE`

* Ergun Biçici, Declan Groves, and Josef van Genabith. 2013. [Predicting sentence translation quality using extrinsic and language independent features](https://cyberleninka.org/article/n/959597.pdf). *Machine Translation, 27:171–192, December.*
* Ergun Biçici and Andy Way. 2014. [Referential translation machines for predicting translation quality.](http://doras.dcu.ie/19990/1/RTMforQE.pdf) *In Proceedings of the Ninth Workshop on Statistical Machine Translation, pages 313–321, Baltimore, Maryland, USA, June.*
* Ergun Biçici, Qun Liu, Andy Way. 2015. [Referential Translation Machines for Predicting Translation Quality and Related Statistics](http://www.aclweb.org/anthology/W15-3035). *In Proceedings of the Tenth Workshop on Statistical Machine Translation, pages 304–308.*
  *   `These methods add the tree-structure features into QE model and the articles above are not the full list of the series.`

* André F. T. Martins, Marcin Junczys-Dowmunt, Fabio Kepler, Ramon Astudillo, Chris Hokamp, and Roman Grundkiewicz. 2017. [Pushing the limits of translation quality estimation](https://www.transacl.org/ojs/index.php/tacl/article/download/1113/237). *Transactions of the Association for Computational Linguistics, vol. 5, pp. 205–218, 2017.*
  *   `Even thouth the method use neural network for word-level QE, it converts the result to sentence-level in traditonal way`
* Melania Duma and Wolfgang Menzel. [The Benefit of Pseudo-Reference Translations in Quality Estimation of MT Output](http://aclweb.org/anthology/W18-6460). *In Proceedings of the Third Conference on Machine Translation (WMT), Volume 2: Shared Task Papers, pages 776–781.*
* Thierry Etchegoyhen and Eva Martínez Garcia and Andoni Azpeitia. 2018. [Supervised and Unsupervised Minimalist Quality Estimators: Vicomtech’s Participation in the WMT 2018 Quality Estimation Task](http://aclweb.org/anthology/W18-6461). *Proceedings of the Third Conference on Machine Translation (WMT), Volume 2: Shared Task Papers, pages 782–787.* 


<h3 id="sentence_neural_aware_method">Neural Aware QE Method</h3>

* Kashif Shah, Raymond W. M. Ng, Fethi Bougares, Lucia Specia. 2015. [Investigating Continuous Space Language Models for Machine
Translation Quality Estimation](http://www.aclweb.org/anthology/D15-1125). *In Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing.*
* Zhiming Chen, Yiming Tan, Chenlin Zhang, Qingyu Xiang, Lilin Zhang, Maoxi Li, Mingwen Wang. 2016. [Improving Machine Translation Quality Estimation with Neural Network Features](http://www.aclweb.org/anthology/W17-4761). *In Proceedings of the Conference on Machine Translation (WMT), Volume 2: Shared Task Papers, pages 551–555.*

<h3 id="sentence_pure_neural_method">Pure Neural QE Method</h3>

* Hyun Kim, Jong-Hyeok Lee. 2016. [A Recurrent Neural Networks Approach for Estimating the Quality of Machine Translation Output](http://www.aclweb.org/anthology/N16-1059). *In Proceedings of NAACL-HLT 2016.*
* Hyun Kim, Jong-Hyeok Lee. 2016. [Recurrent Neural Network based Translation Quality Estimation](http://www.aclweb.org/anthology/W16-2384). *In Proceedings of the First Conference on Machine Translation, Volume 2: Shared Task Papers, pages 787–792.*
* Hyun Kim, Hun-Young Jung, Hongseok Kwon, Jong-Hyeok Lee, and Seung-Hoon Na. 2017a. [Predictor-Estimator: Neural quality estimation based on target word prediction for machine translation](https://dl.acm.org/citation.cfm?id=3109480). *ACM Transactions on Asian and Low-Resource Language Information Processing, 17(1):3:1–3:22, September.*
* Hyun Kim, Jong-Hyeok Lee, and Seung-Hoon Na. 2017b. [Predictor-estimator using multilevel task learning with stack propagation for neural quality estimation](http://www.statmt.org/wmt17/pdf/WMT63.pdf). *In Proceedings of the Second Conference on Machine Translation (WMT), pages 562–568, September.*
* Julia Ive, Frédéric Blain, Lucia Specia. 2018. [deepQuest: A Framework for Neural-based Quality Estimation](http://aclweb.org/anthology/C18-1266). *In Proceedings of the 27th International Conference on Computational Linguistics, pages 3146–315.*
* Maoxi Li, Qingyu Xiang, Zhiming Chen and Mingwen Wang. 2018. [A Unified Neural Network for Quality Estimation of Machine Translation](https://www.jstage.jst.go.jp/article/transinf/E101.D/9/E101.D_2018EDL8019/_pdf/-char/en). *IEICE TRANS. INF. & SYST., VOL.E101–D, NO.9 SEPTEMBER 2018.*
* Kai Fan, Jiayi Wang, Bo Li, Fengming Zhou, Boxing Chen, Luo Si. 2019. ["Bilingual Expert" Can Find Translation Errors](https://arxiv.org/pdf/1807.09433.pdf). *In Proceedings of The Thirty-Third AAAI Conference on Artificial Intelligence (AAAI-19).*

<h2 id="document_level_quality_estimation">Document Level Quality Estimation</h2>
<h3 id="document_traditional_method">Traditional QE method</h3>

* Lucia Specia, Gustavo Henrique Paetzold and Carolina Scarton. 2015. [Multi-level Translation Quality Prediction with QUEST++](http://www.aclweb.org/anthology/P15-4020). *In Proceedings of ACL-IJCNLP 2015 System Demonstrations.*

<h3 id="document_neural_method">Neural QE Method</h3>

* Julia Ive, Frédéric Blain, Lucia Specia. 2018. [deepQuest: A Framework for Neural-based Quality Estimation](http://aclweb.org/anthology/C18-1266). *In Proceedings of the 27th International Conference on Computational Linguistics, pages 3146–315.*
