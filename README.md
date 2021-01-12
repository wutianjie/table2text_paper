## Table2Text--Paper＆Code

### Datasets

#### 1、RotoWire

EMNLP2017_Challenges in Data-to-document Generation  [Paper](https://arxiv.org/pdf/1707.08052.pdf)  

[RotoWire下载](https://github.com/harvardnlp/boxscore-data)

输入：一场NBA比赛的数据

输出：一段对比赛情况的描述

其中输入数据更丰富，文本长度更长，通常每篇描述包含5-7句话；并且文字中直接提及或通过不同措辞蕴含的部分信息，需要从具体的数值、时间等信息推断得出，无法从输入的表格数据中直接获取。

**RotoWire-modified**

ACL2019_Learning to Select, Track, and Generate for Data-to-Text  ((Iso et al)  [Paper](https://www.aclweb.org/anthology/P19-1202.pdf)  

[Rotowire-modified](https://github.com/aistairc/rotowire-modified)  [code](https://github.com/aistairc/sports-reporter)

#### 2、WikiBio

EMNLP2016_Neural text generation from structured data with application to the biography domain  [Paper](https://arxiv.org/pdf/1603.07771.pdf) 

[WikiBio下载](https://github.com/DavidGrangier/wikipedia-biography-dataset)

输入：维基百科的infobox

输出：传记的第一句话

维基百科传记数据集WikiBio

#### 3、E2E NLG

SIGDIAL2017_The E2E Dataset-- New Challenges For End-to-End Generation  [Paper](https://arxiv.org/pdf/1706.09254.pdf) 

[E2E NLG下载](http://www.macs.hw.ac.uk/InteractionLab/E2E/)

输入：餐馆信息的表示

输出：对餐馆的自然语言描述

E2E NLG Challenge评测数据集，收集了上万条配对的餐馆描述及语义表示数据

----

### Paper&Code

#### Rotowire

| No   | Paper                                                        | Code                                                         | Note                   |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- |
| 1    | AAAI2019_Data-to-Text Generation with Content Selection and Planning (Puduppully, R.) | [paper&code](https://github.com/ratishsp/data2text-plan-py)  | torch=0.3.1 python=2.7 |
| 2    | ACL2019_Data-to-text Generation with Entity Modeling (Puduppully, R.) | [paper&code](https://github.com/ratishsp/data2text-entity-py) | torch=0.3.1 python=2.7 |
| 3    | ECIR2019_C_A Hierarchical Model for Data-to-Text Generation (Rebuffel) | [paper&code](https://github.com/KaijuML/data-to-text-hierarchical) | torch=1.1.0 python=3.6 |
| 4    | EMNLP2019_Table-to-Text Generation with Effective Hierarchical Encoder on Three Dimensions (Row, Column and Time) | [paper&code](https://github.com/ernestgong/data2text-three-dimensions/) | based on code1         |
| 5    | EMNLP2020_Enhancing Content Planning for Table-to-Text Generation with Data Understanding and Verification | [paper&code](https://github.com/ErnestGong/data2text-duv)    | release soon...        |
| 6    | EMNLP2020_Stepwise Extractive Summarization and Planning with Structured Transformers | [paper&code](https://github.com/google-research/google-research/tree/master/etcsum) | release soon...        |
| 7    | EMNLP2018_Operation-guided Neural Networks for High Fidelity Data-To-Text Generation | [paper](https://arxiv.org/pdf/1809.02735v1.pdf)              | 提出了数据集ESPN       |
| 8    | EMNLP2018_Learning Latent Semantic Annotations for Grounding Natural Language to Structured Data | [paper](https://www.aclweb.org/anthology/D18-1411.pdf) [code](https://github.com/hiaoxui/D2T-Grounding) | python=3.6             |
| 9    | COLING2018_Point Precisely--Towards Ensuring the Precision of Data in Generated Texts Using Delayed Copy Mechanism | [paper](https://www.aclweb.org/anthology/C18-1089.pdf)       |                        |
| 10   | EMNLP2018_Data2Text Studio--Automated Text Generation from Structured Data | [paper](https://www.aclweb.org/anthology/D18-2003.pdf)       |                        |
| 11   | EMNLP2019_Selecting, Planning, and Rewriting--A Modular Approach for Data-to-Document Generation and Translation | [paper](https://www.aclweb.org/anthology/D19-5633.pdf)       |                        |



#### WikiBio

| No   | Paper                                                        | Code                                                         | Note                   |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- |
| 1    | AAAI2018_Order-planning neural text generation from structured data | [paper&code](https://github.com/anindyasarkarIITH/Structure_data_to_summary?utm_source=catalyzex.com) |                        |
| 2    | AAAI2018_Table-to-text Generation by Structure-aware Seq2seq Learning | [paper&code](https://github.com/tyliupku/wiki2bio?utm_source=catalyzex.com) | tf=1.0 python=2.7      |
| 3    | EMNLP2018_Learning Neural Templates for Text Generation      | [paper&code](https://github.com/harvardnlp/neural-template-gen?utm_source=catalyzex.com) | torch=0.3.1 python=2.7 |
| 4    | AAAI2018_Table-to-Text--Describing Table Region with Natural Language | [paper](https://arxiv.org/pdf/1805.11234.pdf)                |                        |
| 5    | AAAI2019_Hierarchical Encoder with Auxiliary Supervision for Neural Table-to-Text Generation Learning Better Representation for Tables | [paper](https://ojs.aaai.org//index.php/AAAI/article/view/4653) |                        |
| 6    | ACL2019_Towards Comprehensive Description Generation from Factual Attribute-value Tables | [paper](https://www.aclweb.org/anthology/P19-1600.pdf)       |                        |
| 7    | EMNLP2019_Enhancing Neural Data-To-Text Generation Models with External Background Knowledge | [paper](https://www.aclweb.org/anthology/D19-1299.pdf)       | WikiBio数据集扩展      |
| 8    | ICLR2020_Variational Template Machine for Data-to-Text Generation | [paper](https://openreview.net/pdf?id=HkejNgBtPB)            |                        |
| 9    |                                                              |                                                              |                        |



**E2E NLG**

| No   | Paper                                                        | Code                                                         | Note                   |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- |
| 1    | EMNLP2018_Learning Neural Templates for Text Generation      | [paper&code](https://github.com/harvardnlp/neural-template-gen?utm_source=catalyzex.com) | torch=0.3.1 python=2.7 |
| 2    | NAACL2018_A Deep Ensemble Model with Slot Alignment for Sequence-to-Sequence Natural Language Generation | [paper](https://arxiv.org/pdf/1805.06553.pdf)                |                        |
| 3    | INLG2018_End-to-End Content and Plan Selection for Data-to-Text Generation | [paper](https://arxiv.org/pdf/1810.04700.pdf)                |                        |
| 4    |                                                              |                                                              |                        |

