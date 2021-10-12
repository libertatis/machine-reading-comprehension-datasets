## [Machine Reading Comprehension(MRC) Datasets](#mrc) 


| Dataset（54）                                           | Size(questions) | Data Source                                 | Q/A Source   | LB   | Human Performance  | Sol-ved | TMFW  | PAD  |
| ------------------------------------------------------- | --------------- | ------------------------------------------- | ------------ | ---- | ------------------ | ------- | ----- | ---- |
| **Cloze Datasets（9）**                                 |                 |                                             |              |      |                    |         |       |      |
| CNN/Daily Mail(Hermann et al., 2015)                    | 387K/997K       | CNN/Daily Mail                              | AG           | ★    | -                  | ✗       | -     | ✔    |
| Children BookTest (Hill et al., 2016)                   | 687K            | Project Gutenberg                           | AG           | ★    | 83                 | ✔       | -     | ✔    |
| Who Did What (Onishi et al., 2016)                      | 186K            | Gigaword                                    | AG           | ✔    | 84                 | ✗       | -     | ✉    |
| BookTest (Bajgar et al., 2017)                          | 14M             | Project Gutenberg                           | AG           | ✗    | -                  | ✗       | -     | ✗    |
| Quasar-S (Dhingra et al., 2017)                         | 37K             | Stack Overflow                              | AG           | ✗    | 46.8/50.0          | ✗       | -     | ✔    |
| RecipeQA (Yagcioglu et al., 2018)                       | 9.8K            | instructibles.com                           | AG           | ✔    | 73.6               | ✗       | -     | ✔    |
| CliCR ( ˇ Suster and Daelemans, 2018)                   | 105K            | Clinical Reports                            | AG           | ★    | 53.7/45.1(F1)      | ✗       | -     | ✉    |
| ReCoRD (Zhang et al., 2018a)                            | 121K            | CNN                                         | AG           | ✔★   | 91.3/91.7(F1)      | ✔       | -     | ✔    |
| Shmoop (Chaudhury et al., 2019)                         | 7.2K            | Project Gutenberg                           | ER, AG       | ✗    | -                  | ✗       | -     | ✉    |
| **Multiple Choice Datasets（15）**                      |                 |                                             |              |      |                    |         |       |      |
| MCTest (Richardson et al., 2013)                        | 2k/640          | Stories                                     | CRW          | ✔★   | 95.3               | ✗       | what  | ✔    |
| WikiQA (Yang et al., 2015)                              | 3K              | Wikipedia                                   | UG, CRW      | ★    | -                  | ✗       | what  | ✔    |
| bAbI (Weston et al., 2016)                              | 40K             | AG                                          | AG           | ★    | 100                | ✔       | what  | ✔    |
| MovieQA (Tapaswi et al., 2016)                          | 15K             | Wikipedia                                   | annotators   | ✔    | -                  | ✗       | what  | ✉    |
| RACE (Lai et al., 2017)                                 | 98K             | ER                                          | experts      | ✔★   | 73.3/94.5          | ✗       | what  | ✔    |
| SciQ (Welbl et al., 2017)                               | 12K             | Science Books                               | CRW          | ✗    | 87.8               | ✗       | what  | ✔    |
| MultiRC (Khashabi et al., 2018)                         | 10K             | reports, News,Wikipedia, ...                | CRW          | ✔★   | 81.8(F1)           | ✔       | what  | ✔    |
| MedQA (Zhang et al., 2018b)                             | 235K            | Medical Books                               | expert       | ✗    | -                  | ✔       | -     | ✗    |
| MCScript (Ostermann et al., 2018)                       | 14K             | Scripts, CRW                                | CRW          | ✗    | 98.0               | ✗       | how   | ✔    |
| MCScript2.0 (Ostermann et al., 2019)                    | 20K             | Scripts, CRW                                | CRW          | ✗    | 97.0               | ✗       | what  | ✔    |
| RACE-C (Liang et al., 2019)                             | 14K             | ER                                          | experts      | ✗    | -                  | ✗       | the   | ✔    |
| DREAM(Sun et al., 2019)                                 | 10K             | ER                                          | expers       | ✔    | 98.6               | ✗       | what  | ✔    |
| Cosmos QA (Huang et al., 2019)                          | 36K             | Blogs                                       | CRW          | ✔    | 94                 | ✗       | what  | ✔    |
| ReClor (Yu et al., 2020)                                | 6K              | ER                                          | experts      | ✔    | 63.0               | ✗       | which | ✔    |
| QuAIL (Rogers et al., 2020)                             | 1.5K            | News, Stories, Fiction, <br/>Blogs, UG      | CRW, experts | ✔    | 60.0               | ✗       | -     | ✔    |
| **Boolean Questions（3）**                              |                 |                                             |              |      |                    |         |       |      |
| BoolQ (Clark et al., 2019)                              | 16K             | Wikipedia                                   | UG, CRW      | ✔★   | 89                 | ✔       | is    | ✔    |
| AmazonYesNo (Dzendzik et al., 2019)                     | 80K             | Reviews                                     | UG           | ✗    | -                  | ✗       | does  | ✉    |
| PubMedQA (Jin et al., 2019)                             | 211K            | PubMed                                      | CRW          | ✔    | 78                 | ✗       | does  | ✔    |
| **Extractive Datasets（4）**                            |                 |                                             |              |      |                    |         |       |      |
| SQuAD (Rajpurkar et al., 2016)                          | 108K            | Wikipedia                                   | CRW          | ✔★   | 86.8(F1)           | ✔       | what  | ✔    |
| SQuAD2.0 (Rajpurkar et al., 2018)                       | 151K            | Wikipedia                                   | CRW          | ✔★   | 89.5(F1)           | ✔       | what  | ✔    |
| NewsQA (Trischler et al., 2017)                         | 120K            | CNN                                         | CRW          | ★    | 69.4(F1)           | ✔       | what  | ✔    |
| SearchQA (Dunn et al., 2017)                            | 140K            | CRW, AG                                     | J!Archive    | ★    | 57.6(F1)           | ✔       | this  | ✔    |
| **Generative Datasets（7）**                            |                 |                                             |              |      |                    |         |       |      |
| MS MARCO (Nguyen et al., 2016)                          | 100K            | Web documents                               | UG, HG       | ✔★   | -                  | ✗       | what  | ✔    |
| LAMBADA (Paperno et al., 2016)                          | 10K             | BookCorpus                                  | CRW, AG      | ✗    | -                  | ✗       | -     | ✔    |
| WikiMovies (Miller et al., 2016; Watanabe et al., 2017) | 116K            | Wikipedia, KG                               | CRW, AG, KG  | ✗    | 93.9 (hit@1)       | ✗       | what  | ✔    |
| WikiSuggest (Choi et al., 2017)                         | 3.47M           | Wikipedia                                   | CRW, AG      | ✗    | -                  | ✗       | -     | ✗    |
| TriviaQA (Joshi et al., 2017)                           | 96K             | Wikipedia, Web docs                         | Trivia, CRW  | ✔★   | 79.7/75.4 wiki/web | ✗       | which | ✔    |
| NarrativeQA (Koˇcisk´y et al., 2018)                    | 47K             | Wikipedia, Project Gutenberg,<br/>movie, HG | HG           | ★    | 19.7 BLEU4         | ✔       | what  | ✔    |
| TweetQA (Xiong et al., 2019)                            | 14K             | News, Twitter, HG                           | CRW          | ✔    | 70.0 BLEU1         | ✔       | what  | ✔    |
| **Conversational Datasets（2）**                        |                 |                                             |              |      |                    |         |       |      |
| ShARC (Saeidi et al., 2018)                             | 32K             | Legal web sites                             | CRW          | ✔    | 93.9               | ✗       | can   | ✔    |
| CoQA (Reddy et al., 2019)                               | 127K            | Books, News, Wikipedia,<br/>ER              | CRW          | ✔★   | 88.8               | ✔       | what  | ✔    |
| **Mixed Datasets（14）**                                |                 |                                             |              |      |                    |         |       |      |
| TurkQA (Malon and Bai, 2013)                            | 54K             | Wikipedia                                   | CRW          | ✗    | -                  | ✗       | what  | ✔    |
| WikiReading (Hewlett et al., 2016)                      | 18.9M           | Wikipedia                                   | AG, KG       | ✗    | -                  | ✗       | -     | ✔    |
| Quasar-T (Dhingra et al., 2017)                         | 43K             | Trivia ClueWeb09                            | AG           | ★    | 60.4/60.6 (F1)     | ✗       | what  | ✔    |
| HotpotQA (Yang et al., 2018)                            | 113K            | Wikipedia                                   | CRW          | ✔★   | 96.37(F1)          | ✗       | what  | ✔    |
| QAngaroo WikiHop (Welbl et al., 2018)                   | 51K             | Wikipedia                                   | CRW, KG      | ✔★   | 85.0               | ✗       | -     | ✔    |
| QAngaroo MedHop (Welbl et al., 2018)                    | 2.5K            | Medline abstracts                           | CRW, KG      | ✔    | -                  | ✗       | -     | ✔    |
| QuAC (Choi et al., 2018)                                | 98K             | Wikipedia                                   | CRW          | ✔★   | 81.1(F1)           | ✗       | what  | ✔    |
| DuoRC (Saha et al., 2018)                               | 86K             | Wikipedia + IMDB                            | CRW          | ✔    | -                  | ✗       | who   | ✔    |
| emr QA (Pampari et al., 2018)                           | 456K            | Clinic Records                              | expert, AG   | ✗    | -                  | ✗       | does  | ✉    |
| DROP (Dua et al., 2019)                                 | 97K             | Wikipedia                                   | CRW          | ✔    | 96.4(F1)           | ✗       | how   | ✔    |
| NaturalQuestions (Kwiatkowski et al., 2019)             | 323K            | Wikipedia                                   | UG, CRW      | ✔★   | 87/76 L/S(F1)      | ✗       | who   | ✔    |
| AmazonQA (Gupta et al., 2019b)                          | 570K            | UG Review                                   | UG           | ✗    | 53.5               | ✗       | does  | ✔    |
| TyDi (Clark et al., 2020)                               | 11K             | Wikipedia                                   | CRW          | ✔    | 54.4(F1)           | ✗       | what  | ✔    |
| $R^3$ (Wang et al., 2020b)                              | 60K             | Wikipedia                                   | CRW          | ✗    | -                  | ✗       | -     | ✗    |

