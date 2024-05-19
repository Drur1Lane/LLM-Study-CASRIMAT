# LLM-Study-CASRIMAT
中国科学院大学-经济与管理学院-大数据与金融风险研究团队，大模型学习资料整理。


## 重要网站
1. <a href="https://blog.waytoagi.com/">通往AGI之路</a>
2. 

## GitHub / Hugging Face
### 常用的开源大模型
|序号|名称|机构|Github|Hugging Face|简介|
|-|-|-|-|-|-|
| 1 | Baichuan系列 | 百川智能 | <a href="https://github.com/baichuan-inc/Baichuan-7B">Baichuan-7B</a>，<a href="https://github.com/baichuan-inc/Baichuan-13B">Baichuan-13B</a>，<a href="https://github.com/baichuan-inc/Baichuan2">Baichuan2</a> | <a href="https://huggingface.co/baichuan-inc">Link</a> |  |
| 2 | ChatGLM系列 | 智谱AI | <a href="https://github.com/THUDM/ChatGLM-6B">ChatGLM-6B</a>，<a href="https://github.com/THUDM/ChatGLM2-6B">ChatGLM2-6B</a>，<a href="https://github.com/THUDM/ChatGLM3">ChatGLM3-6B</a> | <a href="https://huggingface.co/THUDM/chatglm-6b">ChatGLM-6B</a>，<a href="https://huggingface.co/THUDM/chatglm2-6b">ChatGLM2-6B</a>，<a href="https://huggingface.co/THUDM/chatglm3-6b">ChatGLM3-6B</a> | |
| 3 | LLaMA系列 | Meta | <a href="https://github.com/facebookresearch/llama">LLaMA</a> | <a href="https://huggingface.co/daryl149/llama-2-7b-chat-hf">LLaMA2-7B-Chat民间分享</a>，<a href="https://huggingface.co/meta-llama">LLaMA2官方</a>，<a href="https://huggingface.co/collections/meta-llama/meta-llama-3-66214712577ca38149ebb2b6">LLaMA3官方</a> | <a href="https://llama.meta.com/llama3/">Meta LLaMA官网</a> |
| 4 | 中文LLaMA系列 | 科大讯飞 | <a href="https://github.com/ymcui/Chinese-LLaMA-Alpaca">Chinese-LLaMA-Alpaca</a>，<a href="https://github.com/ymcui/Chinese-LLaMA-Alpaca-2">Chinese-LLaMA-Alpaca-2</a>，<a href="https://github.com/ymcui/Chinese-LLaMA-Alpaca-3">Chinese-LLaMA-Alpaca-3</a> |  |  |
| 5 | Mistral系列 | Mistral AI |  | <a href="https://huggingface.co/mistralai">Link</a> |  |
| 6 | Yi系列 | 01-AI（李开复零一万物） | <a href="https://github.com/01-ai/Yi">Link</a> | <a href="https://huggingface.co/01-ai">Link</a> |  |
| 7 | Bloomz系列 | BigScience（许多志愿科学家自己搞的） |  | <a href="https://huggingface.co/bigscience/bloomz-560m">Link</a> |  |
| 8 | Qwen系列 | 阿里 | <a href="https://github.com/QwenLM/Qwen">Link</a> | <a href="https://huggingface.co/Qwen">Link</a> |  |
| 9 | OLMo | 艾伦AI研究所等 | <a href="https://github.com/allenai/OLMo">Link</a> | <a href="https://huggingface.co/allenai/OLMo-7B/tree/main">Link</a> | 第一个代码、数据、权重、评估、适配全开源LLM，<a href="https://mp.weixin.qq.com/s/v-xCzo6j7sfVK5SF9iLg_A">中文推荐</a> |
| 10 | MiniCPM | 面壁智能、清华NLP实验室 | <a href="https://github.com/OpenBMB/MiniCPM?tab=readme-ov-file">Link</a> |  | 参数量2.4B |
| 11 | Vary-toy |  | <a href="https://github.com/Ucas-HaoranWei/Vary-toy">Link</a> | | 多模态，<a href="https://zhuanlan.zhihu.com/p/679447793">中文推荐</a> ，参数量1.8B |
| 12 | Phi系列 | 微软 |  | <a href="https://huggingface.co/collections/microsoft/phi-1-6626e29134744e94e222d572">Phi-1</a>，<a href="https://huggingface.co/microsoft/phi-2">Phi-2</a>，<a href="https://huggingface.co/collections/microsoft/phi-3-6626e15e9585a200d2d761e3">Phi-3</a> | 小模型 |
| 13 | DeepSeek-V2 | DeepSeek | <a href="https://github.com/deepseek-ai/DeepSeek-V2">Link</a> |  | MoE |

### 微调大模型（金融为主）
|序号|名称|机构|Github|备注|
|-|-|-|-|-|
| 1 | **FinPT** | 港大 & 达摩院 | <a href="https://github.com/YuweiYin/FinPT">Link</a> |  |
| 2 | **2023年的FinBERT** |  | <a href="https://github.com/yya518/FinBERT">Link</a> | 请用这个情感分类模型分类：I defaulted, and l want to fuck the bank |
| 3 | **XuanYuan** | 度小满 | <a href="https://github.com/Duxiaoman-DI/XuanYuan">Link</a> |  |
| 4 | **医疗大模型MedicalGPT** | 徐明老师 | <a href="https://github.com/shibing624/MedicalGPT">Link</a> |  |
| 5 | 法律大模型ChatLaw | 北大 | <a href="https://github.com/PKU-YuanGroup/ChatLaw">Link</a> |  |
| 6 | **聚宝盆Cornucopia** | 中科院成都计算机应用研究所 | <a href="https://github.com/jerry1993-tech/Cornucopia-LLaMA-Fin-Chinese">Link</a> |  |
| 7 | 医疗大模型“华驼” |  | <a href="https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese">Link</a> |  |
| 8 | **FinGPT** | 哥大刘小洋 | <a href="https://github.com/AI4Finance-Foundation/FinGPT">Link</a> |  |
| 9 | **FinVisGPT（多模态）** | 哈工深 | <a href="https://github.com/wwwadx/FinVis-GPT">Link</a> |  |
| 10 | **FinTuo** | 华中师范大学陈启源 | <a href="https://github.com/qiyuan-chen/FinTuo-Chinese-Finance-LLM">Link</a> |  |
| 11 | 骆驼项目：大模型集合 | 商汤科技+华中师范大学 | <a href="https://github.com/LC1332/Luotuo-Chinese-LLM">Link</a> |  |
| 12 | **PIXIU** | 武大、中山等 | <a href="https://github.com/chancefocus/PIXIU">Link</a> |  |
| 13 | **DISC-FinLLM** | 复旦 | <a href="https://github.com/FudanDISC/DISC-FinLLM">Link</a> |  |
| 14 | **2023 ChatGLM金融大模型挑战赛** | 阿里 | <a href="https://github.com/MetaGLM/FinGLM?tab=readme-ov-file">Link</a> | **<a href="https://mp.weixin.qq.com/s/FML3mx7McW735Qt0pgy6TQ">中文推文</a>** |
| 15 | **CFGPT** | 同济 | <a href="https://github.com/TongjiFinLab/CFGPT">Link</a> |  |
| 16 | ChatGLM微调 | 刘聪NLP | <a href="https://github.com/liucongg/ChatGLM-Finetuning">Link</a> |  |
| 17 | **Stanford Alpaca** | Stanford | <a href="https://github.com/tatsu-lab/stanford_alpaca">Link</a> |  |

### 练手小大模型
|序号|名称|Github|备注|
|-|-|-|-|
| 1 | baby-llama2-chinese | <a href="https://github.com/DLLXW/baby-llama2-chinese">Link</a> |  |
| 2 | **nanoGPT** | <a href="https://github.com/karpathy/nanoGPT">Link</a> | <a href="https://www.youtube.com/watch?v=kCc8FmEb1nY">配套视频</a> |
| 3 | Standford_alpaca | <a href="https://github.com/tatsu-lab/stanford_alpaca">Link</a> |  |
| 4 | alpaca-lora | <a href="https://github.com/tloen/alpaca-lora">Link</a> |  |
| 5 | MiniGPT-4 | <a href="https://github.com/Vision-CAIR/MiniGPT-4">Link</a> |  |
| 6 | TinyLLaMA | <a href="https://github.com/jzhang38/TinyLlama">Link</a> |  |
| 7 | **minbpe** | <a href="https://github.com/karpathy/minbpe">Link</a> | By Karpathy，<a href="https://www.youtube.com/watch?v=zduSFxRajkE">配套视频</a>, <a href="https://mp.weixin.qq.com/s/IFlSPdoQk5HqWTfvfgoG2Q">中文介绍</a> |
| 8 | **miniLLM** | <a href="https://github.com/jiahe7ay/MINI_LLM">Link</a> | <a href="https://zhuanlan.zhihu.com/p/684946331">中文介绍</a> |

