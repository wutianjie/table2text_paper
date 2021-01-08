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

EMNLP2016_Neural text generation from structured data with application to the biography domain[Paper](https://arxiv.org/pdf/1603.07771.pdf) 

[WikiBio下载](https://github.com/DavidGrangier/wikipedia-biography-dataset)

输入：维基百科的infobox

输出：传记的第一句话

维基百科传记数据集WikiBio

#### 3、E2E

SIGDIAL2017_The E2E Dataset-- New Challenges For End-to-End Generation  [Paper](https://arxiv.org/pdf/1706.09254.pdf) 

[E2E 下载](http://www.macs.hw.ac.uk/InteractionLab/E2E/)

输入：餐馆信息的表示

输出：对餐馆的自然语言描述

E2E NLG Challenge评测数据集，收集了上万条配对的餐馆描述及语义表示数据

----

### Code

#### Rotowire

1. AAAI2019_Data-to-Text Generation with Content Selection and Planning (Puduppully, R.)

   torch=0.3.1 python=2.7  [paper&code](https://github.com/ratishsp/data2text-plan-py)

2. ACL2019_Data-to-text Generation with Entity Modeling (Puduppully, R.)

   torch=0.3.1 python=2.7  [paper&code](https://github.com/ratishsp/data2text-entity-py)

3. ECIR2019_C_A Hierarchical Model for Data-to-Text Generation (Rebuffel)  

   torch=1.1.0 python=3.6  [paper&code](https://github.com/KaijuML/data-to-text-hierarchical)

4. EMNLP2019_Table-to-Text Generation with Effective Hierarchical Encoder on Three Dimensions (Row, Column and Time)

   based on code1  [paper&code](https://github.com/ernestgong/data2text-three-dimensions/)

5. EMNLP2020_Enhancing Content Planning for Table-to-Text Generation with Data Understanding and Verification

   release soon...[paper&code](https://github.com/ErnestGong/data2text-duv)

6. EMNLP2020_Stepwise Extractive Summarization and Planning with Structured Transformers

   release soon...[paper&code](https://github.com/google-research/google-research/tree/master/etcsum)

#### WikiBio

1. AAAI2018_Order-planning neural text generation from structured data

   [paper&code](https://github.com/anindyasarkarIITH/Structure_data_to_summary?utm_source=catalyzex.com)

2. AAAI2018_Table-to-text Generation by Structure-aware Seq2seq Learning

   [paper&code](https://github.com/tyliupku/wiki2bio?utm_source=catalyzex.com)

3. EMNLP2018_Learning Neural Templates for Text Generation

   [paper&code](https://github.com/harvardnlp/neural-template-gen?utm_source=catalyzex.com)

E2E NLG

1. EMNLP2018_Learning Neural Templates for Text Generation

   python=2.7 and pytorch=0.3.1  [paper&code](https://github.com/harvardnlp/neural-template-gen?utm_source=catalyzex.com)