| 缩写              | 说明                                                         |
| ----------------- | ------------------------------------------------------------ |
| LB                | leader board available                                       |
| Human Performance | (expert/non-expert if other not specified): accuracy if other is not specified |
| TMFW              | the most frequent first word                                 |
| PAD               | publicly available data                                      |
| K/M               | thousands/millions                                           |
| CRW               | crowdsourcing                                                |
| AG                | automatically generated                                      |
| KG                | knowledge graph                                              |
| ER                | educational resources                                        |
| UG                | user generated                                               |
| HG                | human generated (UG + annotators, crw, experts)              |
| L/S               | long/short answer                                            |
| ✔                 | available/“solved”                                           |
| ✗                 | unavailable/not “solved”                                     |
| ★                 | the leader board is presented at https://paperswithcode.com/ |
| ✉                 | the dataset is available by request                          |

注：The information is verified in June 2020.


## [2013](#2013)
* 1/1 [MCTest](#MCTest)
  * MCTest: A Challenge Dataset for the Open-Domain Machine Comprehension of Text [paper](https://mattr1.github.io/mctest/MCTest_EMNLP2013.pdf) or [here](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/MCTest_EMNLP2013.pdf) or [here](http://aclweb.org/anthology/D13-1020), [dataset](https://mattr1.github.io/mctest/data.html), [homepage](https://mattr1.github.io/mctest/index.html)


## [2014](#2014)
* 2/1 [ProcessBank](#ProcessBank)
  * Modeling Biological Processes for Reading Comprehension [paper](https://nlp.stanford.edu/pubs/berant-srikumar-manning-emnlp14.pdf), [homepage&code&dataset](https://nlp.stanford.edu/software/bioprocess/)

## [2015](#2015)
* 3/1 [bAbI](#bAbI)
* 4/2 [CNN/Daily Mail](#CNNDailyMail)
* 5/3 [CBTest](#CBTest)

## [2016](#2016)
* 6/1 [ROCStories](#ROCStories)
* 7/2 [SQuAD1.0](#SQuAD1.0)
* 8/3 [LAMBADA](#LAMBADA)
* 9/4 [SelQA](#SelQA)
* 10/5 [WikiReading](#WikiReading)
* 11/6 [WDW](#WDW)
* 12/7 [MSMARCO](#MSMARCO)
* 13/8 [NewsQA](#NewsQA)


## [2017](#2017)
* 14/1 [SCT](#SCT)
* 15/2 [RACE](#RACE)
* 16/3 [SearchQA](#SearchQA)
* 17/4 [TriviaQA](#TriviaQA)
* 18/5 [Quasar](#Quasar)
* 19/6 [WikiHop&MedHop](#WikiHop&MedHop)
* 20/7 [CLOTH](#CLOTH)
* 21/8 [NarrativeQA](#NarrativeQA)

## [2018](#2018)
* 22/1 [MCScript](#MCScript)
* 23/2 [ARC](#ARC)
* 24/3 [CliCR](#CliCR)
* 25/4 [DuoRC](#DuoRC)
* 26/5 [EmoryRCDC](#EmoryRCDC)
* 27/6 [SQuAD2.0](#SQuAD2.0)
  * Know What You Don't Know: Unanswerable Questions for SQuAD [paper](https://arxiv.org/abs/1806.03822), [home](https://rajpurkar.github.io/SQuAD-explorer/)
* 28/7 [QuAC](#QuAC)
* 29/8 [CoQA](#CoQA)
* 30/9 [HotpotQA](#HotpotQA)
* 31/10 [ReCoRD](#ReCoRD)



## [2019](#2019)
* 32/1 [Google's Natural Questions](#NQ)

## To be continued...

<hr>

## [中文机器阅读理解数据集](#cmrc) <br> Chinese Machine Reading Comprehension(CMRC) Datasets

## [2016](#c2016)
* [PD&CFT](#PDCFT)
  * Consensus Attention-based Neural Networks for Chinese Reading Comprehension [paper](https://arxiv.org/abs/1607.02250), [dataset](https://github.com/ymcui/Chinese-RC-Dataset)

## [2017](#c2017)
* [The First Evaluation Workshop on Chinese Machine Reading Comprehension (CMRC 2017)](#CMRC2017) 
  * Dataset for the First Evaluation on Chinese Machine Reading Comprehension [paper](https://arxiv.org/abs/1709.08299), [dataset](https://github.com/ymcui/cmrc2017)

* [DuReader](#DuReader)
  * DuReader: a Chinese Machine Reading Comprehension Dataset from Real-world Applications [paper](https://arxiv.org/abs/1711.05073), [dataset&baseline](https://github.com/baidu/DuReader), [homepage](https://ai.baidu.com/broad/subordinate?dataset=dureader)

## [2018](#c2018)
* [The Second Evaluation Workshop on Chinese Machine Reading Comprehension (CMRC 2018)](CMRC2018)
  * A Span-Extraction Dataset for Chinese Machine Reading Comprehension [paper](https://arxiv.org/abs/1810.07366), [dataset](https://github.com/ymcui/cmrc2018)

* [DRCD](#DRCD) (Traditional Chinese machine reading comprehension)
  * DRCD: a Chinese Machine Reading Comprehension Dataset [paper](https://arxiv.org/abs/1806.00920), [dataset](https://github.com/DRCSolutionService/DRCD)
* [ODSQA](#ODSQA) (Traditional Chinese machine reading comprehension)
  * ODSQA: Open-domain Spoken Question Answering Dataset [paper](https://arxiv.org/abs/1808.02280), [dataset](https://github.com/chiahsuan156/ODSQA)

<hr>

## <span id="mrc">Machine Reading Comprehension(MRC) Datasets</span>

## <span id="2013">2013</span>

### <span id="MCTest">MCTest</span>


## <span id="2014">2014</span>

### <span id="ProcessBank">ProcessBank</span>


## <span id="20153">2015</span>

### <span id="bAbI">bAbI</span>

### <span id="CNNDailyMail">CNN/Daily Mail</span>

### <span id="CBTest">CBTest</span>


## <span id="2016">2016</span>

### <span id="ROCStories">ROCStories</span>

### <span id="SQuAD1.0">SQuAD1.0</span>

### <span id="LAMBADA">LAMBADA</span>

### <span id="SelQA">SelQA</span>

### <span id="WikiReading">WikiReading</span>

### <span id="WDW">WDW</span>

### <span id="MSMARCO">MSMARCO</span>

### <span id="NewsQA">NewsQA</span>


## <span id="2017">2017</span>

### <span id="SCT">SCT</span>

### <span id="RACE">RACE</span>

### <span id="SearchQA">SearchQA</span>

### <span id="TriviaQA">TriviaQA</span>

### <span id="Quasar">Quasar</span>

### <span id="WikiHop&MedHop">WikiHop&MedHop</span>

### <span id="CLOTH">CLOTH</span>

### <span id="NarrativeQA">NarrativeQA</span>


## <span id="2018">2018</span>

### <span id="MCScript">MCScript</span>

### <span id="ARC">ARC</span>

### <span id="CliCR">CliCR</span>

### <span id="DuoRC">DuoRC</span>

### <span id="EmoryRCDC">EmoryRCDC</span>

### <span id="SQuAD2.0">SQuAD2.0</span>

### <span id="QuAC">QuAC</span>

### <span id="CoQA">CoQA</span>

### <span id="HotpotQA">HotpotQA</span>

### <span id="ReCoRD">ReCoRD</span>


## <span id="2019">2019</span>

### <span id="NQ">Google's Natural Questions</span>

<hr>

## <span id="cmrc">中文机器阅读理解数据集</span> <br> Chinese Machine Reading Comprehension(CMRC) Datasets

## <span id="c2016">2016</span>

### <span id="PDCFT">PD&CFT</span>

## <span id="c2017">2017</span>

### <span id="CMRC2017">The First Evaluation Workshop on Chinese Machine Reading Comprehension (CMRC 2017)</span>

### <span id="DuReader">DuReader</span>

## <span id="c2018">2018</span>

### <span id="CMRC2018">The Second Evaluation Workshop on Chinese Machine Reading Comprehension (CMRC 2018)</span>

### <span id="DRCD">DRCD</span>

### <span id="ODSQA">ODSQA</span>