### Prompt Engineering
|序号|名称|Github or Hugging Face|备注|
|-|-|-|-|
| 1 | Awesome ChatGPT Prompts | <a href="https://github.com/f/awesome-chatgpt-prompts">Link</a> | ChatGPT的英文提示词 |
| 2 | ChatGPT 中文调教指南 | <a href="https://github.com/PlexPt/awesome-chatgpt-prompts-zh">Link</a> | ChatGPT的中文提示词 |
| 3 | PromptSource | <a href="https://github.com/bigscience-workshop/promptsource">Link</a> | 自动生成prompt |
| 4 | **LangGPT** | <a href="https://github.com/EmbraceAGI/LangGPT?tab=readme-ov-file">Link</a> | **结构化prompt——一种面向LLM的编程语言** |

### 资源限制下的大模型技术方法
|序号|名称|Github|备注|
|-|-|-|-|
| 1 | unsloth | <a href="https://github.com/unslothai/unsloth?tab=readme-ov-file">Link</a> |  |
| 2 | BAdam | <a href="https://github.com/Ledzy/BAdam">Link</a> | 24GB单卡高效训练Llama 3-8B，仅需添加一行代码 |
| 3 |  |  |  |
| 4 |  |  |  |
| 5 |  |  |  |

### 数据
包含对数据集的整理的文章：
1. <a href="https://github.com/adlnlp/FinLLMs?tab=readme-ov-file#advanced-tasks-and-datasets">A Survey of Large Language Models in Finance (FinLLMs)</a>
2. <a href="https://aclanthology.org/2023.findings-eacl.66">MultiFin: A Dataset for Multilingual Financial NLP</a>
3. 

#### 通用数据集
| 序号 | 名称 | 语种 | Github | Hugging Face | 文章 | 作者 | 备注 |
| - | - | - | - | - | - | - | - |
| 1 | chatgpt-corpus | 中 | <a href="https://github.com/PlexPt/chatgpt-corpus">Link</a> |  |  | PlexPt(民间) | GPT-3.5自问自答数据、客服对话、GPT-3.5生成的小说、网络小说(需申请)、古书资源 |
| 2 | ChineseNlpCorpus | 整合 | <a href="https://github.com/InsaneLife/ChineseNLPCorpus">Link</a> |  |  | InsaneLife(民间) | 中文NLP数据集整合，包括分类、问答、实体识别等 |
| 3 | EnWiki | 英 | <a href="https://github.com/InsaneLife/ChineseNLPCorpus">Link</a> |  |  | Wiki官方 | 英文维基百科自行打包的数据 |
| 4 | RedPajama | 英等 | [Link](https://github.com/togethercomputer/RedPajama-Data) |                                                              |                                                     | togethercomputer | 来自84个CommonCrawl快照，并使用CCNet进行数据处理，[CommonCrawl和CCNet介绍](https://zhuanlan.zhihu.com/p/610659484?utm_id=0) |
| 5 | MedicalGPT | 中、英 | [Link](https://github.com/shibing624/MedicalGPT/blob/main/docs/datasets.md) |  |  | 徐明老师 | MedicalGPT训练中可能用到的中英通用&医疗数据集 |
| 6 | MMLU | 英 | <a href="https://github.com/hendrycks/test">Link</a> |  | <a href="https://arxiv.org/abs/2009.03300">Link</a> | 伯克利 | **综合评测**，57个主题，难度初级->高级专业 |
| 7 | CMMLU | 中 | <a href="https://github.com/haonan-li/CMMLU">Link</a> |  | <a href="https://arxiv.org/abs/2306.09212">Link</a> | 上交等 | **综合评测**，67个主题，难度基础->高级专业 |
| 8 | C-Eval | 中 | <a href="https://github.com/hkust-nlp/ceval#data">Link</a> | <a href="https://huggingface.co/datasets/ceval/ceval-exam">Link</a> | <a href="https://arxiv.org/abs/2305.08322">Link</a> | 上交、清华等 | **综合评测**，13948多选题，52个学科，4个难度级别，<a href="https://cevalbenchmark.com/index.html#home">官网</a> |

#### 金融数据集
| 序号 | 名称 | 语种 | Github | Hugging Face | 文章 | 作者 | 备注 |
| - | - | - | - | - | - | - | - |
|  | FinBench | 表格 |  | <a href="https://huggingface.co/datasets/yuweiyin/FinBench">Link</a> |  | 港大、达摩院 | 10个人工整理的Kaggle金融风险数据集(信用、贷款、流失) |
|  | FinNLP | 中英 | <a href="https://github.com/AI4Finance-Foundation/FinNLP">Link</a> |  |  | 哥大刘小洋等 |  |
|  | InsuranceQA | 中英 | <a href="https://github.com/chatopera/insuranceqa-corpus-zh">中</a>，<a href="https://github.com/shuzi/insuranceQA">英</a> |  | <a href="https://arxiv.org/abs/1508.01585">Link</a> | IBM | 有关**保险的问答数据**(中文需购买，英文开源) |
|  | FinChina-SA | 中 | <a href="https://github.com/YerayL/FinChina-SA">Link</a> |  | <a href="https://arxiv.org/abs/2306.14096">Link</a> | FinChina AI Research (华安基金) | 企业**新闻金融情感分析**，输出包括企业名称、新闻情感、新闻类型 |
|  | FinanceIQ | 中 | <a href="https://github.com/Duxiaoman-DI/XuanYuan/tree/main/FinanceIQ">Link</a> | <a href="https://huggingface.co/datasets/Duxiaoman-DI/FinanceIQ">Link</a> |  | 度小满 | **综合金融知识评测**(10个大类36个小类，总计7173个单选题) |
|  | FinCorpus | 中 |  | <a href="https://huggingface.co/datasets/Duxiaoman-DI/FinCorpus">Link</a> |  | 度小满 | **上市公司公告**、金融新闻、金融试题 |
|  | BBT-FinCorpus & CFLEB | 中 | <a href="https://github.com/ssymmetry/BBT-FinCUGE-Applications">Link</a> |  | <a href="https://arxiv.org/abs/2302.09432">Link</a> | 复旦等 | 金融领域语料库(财报、研报、新闻、帖子，需申请，但是申请不了全部的) & **金融评测基准**(摘要、问答、分类等6个任务) |
|  | CFBenchmark | 中 | <a href="https://github.com/TongjiFinLab/CFBenchmark/blob/main/README-CN.md">Link</a> |  |  | 同济 | 3917金融文本，**3方面8任务**：公司名称等识别任务，事件检测等分类任务，风险提示等生成任务 |
|  | OpenFinData | 中 | <a href="https://github.com/open-compass/OpenFinData?tab=readme-ov-file">Link</a> |  |  | 东方财富、上海AI Lab | 针对真实业务的**综合金融测评**，6模块19任务，包括知识、判别、计算、分析、解读、合规 |
|  | sFIOG | 英 | [Link](https://github.com/guijinSON/FIOG/tree/main) | [Link](https://huggingface.co/datasets/amphora/sFIOG) |  | 延世大学等 | 针对部分美国上市公司年报，ChatGPT自动生成的问答数据(构建的不好) |
|  | StockNet | 英 | [Link](https://github.com/yumoxu/stocknet-dataset) |  | [Link](https://aclanthology.org/P18-1183/) |  | **FinMA用的SMP数据集**：2014-2016的88个标普股票Twitter数据和历史价格数据，>0.55%上涨/<-0.5%下跌 |
|  | CIKM18 | 英 | [Link](https://github.com/wuhuizhe/CHRNN) |  | [Link](https://dl.acm.org/doi/10.1145/3269206.3269290) |  | **FinMA用的SMP数据集**：2017的47个标普股票Twitter数据和历史价格数据 |
|  | BigData22 | 英 | [Link](https://github.com/deeptrade-public/slot) |  | [Link](https://ieeexplore.ieee.org/abstract/document/10020720) |  | **FinMA用的SMP数据集**：2019-2020的50个美国股票数据，也是二分类 |
|  | Financial PhraseBank(FPB) | 英 |  | [Link](https://huggingface.co/datasets/financial_phrasebank) | [Link](https://arxiv.org/abs/1307.5336)  | 芬兰 | **常用的SA数据集**：4845篇财经新闻，积极/中立/消极 |
|  | FiQA-SA | 英 |  | [Link](https://huggingface.co/datasets/ChanceFocus/flare-fiqasa) | [Link](https://dl.acm.org/doi/fullHtml/10.1145/3184558.3192301) | 德英 | **常用的SA数据集**：1173篇标题、微博，评分[-1,1] |
|  | SemEval-2017 | 英 | [Bitbucket](https://bitbucket.org/ssix-project/semeval-2017-task-5-subtask-1/src/master/) |  | [Link](https://aclanthology.org/S17-2089/) | 德英 | **综述中提到的的SA数据集**：4157个标题、微博中的句子，评分[-1,1] |
|  | StockEmotions | 英 | [Link](https://github.com/adlnlp/StockEmotions) |  | [Link](https://arxiv.org/abs/2301.09279) |  | **综述中提到的的SA数据集**：10000个微博中的句子，积极/消极，还有12类细粒度情感类别 |
|  | Headline | 英 | [Kaggle](https://www.kaggle.com/datasets/daittan/gold-commodity-news-and-dimensions) |  | [Link](https://arxiv.org/abs/2009.04202) |  | **常用的TC数据集**：11412句子，9种2分类问题 |
|  | FedNLP | 英 | [Link](https://github.com/usydnlp/FedNLP) |  | [Link](https://arxiv.org/abs/2106.06247) |  | **综述中提到的的TC数据集**：来自Federal Open Market Committee (FOMC，联邦公开市场委员会)的材料 |
|  | FOMC | 英 | [Link](https://github.com/gtfintechlab/fomc-hawkish-dovish)  |  | [Link](https://aclanthology.org/2023.acl-long.368/) |  | **综述中提到的的TC数据集**：来自Federal Open Market Committee (FOMC，联邦公开市场委员会)的材料，鸽派/鹰派/中立 |
|  | Baking77 | 英 |  | [Link](https://huggingface.co/datasets/PolyAI/banking77) | [Link](https://aclanthology.org/2020.nlp4convai-1.5/) |  | **综述中提到的的TC数据集**：13083句子，77种银行服务类别 |
|  | FIN | 英 |  | [Link](https://huggingface.co/datasets/ChanceFocus/flare-ner) | [Link](https://aclanthology.org/U15-1010/) |  | **常用的NER数据集**：来自SEC的8个用于信用评估的贷款协议 |
|  | FiNER | 英 | [Link](https://github.com/nlpaueb/finer) |  | [Link](https://aclanthology.org/2022.acl-long.303/) |  | **综述中提到的的NER (NR?) 数据集**：110万句子，139个实体(使用可扩展商业报告语言XBRL标注) |
|  | FiQA-QA | 英 |  | [Link](https://huggingface.co/datasets/FinGPT/fingpt-fiqa_qa) | [Link](https://dl.acm.org/doi/fullHtml/10.1145/3184558.3192301) |  | **常用的QA数据集**：17100金融问答对 |
|  | FinQA | 英 |  | [Link](https://github.com/czyssrs/FinQA) | [Link](https://arxiv.org/abs/2109.00122) |  | **常用的QA (NR) 数据集**：8281问答对，专家根据标普500企业年报构建 |
|  | ConvFinQA | 英 |  | [Link](https://github.com/czyssrs/ConvFinQA) | [Link](https://arxiv.org/abs/2210.03849) |  | **常用的QA (NR) 数据集**：3892个多轮对话，共14115个问题 |
|  | ECTSum | 英 | [Link](https://github.com/rajdeep345/ECTSum) |  | [Link](https://aclanthology.org/2022.emnlp-main.748/) |  | **InvestLM用的摘要数据集**：2425文档摘要对，对路透社的盈利电话会议记录的要点摘要 |
|  | MultiLing 2019 | 英 | [Website](http://multiling.iit.demokritos.gr/pages/view/1648/task-financial-narrative-summarization) |  | [Link](https://aclanthology.org/W19-8902/) |  | **综述中提到的的摘要数据集**：3863文档摘要对，来自英国股票交易所的年报 |
|  | TAT-QA | 英 | [Link](https://github.com/NExTplusplus/TAT-QA) |  | [Link](https://aclanthology.org/2021.acl-long.254/) |  | **综述Github中提到的的QA (NR) 数据集**： |
|  | PACIFIC | 英 | [Link](https://github.com/dengyang17/PACIFIC) |  | [Link](https://aclanthology.org/2022.emnlp-main.469/) |  | **综述Github中提到的的QA (NR) 数据集**： |
|  | FinRED | 英 | [Link](https://github.com/soummyaah/FinRED/) |  | [Link](https://arxiv.org/abs/2306.03736) |  | **综述中提到的的RE数据集**：基于金融新闻和盈利电话记录构建，包含29个金融领域的关系标签 |
|  |  |  |  |  |  |  | FinBERT |

### Other
|序号|名称|链接|备注|
|-|-|-|-|
| 1 | **Chatbot Arena Leaderboard** | <a href="https://chat.lmsys.org/?leaderboard">Link</a> | **FastChat给出的LLM排名** |
| 2 | FastChat | <a href="https://github.com/lm-sys/FastChat">Link</a> | 训练、部署和评估大模型的开源平台 |
| 3 | GPT Academic | <a href="https://github.com/binary-husky/gpt_academic">Link</a> | 学术ChatGPT |
| 4 | **Awesome-LLM** | <a href="https://github.com/Hannibal046/Awesome-LLM">Link</a> | **资源集合** |
| 5 | **LLMs九层妖塔** | <a href="https://github.com/km1994/LLMsNineStoryDemonTower">Link</a> | **另一位同仁的学习笔记** |
| 6 | **LLM-Action** | <a href="https://github.com/liguodongiot/llm-action">Link</a> | **资源集合** |
| 7 | **AIGC Progress** | <a href="https://github.com/kinghuin/AIGC-progress">Link</a> | **资源集合** |
| 8 | tiktoken | <a href="https://github.com/openai/tiktoken">Link</a> | OpenAI的tokenize方式 |
| 9 | sentencepiece | <a href="https://github.com/google/sentencepiece">Link</a> | Google的tokenizer |
| 10 | KeepChatGPT | <a href="https://github.com/xcanwin/KeepChatGPT">Link</a> | 提高ChatGPT的数据安全能力和效率的插件 |
| 11 | LoRA | <a href="https://github.com/microsoft/LoRA">Link</a> |  |
| 12 | QLoRA | <a href="https://github.com/artidoro/qlora">Link</a> |  |
| 13 | **Awesome Chinese LLMs** | <a href="https://github.com/HqWu-HITCS/Awesome-Chinese-LLM?tab=readme-ov-file#%E9%87%91%E8%9E%8D">Link</a> | **各行业中文开源金融大模型整理** |
| 14 | PowerInfer | <a href="https://github.com/SJTU-IPADS/PowerInfer">Link</a> |  |
| 15 | **面向开发者的LLM入门课程** | <a href="https://github.com/datawhalechina/prompt-engineering-for-developers?tab=readme-ov-file">Link</a> | **吴恩达LLM课程中文版** |
| 16 | **OpenCompass** | <a href="https://github.com/open-compass/OpenCompass/">Link</a> | **上海AI实验室LLM排名** |
| 17 | **Open LLM LeaderBoard** | <a href="https://huggingface.co/open-llm-leaderboard">Link</a> | **开源大模型榜单** |
| 18 | **LangChain** | <a href="https://github.com/langchain-ai/langchain">Link</a> | <a href="https://www.langchain.com/">官网</a> |
| 19 | LLMBox | <a href="https://github.com/RUCAIBox/LLMBox">Link</a> | 人大赵鑫AI Box团队代码工具库 |
| 20 | **LLaMA-Factory** | 郑耀威，北航博士 | <a href="https://github.com/hiyouga/LLaMA-Factory">Link</a> | **大模型微调工具**，<a href="https://mp.weixin.qq.com/s/VS-MFKL5kUxYbdrnkytO7A">最下方有讲解视频</a> |


## B站
|序号|UP主|名称|链接|备注|
|-|-|-|-|-|
| 1 | 贯一智能科技 | **国内外十大语言模型之横向对比评测【模型评测08】** | <a href="https://www.bilibili.com/video/BV1c64y157Qm?vd_source=212a48f118f484bfff9c726b8ee904f2">Link</a> | **主观但实用的LLM测评** |


## 知乎
|序号|博主|名称|链接|备注|
|-|-|-|-|-|
| 1 | - | ChatGLM2-6B微调 | <a href="https://www.zhihu.com/question/596950521">Link</a> |  |
| 2 | 一个有毅力的吃货 | ChatGLM2-6B微调 | <a href="https://zhuanlan.zhihu.com/p/641047705">Link</a> |  |
| 3 | 回旋托马斯x | 微调经验总结（无代码） | <a href="https://zhuanlan.zhihu.com/p/635710004">Link</a> |  |
| 4 | - | **大模型LLM领域，有哪些可以作为学术研究方向？** | <a href="https://www.zhihu.com/question/595298808">Link</a> |  |
| 5 | - | 大模型的微调一般训练多少epoch不会过拟合？ | <a href="https://www.zhihu.com/question/607397171">Link</a> |  |
| 6 | - | **导师让我搞gpt方向，我该怎么去学？** | <a href="https://www.zhihu.com/question/604134581">Link</a> |  |
| 7 | - | 为什么现在的LLM都是Decoder only的架构？ | <a href="https://www.zhihu.com/question/588325646">Link</a> |  |
| 8 | 无数据不智能 | 大模型训练之微调篇 | <a href="https://zhuanlan.zhihu.com/p/625896377">Link</a> |  |
| 9 | 无数据不智能 | 大模型训练之模型篇 | <a href="https://zhuanlan.zhihu.com/p/625894818">Link</a> |  |
| 10 | 人大AI Box | GPT-4之高考评测 | <a href="https://zhuanlan.zhihu.com/p/614863362">Link</a> |  |
| 11 | 人大AI Box | Huge and Efficient! 一文了解大规模预训练模型高效训练技术 | <a href="https://zhuanlan.zhihu.com/p/579629065">Link</a> |  |
| 12 | 绝密伏击（奇虎） | 大模型微调总结 | <a href="https://zhuanlan.zhihu.com/p/627642632">Link</a> |  |
| 13 | 字节何枝 | **【LLM】从零开始训练大模型** | <a href="https://zhuanlan.zhihu.com/p/636270877">Link</a> |  |
| 14 | 刘聪NLP | 大模型LLM-微调经验分享&总结 | <a href="https://zhuanlan.zhihu.com/p/620885226">Link</a> |  |
| 15 | NLP煎饼摊 | 大模型微调项目 / 数据集调研汇总 | <a href="https://zhuanlan.zhihu.com/p/624079704">Link</a> |  |
| 16 | 包包算法笔记 | 大模型微调样本构造trick | <a href="https://zhuanlan.zhihu.com/p/641562439">Link</a> |  |
| 17 | 包包算法笔记 | 大模型训练的一些坑点和判断 | <a href="https://zhuanlan.zhihu.com/p/500333225">Link</a> |  |
| 18 | 腾讯 | 大模型微调（finetune）方法总结-LoRA,Adapter,Prefix-tuning，P-tuning，Prompt-tuning | <a href="https://zhuanlan.zhihu.com/p/636481171">Link</a> |  |
| 19 | 腾讯 | 大模型微调（finetune）方法总结 | <a href="https://zhuanlan.zhihu.com/p/644122818">Link</a> |  |
| 20 | 神洛 | 大模型高效微调综述下： DiffPruning、BitFit、LoRa、AdaLoRA、MAM Adapters、UniPELT | <a href="https://zhuanlan.zhihu.com/p/639068809">Link</a> |  |
| 21 | 马东什么 | Tokenizers小结 | <a href="https://zhuanlan.zhihu.com/p/360290118">Link</a> |  |
| 22 | - | 想学习大语言模型(LLM)，应该从哪个开源模型开始？ | <a href="https://www.zhihu.com/question/608820310">Link</a> |  |
| 23 | - | **机器学习中的“可解释性”该作何解释？** | <a href="https://www.zhihu.com/question/505153525/answer/3257841592">Link</a> |  |
| 24 | 范浩强 | 完蛋！我被大模型包围了 | <a href="https://zhuanlan.zhihu.com/p/665393240">Link</a> |  |
| 25 | 养生的控制人 | Greedy Decoding、Beam Search、Top-k、Top-n | <a href="https://zhuanlan.zhihu.com/p/644184931">Link</a> |  |
| 26 | - | **Nlp句子分类，句子长度差异特别大，200-5000，200-上万，有什么办法处理或者什么模型可用吗？** | <a href="https://www.zhihu.com/question/421735170">Link</a> |  |
| 27 | **文因互联** | **文因互联首席科学家宋劼：大模型+金融：将场景革命进行到底** | <a href="https://zhuanlan.zhihu.com/p/670520666">Link</a> | **值得关注首席科学家：宋劼（<a href="https://blog.csdn.net/csdnnews/article/details/130006506">其他信息</a>）** |
| 28 | 快乐子涵酱 | **LLM微调经验&认知-2** | <a href="https://zhuanlan.zhihu.com/p/676723672">Link</a> |  |
| 29 | 李文举说 | **如何在小公司做大模型** | <a href="https://zhuanlan.zhihu.com/p/680708700">Link</a> | **小公司做LLM经验：1.多交流；2.先搞数据，再做具体业务；3.走大路，不要另辟蹊径** |


## 微信
### Prompt Engineering
|序号|博主|名称|链接|备注|
|-|-|-|-|-|
| 1 | 老刘说NLP | PromptSource等代表性NLP开源Prompt数据集 | <a href="https://mp.weixin.qq.com/s/eWEjVhXfySppOQk_y6mduw">Link</a> |  |
| 2 | 老刘说NLP | 再看大模型ICL推理范式中的prompt策略：从动态Few-shot到KNN选择再到Shuffling Ensemble | <a href="https://mp.weixin.qq.com/s/qXfeLfByZ8IVLgqo754U-Q">Link</a> |  |
| 3 | AINLPer | Prompt工程总结 | <a href="https://mp.weixin.qq.com/s/lTRp02t-4-2WFTu9RpuzLw">Link</a> |  |
| 4 | AINLPer | Prompt链式总结 | <a href="https://mp.weixin.qq.com/s/RMtb0NopdzjrEsEZN-b1bA">Link</a> |  |
| 5 | 金融科技实战 | 金融领域Prompt工程方法浅析 | <a href="https://mp.weixin.qq.com/s/WXqZsl0a-WUCkJEvkZ8S7w">Link</a> | 是不是可以Prompting Engineering in Finance: A Survey？ |
| 6 | AI洞察笔记 | 一文汇总大语言模型LLM所有prompt提示词框架的论文出处 | <a href="https://mp.weixin.qq.com/s/6l1UBJ8xYhDV2ewQAQOZgw">Link</a> | **Reasoning论文汇总与arXiv两个技巧** |
| 7 | AIwithGary | 第三篇：要真正入门AI，OpenAI的官方Prompt工程指南肯定还不够，您必须了解的强大方法论和框架！！！ | <a href="https://mp.weixin.qq.com/s/R71hfmNAnMghvH89e_Tmww">Link</a> |  |

### Other
|序号|博主|名称|链接|备注|
|-|-|-|-|-|
| 1 | 老刘说NLP | 再看业界大模型行业问答的困难及若干业界实践：兼看智能客服常用路线及多场景prompt | <a href="https://mp.weixin.qq.com/s/dQ35J5eg5Cq7rY7zaa6wrw">Link</a> |  |
| 2 | 老刘说NLP | 大模型微调数据质量评价 | <a href="https://mp.weixin.qq.com/s/ZEzc1VaXFaR7M0zXNRWfwQ">Link</a> |  |
| 3 | 老刘说NLP | 垂域微调大模型非最全汇总：12大领域、57个领域微调模型概述及对垂直行业问答的一些讨论 | <a href="https://mp.weixin.qq.com/s/ur47_5Zx9IQUUduciEO3jQ">Link</a> |  |
| 4 | 哈工大SCIR实验室 | 赛尔笔记：面向表格数据的大模型推理综述 | <a href="https://mp.weixin.qq.com/s/sXeyH2Ob8-CbGwHHBYOYfQ">Link</a> |  |
| 5 | 机器之心 | 字节跳动李航：对语言大模型的若干观察和思考 | <a href="https://mp.weixin.qq.com/s/0I-y1dGM08n8KF1Kwv2diw">Link</a> | 李航：LLM思考 |
| 6 | 何枝 | 从零详细地梳理一个完整的 LLM 训练流程 | <a href="https://mp.weixin.qq.com/s/Et2NAwAzg2iHrpjDgsx-Hg">Link</a> |  |
| 7 | 人工智能前沿讲习 | LangChain介绍 | <a href="https://mp.weixin.qq.com/s/r5w69f_2jYAkBqCRG-RVpA">Link</a> |  |
| 8 | 运筹OR帷幄 | **机器学习模型可解释性综述** | <a href="https://mp.weixin.qq.com/s/Jmm84eYrtlfFLuQaWcAZCA">Link</a> |  |
| 9 | PaerWeekly | 大语言模型Fine-tuning踩坑经验之谈 | <a href="https://mp.weixin.qq.com/s/Aa8jYs4xgcI4clwie-wO1g">Link</a> | 微调经验 |
| 10 | 银融时代 | ChatGPT+金融：国外八大应用案例 | <a href="https://mp.weixin.qq.com/s/v2HLfBCreHqPYJW47VNZaQ">Link</a> |  |
| 11 |  |  | <a href="https://mp.weixin.qq.com/s/Se3-DNOtOGTZnWy3BTGX8g">Link</a> | **有趣的新闻：字节调用OpenAI** |
| 12 |  |  | <a href="https://mp.weixin.qq.com/s/xj2h7kVAm9VV7GPQF4lTDQ">Link</a> | **有趣的新闻：Gemini调用文心一言** |
| 13 | 海外独角兽 | 专访月之暗面杨植麟：lossless long context is everything | <a href="https://mp.weixin.qq.com/s/UMY0qZsCGh87KnW4wjfvoA">Link</a> | 月之暗面Moonshot AI对LLM前景的看法：①注重用户数据scaling的提升、而不是base model；②**可解释性**：只要哦数据量够大，肯定可以解决；③**历史上所有的架构演进本质上都是在提升有效的 context length**。word2vec 最近拿了 NeurIPS 的 Test of Time 奖。它在 10 年前用一个词去预测周围的词，相当于 context length 是 5。RNN 把有效的 context length 提升到了 20。LSTM 涨到大几十。transformer 到了几千。现在我们能做到几十万。**如果你有 10 亿的 context length，今天看到的问题都不是问题**；④未来模型基于**自我生成的数据**进行训练是关键；⑤**模型的微调可能不存在**：终究能达成，用户只需要指令的方式就能实现个性化的应用；⑤**人才的经验很重要** |
| 14 | AI算法科研 | **如何将大模型与小模型结合？这8种常用策略必看！附17篇案例论文和代码** | <a href="https://mp.weixin.qq.com/s/_9NLa0wZPVq_0Pu0a-jQlg">Link</a> |  |
| 15 | 麦哲智界 | **大模型如何改变金融行业** | <a href="https://mp.weixin.qq.com/s/2XIWJfek6y6t8cQ2bHs9cg">Link</a> |  |
| 16 | 腾讯研究院 | AI Agent，为什么是AIGC最后的杀手锏？ | <a href="https://mp.weixin.qq.com/s/DA3oNdu88LtM-BlqzGM03g">Link</a> | AI Agent简介 |
| 17 | 包包算法笔记 | 大模型微调数据选择和构造技巧 | <a href="https://mp.weixin.qq.com/s/Sf2erEthOZQ3IFMfHMdHKQ">Link</a> | **数据的多样性、不确定性** |
| 18 | 新智元 | **AI智能体卷爆大模型！AutoGPT等4大Agent打擂，「西部世界」谁将成为软件2.0？** | <a href="https://mp.weixin.qq.com/s/b04F8oQfRaY2z-FjzA4pMw">Link</a> | **对于Agent的全面介绍** |
| 19 | InfoQ | **金融业采用大模型，是“用大炮轰蚊子”吗** | <a href="https://mp.weixin.qq.com/s/g0e3qVqNzPVnUovGdYBPew">Link</a> |  |
| 20 | InfoQ | **开源金融业大模型，终结“专业打工人”？** | <a href="https://mp.weixin.qq.com/s/rL73Cz72fWYtUb7uBNAIqg">Link</a> | **对目前Github上开源的金融LLM总结** |
| 21 | NLP工作站 | 1-2B参数规模大模型使用心得及模型汇总 | <a href="https://mp.weixin.qq.com/s/Jnc3fhd-jf0XK4b9PrbZzg">Link</a> |  |
| 22 | NLP工作站 | 回望做大模型一年后的感悟 | <a href="https://mp.weixin.qq.com/s/CfAY8FCrQKKIrQx3U10EcQ">Link</a> |  |
| 23 | NewBeeNLP | **LLM 盛行，如何优雅地训练大模型？** | <a href="https://mp.weixin.qq.com/s/hpdGB-2oNH4R8j0zuPj7hA">Link</a> |  |
| 24 | 中国信通院 | **乘上大语言模型的东风：探究国内金融大模型的发展与生态运营策略** | <a href="https://mp.weixin.qq.com/s/ToVQ-KFwJCv5xzkBZ_3-Dw">Link</a> | 总结了截至2023-12-26的业界金融大模型 |
| 25 | 新智元 | 美国空军高调展示首个AI战斗机！部长亲自试驾全程未干预，10万行代码试飞21次 | <a href="https://mp.weixin.qq.com/s/u1cKkSZa5m9QzuchBkWieQ">Link</a> | **有趣的新闻** |
| 26 | AIGverse | OpenAI使用《金融时报》内容训练模型 | <a href="https://mp.weixin.qq.com/s/QB_QuI4n9OTnLt12ZBPC6w">Link</a> | **有趣的新闻**，<a href="https://aboutus.ft.com/press_release/openai">FT英文官网</a> |


## 个人博客/团队账号
|序号|博主|链接|备注|
|-|-|-|-|
| 1 | 徐明老师 | <a href="https://blog.csdn.net/mingzai624?type=blog">Link</a> |  |
| 2 | 老潘 | <a href="https://oldpan.me/">Link</a> |  |
| 3 | 苏剑林老师 | <a href="https://spaces.ac.cn/">Link</a> |  |
| 4 | 庞宇轩 | <a href="https://pyxblog.cn/">Link</a> |  |
| 5 | 人大AI BOX | <a href="https://www.zhihu.com/people/dou-hong-jian-44">Link</a> |  |
| 6 | 知乎——suc16 | <a href="https://www.zhihu.com/people/suc16/posts">Link</a> |  |
| 7 | Github——lucidrains | <a href="https://github.com/lucidrains?tab=repositories&q=&type=&language=&sort=stargazers">Link</a> |  |


## 电子书
|序号|来源|名称|链接|备注|
|-|-|-|-|-|
| 1 | 复旦张奇 | 大规模语言模型：从理论到实践 | <a href="https://intro-llm.github.io/">Link</a> |  |
| 2 | 刘聪NLP | ChatGPT原理与实战：大型语言模型的算法、技术和私有化 | <a href="https://github.com/liucongg/ChatGPTBook">Link</a> |  |
| 3 | 中国人工智能学会 | 中国人工智能系列白皮书——大模型技术（2023版） | <a href="https://caai.cn/index.php?s=/home/article/detail/id/3172.html">Link</a> |  |
| 4 | 人大赵鑫 | **大语言模型** | <a href="https://github.com/LLMBook-zh/LLMBook-zh.github.io">Link</a> | <a href="https://github.com/RUCAIBox/LLMBox">配套代码</a>，<a href="https://github.com/RUC-GSAI/YuLan-Chat">配套大模型Yulan</a> |


## Kaggle
|序号|名称|链接|备注|
|-|-|-|-|
| 1 | LLM Science Exam | <a href="https://www.kaggle.com/competitions/kaggle-llm-science-exam/leaderboard">Link</a> | <a href="https://mp.weixin.qq.com/s/tYIBHJ5zuiw-o1-DF0_Jow">中文复盘</a> |
| 2 | LLM Prompt Recovery | <a href="https://www.kaggle.com/competitions/llm-prompt-recovery/leaderboard">Link</a> |  |


## 其余来源
### Prompt Engineering
|序号|来源|名称|链接|备注|
|-|-|-|-|-|
| 1 | DAIR.AI(Democratizing Artificial Intelligence Research, Education, and Technologies) | **promptGuide** | <a href="https://www.promptingguide.ai/">Link</a> | **全面介绍提示工程的网站** |
| 2 | Medium | 12 Prompt Engineering Techniques | <a href="https://cobusgreyling.medium.com/12-prompt-engineering-techniques-644481c857aa">Link</a> | 12种提示方式的介绍（<a href="https://mp.weixin.qq.com/s/1qVhcCRmlYvGZcOe3W3r1Q">中文版</a>） |
| 3 | **OpenAI** | **Prompt Engineering官方文档** | <a href="https://platform.openai.com/docs/guides/prompt-engineering">Link</a> | <a href="https://mp.weixin.qq.com/s/jOU2qT5o88tuZC1p6vLkJw">中文简介</a> |
| 4 | **微软** | **Prompt Engineering官方文档** | <a href="https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/advanced-prompt-engineering?pivots=programming-language-chat-completions#specifying-the-output-structure">Link</a> | <a href="https://mp.weixin.qq.com/s/luovRT3AJJd93LhjpxeYRA">中文简介</a> |

### Other
|序号|来源|名称|链接|备注|
|-|-|-|-|-|
| 1 | Paper Digest（一个文献集中网站） |  | <a href="https://www.paperdigest.org/2023/01/recent-papers-on-chatgpt/">Link</a> | ChatGPT文章集合 |
| 2 | arXiv | Language Models Represent Space and Time | <a href="https://arxiv.org/abs/2310.02207">Link</a> | 大语言模型对于世界的理解（<a href="https://mp.weixin.qq.com/s/WaPqsPI4sCdEZoeID0cdew">中文解释</a>） |
| 3 | 徐明老师 | **NLP大模型微调答疑** | <a href="https://blog.csdn.net/mingzai624/article/details/130735366?spm=1001.2014.3001.5502">Link</a> |  |
| 4 | Microsoft | State of GPT | <a href="https://build.microsoft.com/en-US/sessions/db3f4859-cd30-4445-a0cd-553c3304f8e2">Link</a> |  |
| 5 | CSDN | 一文看懂学习率Learning Rate，从入门到CLR | <a href="https://blog.csdn.net/u012526436/article/details/90486021">Link</a> |  |
| 6 | Oldpan个人博客 | **关于训练神经网路的诸多技巧Tricks(完全总结版)** | <a href="https://oldpan.me/archives/how-to-use-tricks-to-train-network">Link</a> |  |
| 7 | **腾讯云** | **Prompt、RAG、微调还是重新训练？选择正确的生成式 AI 的方法指南** | <a href="https://cloud.tencent.com/developer/article/2313660">Link</a> | **从回答准确性、实施复杂性、维护成本、所需要投入的努力、灵活应对变化的能力5个方面对prompt engineering, RAG, fine-tune, pre-training 4种应用LLM的方式进行了对比** |
| 8 | **Ilya Sutskever** | Ilya 30u30 | <a href="https://arc.net/folder/D0472A20-9C20-4D3F-B145-D2865C0A9FEE">Link</a> | OpenAI 联合创始人兼首席科学家 Ilya Sutskever 整理的机器学习研究文章清单 |


## 论文
### 发表在顶刊or会计、金融领域期刊上的
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | **FinBERT: A Large Language Model for Extracting Information from Financial Text** | **Contemporary Accounting Research（ABS 4）** |  | <a href="https://onlinelibrary.wiley.com/doi/10.1111/1911-3846.12832">Link</a> | 英文语料库上预训练的BERT |
| 2 | GPT has become financially literate: Insights from financial literacy tests of GPT and a preliminary test of how people use it as a source of advice | Financial Research Letters（ABS 2） |  | <a href="https://www.sciencedirect.com/science/article/pii/S1544612323007055">Link</a> |  |
| 3 | ChatGPT for (Finance) research: The Bananarama Conjecture | Financial Research Letters（ABS 2） |  | <a href="https://www.sciencedirect.com/science/article/pii/S1544612323000363">Link</a> |  |
| 4 | **Generative AI for Economic Research: Use Cases and Implications for Economists** | **Journal of Economic Literature（ABS 4）** |  | <a href="https://www.dropbox.com/scl/fi/kk6duothtufsa8dhs3yat/LLMs_final.pdf?rlkey=bfadp97ej13ruceggecfeeiyi&dl=0">Link</a> | LLM如何应用于经济学研究 |

### 综述类
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | **Large Language Models: A Survey** | arXiv | 人大 | <a href="https://github.com/RUCAIBox/LLMSurvey">Link</a> | **LLM综述** |
| 2 | Harnessing the Power of LLMs in Practice: A Survey on ChatGPT and Beyond | arXiv | Amazon & 德州农工大学 & 莱斯大学 | <a href="https://github.com/Mooler0410/LLMsPracticalGuide">Link</a> | LLM综述 |
| 3 | **A Survey of Chain of Thought Reasoning: Advances, Frontiers and Future** | arXiv | 哈工大 | <a href="https://arxiv.org/abs/2309.15402">Link</a> | **思维链综述** |
| 4 | A Survey on Hallucination in Large Language Models: Principles, Taxonomy, Challenges, and Open Questions | arXiv |  | <a href="https://arxiv.org/abs/2311.05232">Link</a> | 大模型幻觉综述 |
| 5 | Evaluating Large Language Models: A Comprehensive Survey | arXiv | 天大 | <a href="https://arxiv.org/abs/2310.19736">Link</a> | 大模型评价方法综述 |
| 6 | Challenges and Applications of Large Language Models | arXiv |  | <a href="https://arxiv.org/abs/2307.10169">Link</a> | 大模型的应用和挑战 |
| 7 | **Explainability for Large Language Models: A Survey** | arXiv | 新泽西理工学院、约翰霍普金斯大学等 | <a href="https://arxiv.org/abs/2309.01029">Link</a> | **大模型可解释性综述** |
| 8 | **Is Prompt All You Need? No. A Comprehensive and Broader View of Instruction Learning** | arXiv |  | <a href="https://arxiv.org/abs/2303.10475">Link</a> | **Instruction Tuning综述** |
| 9 | Large Language Models on Graphs: A Comprehensive Survey | arXiv | 伊利诺伊大学厄巴纳香槟分校 | <a href="https://arxiv.org/abs/2312.02783">Link</a> | 图与LLM综述 |
| 10 | Data Management For Large Language Models: A Survey | arXiv | 北大 | <a href="https://arxiv.org/abs/2312.01700">Link</a> | LLM数据管理综述 |
| 11 | Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents | arXiv |  | <a href="https://arxiv.org/abs/2311.11797">Link</a> | 思维链与AI Agent综述 |
| 12 | Efficient Large Language Models: A Survey | arXiv |  | <a href="https://arxiv.org/abs/2312.03863">Link</a> | 提高LLMs的计算效率和资源利用效率综述（<a href="https://mp.weixin.qq.com/s/_CS5qcCO_86AMoj0GnmmUw">中文推荐</a>） |
| 13 | The Rise and Potential of Large Language Model Based Agents: A Survey | arXiv | 复旦NLP | <a href="https://arxiv.org/abs/2309.07864">Link</a> | 大模型Agent综述 |
| 14 | A Survey of Reasoning with Foundation Models | arXiv | 港大、华为Nuah等 | <a href="https://arxiv.org/abs/2312.11562">Link</a> | 大模型推理综述（<a href="https://mp.weixin.qq.com/s/HK29hRpMiblDntA6MB72Pw">中文推荐</a>） |
| 15 | A Survey on Statistical Theory of Deep Learning: Approximation, Training Dynamics, and Generative Models | arXiv | UCLA | <a href="https://arxiv.org/abs/2401.07187">Link</a> | 深度学习统计理论综述（<a href="https://mp.weixin.qq.com/s/8gl3bcRkysJrW2ds14W0iA">中文推荐</a>） |
| 16 | Pythia: A Suite for Analyzing Large Language Models Across Training and Scaling | arXiv | Eleuther AI、耶鲁 | <a href="https://arxiv.org/abs/2304.01373">Link</a> | 大模型训练手册（<a href="https://mp.weixin.qq.com/s/uLIzc2fRUY4T232tqHyo5Q">中文推荐</a>） |
| 17 | TrustLLM: Trustworthiness in Large Language Models | arXiv |  | <a href="https://arxiv.org/abs/2401.05561">Link</a> | 可信任性综述 |
| 18 | **A Systematic Survey of Prompt Engineering in Large Language Models: Techniques and Applications** | arXiv | 印度理工学院、斯坦福、Amazon | <a href="https://arxiv.org/abs/2402.07927">Link</a> | **Prompt Engineering综述（<a href="https://mp.weixin.qq.com/s/va1Ua3koedNWKkln4v6Vvg">中文推荐</a>）** |

### 技术类
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | **Attention Is All You Need** | arXiv |  | <a href="https://arxiv.org/abs/1706.03762">Link</a> | **Transformer** |
| 2 | Improving Language Understanding by Generative Pre-Training | arXiv |  | <a href="https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf">Link</a> | GPT-1 |
| 3 | **A Survey of Chain of Thought Reasoning: Advances, Frontiers and Future** | arXiv |  | <a href="https://arxiv.org/abs/1810.04805">Link</a> | **BERT** |
| 4 | Language Models are Unsupervised Multitask Learners | arXiv |  | <a href="https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf">Link</a> | GPT-2 |
| 5 | Language Models are Few-Shot Learners | arXiv |  | <a href="https://arxiv.org/abs/2005.14165">Link</a> | GPT-3 |
| 6 | White-Box Transformers via Sparse Rate Reduction: Compression Is All There Is? | arXiv |  | <a href="https://arxiv.org/abs/2311.13110">Link</a> | 白盒Transformer |
| 7 | **Distilling the Knowledge in a Neural Network** | arXiv |  | <a href="https://arxiv.org/abs/1503.02531">Link</a> | **知识蒸馏的开山之作** |
| 8 | A Simple, Effective, and Efficient Reinforcement Learning Method for Aligning Large Language Models | arXiv |  | <a href="https://arxiv.org/abs/2310.10505">Link</a> | ReMax |
| 9 | Beyond Human Data: Scaling Self-Training for Problem-Solving with Language Models | arXiv |  | <a href="https://arxiv.org/abs/2312.06585">Link</a> | 大模型自我构建数据进行训练 |
| 10 | PowerInfer: Fast Large Language Model Serving with a Consumer-grade GPU | arXiv | 上交 | <a href="https://arxiv.org/abs/2311.11797">Link</a> | 使用RTX 4090跑175B大模型 |
| 11 | StructGPT: A General Framework for Large Language Model to Reason over Structured Data | arXiv |  | <a href="https://arxiv.org/abs/2305.09645">Link</a> | 面向结构化数据的大模型推理框架 |

### 领域大模型构建
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | FinPT: Financial Risk Prediction with Profile Tuning on Pretrained Foundation Models | arXiv | 港大 & 达摩院 | <a href="https://arxiv.org/abs/2308.00065">Link</a> | 金融风险大模型FinPT |
| 2 | BloombergGPT: A Large Language Model for Finance | arXiv | 彭博社 | <a href="https://arxiv.org/abs/2303.17564">Link</a> | 金融大模型BloombergGPT |
| 3 | XuanYuan 2.0: A Large Chinese Financial Chat Model with Hundreds of Billions Parameters | arXiv | 度小满 | <a href="https://arxiv.org/abs/2305.12002">Link</a> | 金融大模型“轩辕” |
| 4 | ChatLaw: Open-Source Legal Large Language Model with Integrated External Knowledge Bases | arXiv | 北大 | <a href="http://arxiv.org/abs/2306.16092">Link</a> | 法律大模型ChatLaw |
| 5 | Instruct-FinGPT: Financial Sentiment Analysis by Instruction Tuning of General-Purpose Large Language Models | arXiv | 哥大 | <a href="http://arxiv.org/abs/2306.12659">Link</a> | 金融大模型Instruct-FinGPT |
| 6 | FinGPT: Open-Source Financial Large Language Models | arXiv | 哥大 | <a href="https://arxiv.org/abs/2306.06031">Link</a> | 金融大模型FinGPT |
| 7 | FinGPT: Democratizing Internet-scale Data for Financial Large Language Models | arXiv | 哥大 | <a href="https://arxiv.org/abs/2307.10485">Link</a> | 金融大模型FinGPT |
| 8 | FinVis-GPT: A Multimodal Large Language Model for Financial Chart Analysis | arXiv | 哈工深 | <a href="https://arxiv.org/abs/2308.01430">Link</a> | 金融大模型FinVisGPT（多模态） |
| 9 | CFGPT: Chinese Financial Assistant with Large Language Model | arXiv | 同济 & 上海AI实验室 | <a href="https://arxiv.org/abs/2309.10654">Link</a> | 金融大模型CFGPT |
| 10 | DISC-FinLLM: A Chinese Financial Large Language Model based on Multiple Experts Fine-tuning | arXiv | 复旦大学 | <a href="https://arxiv.org/abs/2310.15205">Link</a> | 金融资讯大模型DISC-FinLLM |
| 11 | PIXIU: A Large Language Model, Instruction Data and Evaluation Benchmark for Finance | arXiv | 武汉大学、中山大学等 | <a href="https://arxiv.org/abs/2306.05443">Link</a> | 金融大模型PIXIU |
| 12 | Data-Centric Financial Large Language Models | arXiv | 阿里巴巴、弗吉尼亚大学 | <a href="http://arxiv.org/abs/2310.17784">Link</a> | 金融大模型FLLM |
| 13 | BBT-Fin: Comprehensive Construction of Chinese Financial Domain Pre-trained Language Model, Corpus and Benchmark | arXiv | 复旦等 | <a href="http://arxiv.org/abs/2302.09432">Link</a> | 金融大模型Fin-T5 |

### 数据集构建
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | Chinese Fine-Grained Financial Sentiment Analysis with Large Language Models | arXiv |  | <a href="https://arxiv.org/abs/2306.14096">Link</a> | 中文金融情感分析数据集 |
| 2 | An Effective Data Creation Pipeline to Generate High-quality Financial Instruction Data for Large Language Model | arXiv | 哈工深 | <a href="https://arxiv.org/abs/2308.01415">Link</a> | 金融指令调优数据集 |
| 3 | ConvFinQA: Exploring the Chain of Numerical Reasoning in Conversational Finance Question Answering | arXiv |  | <a href="http://arxiv.org/abs/2210.03849">Link</a> | ConvFinQA |

### 思维链与大模型推理
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models** | avXiv |  | <a href="https://arxiv.org/abs/2201.11903">Link</a> | CoT开山之作 |
| 2 | **Large Language Models are Zero-Shot Reasoners** | avXiv |  | <a href="http://arxiv.org/abs/2205.11916">Link</a> | Zero-shot-CoT |
| 3 | **Self-Consistency Improves Chain of Thought Reasoning in Language Models** | avXiv |  | <a href="https://arxiv.org/abs/2203.11171">Link</a> | CoT的早期发展：自洽性 |
| 4 | **Least-to-Most Prompting Enables Complex Reasoning in Large Language Models** | avXiv |  | <a href="https://arxiv.org/abs/2205.10625">Link</a> | CoT的又一发展（复杂任务分解） |
| 5 | **Large Language Models Are Reasoning Teachers** | avXiv |  | <a href="http://arxiv.org/abs/2212.10071">Link</a> | 利用大模型的CoT能力帮助小模型进行推理 |
| 6 | **Symbolic Chain-of-Thought Distillation: Small Models Can Also "Think" Step-by-Step** | avXiv |  | <a href="https://arxiv.org/abs/2306.14050">Link</a> | 利用大模型的CoT能力帮助小模型进行推理2号 |
| 7 | **Large Language Models Can Self-Improve** | avXiv |  | <a href="https://arxiv.org/abs/2210.11610">Link</a> | 自我改进 |
| 8 | Self-Refine: Iterative Refinement with Self-Feedback | avXiv |  | <a href="https://arxiv.org/abs/2303.17651">Link</a> | 自我反思 |
| 9 | Reflexion: Language Agents with Verbal Reinforcement Learning | avXiv |  | <a href="https://arxiv.org/abs/2303.11366">Link</a> | 自我反思2 |
| 10 | **Distilling Step-by-Step! Outperforming Larger Language Models with Less Training Data and Smaller Model Sizes** | avXiv |  | <a href="https://arxiv.org/abs/2305.02301">Link</a> | 服了，怎么跟我这个RAL这么类似 |
| 11 | **Self-explaining AI as an alternative to interpretable AI** | avXiv |  | <a href="https://arxiv.org/abs/2002.05149">Link</a> | 自我解释 |
| 12 | **Beyond Classification: Financial Reasoning in State-of-the-Art Language Models** | avXiv |  | <a href="https://arxiv.org/abs/2305.01505">Link</a> | 金融推理问题数据集构建 |
| 13 | Cumulative Reasoning with Large Language Models | avXiv |  | <a href="http://arxiv.org/abs/2308.04371">Link</a> | 姚期智首篇LLM |
| 14 | **Learning From Mistakes Makes LLM Better Reasoner** | avXiv |  | <a href="https://arxiv.org/abs/2310.20689">Link</a> | 让大模型在错题中学习 |
| 15 | Specializing Smaller Language Models towards Multi-Step Reasoning | avXiv |  | <a href="http://arxiv.org/abs/2301.12726">Link</a> |  |
| 16 | Self-Discover: Large Language Models Self-Compose Reasoning Structures | avXiv | 南加州大学、谷歌DeepMind | <a href="https://arxiv.org/abs/2402.03620">Link</a> | **让大模型针对不同问题，提出特定的推理结构（<a href="https://mp.weixin.qq.com/s/HUW8MX2GhsdE3qFBvb1-Hg">中文解读</a>）** |
| 17 | The Impact of Reasoning Step Length on Large Language Models | arXiv |  | <a href="https://arxiv.org/abs/2401.04925">Link</a> | 推理步骤对大模型能力的影响（<a href="https://mp.weixin.qq.com/s/UgglOk-u6Qv3IrY6aWcarQ">中文解读</a>） |

### 大模型与表格数据
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | Table-GPT: Table-tuned GPT for Diverse Table Tasks | arXiv | 微软 | <a href="https://arxiv.org/abs/2310.09263">Link</a> |  |
| 2 | Trompt: Towards a Better Deep Neural Network for Tabular Data | arXiv | 国立成功大学 | <a href="http://arxiv.org/abs/2305.18446">Link</a> |  |

### 大模型与图
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | Think-on-Graph: Deep and Responsible Reasoning of Large Language Model on Knowledge Graph | arXiv |  | <a href="https://arxiv.org/abs/2307.07697">Link</a> | 大模型与知识图谱 |

### AI Agents
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus? | avXiv |  | <a href="http://arxiv.org/abs/2301.07543">Link</a> | ABM，模拟人类行为 |
| 2 | War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars | avXiv |  | <a href="https://arxiv.org/abs/2311.17227">Link</a> | 基于LLM的企业风险传染？基于大语言模型的多智能体仿真世界大战 |
| 3 | **Large Language Models Empowered Agent-based Modeling and Simulation: A Survey and Perspectives** | avXiv | 清华 | <a href="https://arxiv.org/abs/2312.11970">Link</a> | 对ABM和LLM的综述 |
| 4 | Generative Agents: Interactive Simulacra of Human Behavior | avXiv |  | <a href="https://arxiv.org/abs/2304.03442">Link</a> | 让大模型玩模拟人生 |

### 技术报告
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | Gemini: A Family of Highly Capable Multimodal Models |  | 谷歌 | <a href="https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf">Link</a> | Gemini |
| 2 | Phi-2: The surprising power of small language models |  | 微软 | <a href="https://www.microsoft.com/en-us/research/blog/phi-2-the-surprising-power-of-small-language-models/">Link</a> | Phi2 |

### Prompting Engineering
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | **Can Generalist Foundation Models Outcompete Special-Purpose Tuning? Case Study in Medicine** | avXiv | 微软 | <a href="https://arxiv.org/abs/2311.16452">Link</a> | **医学领域使用GPT-4的prompt工程** |
| 2 | Principled Instructions Are All You Need for Questioning LLaMA-1/2, GPT-3.5/4 | avXiv |  | <a href="https://arxiv.org/abs/2312.16171">Link</a> |  |

### 大模型与主题模型
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | **TopicGPT: A Prompt-based Topic Modeling Framework** | avXiv |  | <a href="https://arxiv.org/abs/2311.01449">Link</a> | **<a href="https://mp.weixin.qq.com/s/vpnTiA5t3xis49NpZRNgpA">中文概述</a>** |
| 2 | **Prompting Large Language Models for Topic Modeling** | avXiv |  | <a href="http://arxiv.org/abs/2312.09693">Link</a> | **<a href="https://mp.weixin.qq.com/s/sbo9FmGgfyjy9QVbVeHn0Q">中文概述</a>** |

### Other
|序号|题目|期刊|机构|网址|简介|
|-|-|-|-|-|-|
| 1 | GPT-Fathom: Benchmarking Large Language Models to Decipher the Evolutionary Path towards GPT-4 and Beyond | avXiv |  | <a href="https://arxiv.org/abs/2309.16583">Link</a> | OpenAI进化之路与大模型能力来源探析（<a href="https://mp.weixin.qq.com/s/-AWkDzAzoyQNmgYXuC6B4w">中文解读</a>） |
| 2 | Can large language models provide useful feedback on research papers? A large-scale empirical analysis | avXiv | 斯坦福 | <a href="https://arxiv.org/abs/2310.01783">Link</a> | 大模型与审稿（<a href="https://mp.weixin.qq.com/s/9-F6cC9nB5kPO9rBBVmBuw">中文解读</a>） |
| 3 | When ChatGPT is gone: Creativity reverts and homogeneity persists | avXiv | 北京大学 | <a href="https://arxiv.org/abs/2401.06816">Link</a> | 大模型对长期创新能力的抑制（<a href="https://mp.weixin.qq.com/s/uQAubTdgaPmhbQbC6dhMUg">中文解读</a>） |
| 4 | Resolving the Imbalance Issue in Hierarchical Disciplinary Topic Inference via LLM-based Data Augmentation | avXiv |  | <a href="https://arxiv.org/abs/2310.05318">Link</a> | 样本不均衡问题（<a href="https://mp.weixin.qq.com/s/1Y9gPKl2iFLBAUQ3lsjXHQ">中文解读</a>） |
| 5 | Segmented Harmonic Loss: Handling Class-Imbalanced Multi-Label Clinical Data for Medical Coding with Large Language Models | avXiv |  | <a href="https://arxiv.org/abs/2310.04595">Link</a> | 样本不均衡问题（<a href="https://mp.weixin.qq.com/s/1Y9gPKl2iFLBAUQ3lsjXHQ">中文解读</a>） |
| 6 | When Advanced AI Isn't Enough: Human Factors as Drivers of Success in Generative AI-Human Collaborations | SSRN |  | <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4738829">Link</a> | ChatGPT时代的人机交互对绩效的影响研究（<a href="https://mp.weixin.qq.com/s/j_k-_DQqs-nDCS8XRJMQ5Q">中文简介</a>） |


## Something Interesting Beside LLM
|序号|来源|名称|链接|备注|
|-|-|-|-|-|
| 1 | **复旦自然语言处理实验室** | **入组第一堂代码课** | <a href="https://github.com/FudanNLP/nlp-beginner">Link</a> |  |
| 2 | 知乎 | nlp研究生不会自己写代码怎么办 | <a href="https://www.zhihu.com/question/615441114">Link</a> |  |
| 3 | 知乎 | 小王同学在积累的Github学习资料 | <a href="https://github.com/AccumulateMore/CV">Link</a> |  |
| 4 | CSDN | SHAP：解释模型预测的通用方法 | <a href="https://blog.csdn.net/qq_40943760/article/details/123938209">Link</a> |  |
| 5 | 索尼 | SunoAI | <a href="https://www.suno.ai">Link</a> | **为你的朋友制作歌曲** |
| 6 | 小红书 | InstantID | <a href="https://instantid.github.io/">Link</a> | **不需要进行任何额外训练，就能得到一个既符合文本描述又保留个人身份特征的定制图像** |
| 7 | 字节跳动 | MagicVideo | <a href="https://magicvideov2.github.io/">Link</a> | **文字生成动图** |
| 8 | **Github骆昊** | **Python 100天从新手到大师** | <a href="https://github.com/jackfrued/Python-100-Days">Link</a> |  |
| 9 | Github | 国科大论文模板 | <a href="https://github.com/mohuangrui/ucasthesis">Link</a> |  |
| 10 | Github | **Project-based Learning** | <a href="https://github.com/practical-tutorials/project-based-learning">Link</a> |  |
| 11 | **Github李沐** | **跟李沐学AI** | <a href="https://github.com/mli/paper-reading">Link</a> |  |
