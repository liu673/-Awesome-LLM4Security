# Awesome-LLM4Security 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  
> 以下是关于使用NLP、KG、 GPT 进行网络安全模型研究的精选资源列表，包含模型/项目、论文、数据以及相关产品。

## 目录
- [简介](#简介)
- [资源列表](#资源列表)
  - [项目](#项目)
  - [论文](#论文)
  - [数据集](#数据集)
  - [相关产品](#相关产品)
  - [其他](#其他资源)
- [贡献](#贡献)
- [附录](#附录)
  - [许可证](#许可证)
  - [Stars History](#点赞历史)  


## 简介
这是一个精心整理的网络安全模型资源汇总，旨在为研究人员、工程师及安全爱好者提供一个全面的参考集合。本项目覆盖了模型/项目、学术论文、数据集以及相关产品信息，帮助你深入了解和应用网络安全领域的最新进展。 

## 资源列表

### 项目

| 名称                                            | 简介                                                         | 链接                                                         |
| ----------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| SecureBERT: CyberSecurity Language Model        | 专门为网络安全任务量身定制的专用语言模型。该存储库记录了 SecureBERT 在使用操作码序列对恶意软件样本进行分类方面的研究、开发和实施。 | [SecureBert_Malware-Classification](https://github.com/kaushik-42/SecureBert_Malware-Classification) |
| SecureBERT-NER                                  | 该模型用于从安全咨询文本中提取命名实体。专门针对网络安全文本进行训练的命名实体识别 (NER) 模型。它可以识别身份、安全团队、工具、时间、攻击等各种实体。 | [cybersecurity-ner](https://github.com/PriyankaMohan94/cybersecurity-ner) |
| ceg-afpm                                        | 用于使用LLM句子分类进行安全漏洞误报识别                      | [ceg-afpm](https://github.com/arigig/ceg-afpm)               |
| CVE2TTP                                         | 一种从网络安全文本资源中评估、注释和提取威胁信息的自动化方法，以在 SecureBERT 之上开发模型，将 CVE 分类为 TTP。 | [CVE2TTP](https://github.com/ehsanaghaei/CVE2TTP)            |
| SecureBERT                                      | 一种用于表示网络安全文本数据的特定领域语言模型。             | [SecureBERT](https://github.com/ehsanaghaei/SecureBERT)<br />[SecureBERT-plus](https://github.com/ehsanaghaei/SecureBERT-plus)<br />[SecureDeBERTa](https://github.com/ehsanaghaei/SecureDeBERTa)<br />[SecureGPT](https://github.com/ehsanaghaei/SecureGPT) |
| Finetuning_SecurityLLM                          | 基于BERT微调的网络威胁检测系统                               | [Finetuning_SecurityLLM](https://github.com/GeorgeNhj/Finetuning_SecurityLLM) |
| flipkart_project                                | 使用大型语言模型进行自动合规性监控（LLMs）”项目，利用 BERT 和 RoBERTa 等尖端LLMs技术的力量，彻底改变合规性监控和实施 | [flipkart_project](https://github.com/Gauriiikaaa/flipkart_project) |
| PentestGPT                                      | 支持 GPT 的渗透测试工具                                      | [PentestGPT](https://github.com/GreyDGL/PentestGPT)          |
| WhiteRabbitNeo                                  | 一个可用于进攻和防御网络安全的模型系列【包含7B、13B、33B】   | [WhiteRabbitNeo](https://huggingface.co/WhiteRabbitNeo)      |
| Whiterabbitneo-Pentestgpt                       | 将专门针对网络安全的开源模型whiterabbitneo和GPT 4的提示技术PentestGPT结合起来，让GPT 4进入hack the box用户的前1%，打造一个完全开放的渗透测试的源解决方案。 | [Whiterabbitneo-Pentestgpt](https://github.com/isamu-isozaki/whiterabbitneo-pentestgpt) |
| LATTE                                           | 结合LLM和程序分析的二进制污点分析引擎。结合LLMs来实现自动化的二进制污点分析。这克服了传统污点分析需要手动定制污点传播规则和漏洞检查规则的局限性 | [LATTE](https://github.com/puzhuoliu/LATTE)                  |
| AVScan2Vec                                      | 一种序列到序列自动编码器，可以将恶意文件的防病毒结果嵌入到向量中。然后，这些向量可用于下游 ML 任务，例如分类、聚类和最近邻查找。【将防病毒扫描报告转换为向量表示，有效处理大规模恶意软件数据集，并在恶意软件分类、聚类和最近邻搜索等任务中表现良好】 | [AVScan2Vec](https://github.com/boozallen/AVScan2Vec)        |
| PassGPT                                         | 一个针对密码泄露从头开始训练的 GPT-2 模型。利用 LLMs 的密码生成模型，引入了引导式密码生成，其中 PassGPT 的采样过程生成符合用户定义约束的密码。这种方法通过生成更多以前未见过的密码，优于利用生成对抗网络（GAN）的现有方法，从而证明了LLMs在改进现有密码强度估计器方面的有效性 | [PassGPT](https://github.com/javirandor/passgpt)             |
| pwned-by-passgpt                                | 使用 Have I Been Pwned (HIBP) 数据集进行密码破解研究，以评估 PassGPT 大型语言模型 (LLM) 的有效性。 | [pwned-by-passgpt](https://github.com/sean-t-smith/pwned-by-passgpt) |
| LLM Security 101                                | 深入LLM安全领域：进攻和防御工具的探索，揭示它们目前的能力。  | [LLM Security 101](https://github.com/Seezo-io/llm-security-101) |
| SecurityGPT                                     | 使用大型语言模型 (LLMs) 增强软件源代码中的安全错误报告 (SBR) 的分类。我们开发并微调了 LLMs 来解决识别代码中安全漏洞的关键任务。 | [SecurityGPT](https://github.com/Alexyskoutnev/SecurityGPT)  |
| ChatCVE                                         | 帮助组织分类和聚合 CVE（常见漏洞和暴露）信息。通过利用最先进的自然语言处理，ChatCVE 使每个人都可以访问详细的软件物料清单 (SBOM) 数据 | [ChatCVE](https://github.com/jasona7/ChatCVE)                |
| SecGPT                                          | SecGPT的目标是结合LLM，对网络安全进行更多贡献，包括渗透测试、红蓝对抗、CTF比赛和其他方面。汇总现有的插件功能，并通过AI进行决策。基于这些决策，它构建基础行为逻辑。然后，根据此逻辑，它调用本地插件功能，尝试完成网站渗透、漏洞扫描、代码审计和报告撰写等任务 | [SecGPT](https://github.com/ZacharyZcR/SecGPT)               |
| SecGPT-云起无垠                                 | 网络安全大模型。探索各种网络安全任务，漏洞分析、溯源分析、流量分析、攻击研判、命令解释、网安知识问答、高质量网络安全训练集、DPO强化学习 | [secgpt](https://github.com/Clouditera/secgpt)               |
| HackMentor                                      | 网络安全领域微调开源大语言模型，得到行业大模型HackMentor，研究工作主要分为三个部分：网络安全行业微调数据的构建、大语言模型的微调和对LLMs网络安全能力的评估。 | [HackMentor](https://github.com/tmylla/HackMentor)<br />[中科院信工所: HackMentor-面向网络安全领域的大语言模型微调](https://mp.weixin.qq.com/s/EnGdEm0p6cXrdk42yrB90w) |
| HackerGPT                                       | 用于网络应用程序黑客攻击的值得信赖的道德黑客LLM，针对网络和网络黑客攻击，使用的开源黑客工具进行黑客攻击。 | [HackerGPT](https://github.com/Hacker-GPT/HackerGPT-2.0)     |
| AutoAudit                                       | AutoAudit作为专门针对网络安全领域的大语言模型，其目标是为安全审计和网络防御提供强大的自然语言处理能力。它具备分析恶意代码、检测网络攻击、预测安全漏洞等功能，为安全专业人员提供有力的支持。 | [AutoAudit](https://github.com/ddzipp/AutoAudit)             |
| Agentic LLM                                     | 开源 Agentic LLM 漏洞扫描程序                                | [Agentic LLM](https://github.com/msoedov/agentic_security)   |
| Garak                                           | LLM 漏洞扫描器                                               | [Garak](https://github.com/leondz/garak)                     |
| ART                                             | 用于机器学习安全的 Python 库。ART 提供的工具使开发人员和研究人员能够评估、防御、认证和验证机器学习模型和应用程序，以抵御规避、中毒、提取和推理等对抗性威胁。 | [Adversarial Robustness Toolbox : document](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/)<br />[Adversarial Robustness Toolbox (ART) v1.17](https://github.com/Trusted-AI/adversarial-robustness-toolbox) |
| SourceGPT                                       | 构建在 ChatGPT 之上的源代码分析器和提示管理器（可做代码扫描） | [SourceGPT](https://github.com/NightmareLab/SourceGPT)       |
| ChatGPTScan                                     | 由 ChatGPT 提供支持的代码扫描                                | [ChatGPTScan](https://github.com/YulinSec/ChatGPTScanner)    |
| ChatGPT Code Analyzer                           | 利用ChatGPT 进行的代码分析器                                 | [chatgpt-code-analyzer](https://github.com/MilindPurswani/chatgpt-code-analyzer) |
| GPTLens                                         | 基于LLM的智能合约漏洞检测                                    | [GPTLens](https://github.com/AvijeetRanawat/GPTLens)         |
| Audit GPT                                       | 微调 GPT 以进行智能合约审计                                  | [Audit GPT](https://github.com/fuzzland/audit_gpt)           |
| VulChatGPT                                      | 使用 IDA PRO HexRays 反编译器和 OpenAI(ChatGPT) 来查找二进制文件中可能存在的漏洞 | [VulChatGPT](https://github.com/ke0z/vulchatgpt)             |
| Ret2GPT                                         | 利用 OpenAI API 的能力，RET2GPT 可以为二进制文件提供全面而详细的分析，使其成为 CTF Pwners 不可或缺的工具。 | [Ret2GPT](https://github.com/DDizzzy79/Ret2GPT)              |
| LLM-CodeSecurityReviewer                        | 使用 Ollama(LLM) 检查代码是否存在潜在的不良行为              | [LLM-CodeSecurityReviewer](https://github.com/t41372/LLM-CodeSecurityReviewer) |
| LLM-SOC                                         | 基于大语言模型的安全运营辅助增强工具，**RAG框架**（**目前只有README**） | [LLM-SOC](https://github.com/404notf0und/LLM-SOC)            |
| RagSecOps                                       | LLMs + **RAG** + CVEs + Security = SecAIOps                  | [RagSecOps](https://github.com/rcarrat-AI/ragsecops)         |
| FlipLogGPT                                      | 使用向量存储进行日志和安全分析的交互式LLM（**RAG框架**）     | [FlipLogGPT](https://github.com/adarshpalaskar1/FlipLogGPT_LLM) |
| pentestpal                                      | 不断发展的LLM驱动的工具，以协助渗透测试人员和安全研究人员（**RAG框架**） | [pentestpal](https://github.com/marklechner/pentestpal)      |
| Sovereign Chat                                  | FOSS AI 聊天机器人可以回答有关在线隐私和安全的所有问题（**RAG框架**）<br />[Chainlit](https://docs.chainlit.io/get-started/overview) + [Embedchain](https://github.com/embedchain/embedchain/tree/main) + [Ollama](https://ollama.com/) | [Sovereign Chat](https://github.com/Marconius-Solidus/Sovereign-Chat) |
| Q-A-bot                                         | 利用大型语言模型 （LLM） 功能与网络安全文档交互的个性化机器人。（**RAG框架**） | [Q-A-bot](https://github.com/sheshiisree/Q-A-bot)            |
| ZenGuard AI                                     | 将生产级、低代码 LLM（大型语言模型）护栏集成到其生成式 AI 应用程序中。【及时注入检测、越狱检测、个人身份信息检测、关键字检测等】 | [fast-llm-security-guardrails](https://github.com/ZenGuard-AI/fast-llm-security-guardrails) |
| cyber-security-llm-agents                       | 使用大型语言模型 (LLMs) 执行网络安全日常工作中常见任务的代理集合 | [cyber-security-llm-agents](https://github.com/NVISOsecurity/cyber-security-llm-agents) |
| Galah                                           | 一个 LLM（大型语言模型）驱动的 Web 蜜罐，目前与 OpenAI API 兼容，能够模仿各种应用程序和动态响应任意 HTTP 请求。（GO语言） | [Galah](https://github.com/0x4D31/galah)                     |
| CyberSecurityLLMTest                            | 测试（数据/提示）大型语言模型是否具有作为网络安全专家执行的能力 | [CyberSecurityLLMTest](https://github.com/ybdesire/CyberSecurityLLMTest) |
| OpenAI and FastAPI - Text summarization         | 一个基于 OpenAI 的 GPT-3.5 和 GPT-4 API 生成威胁情报摘要报告的工具 | [OpenAI and FastAPI - Text summarization](https://github.com/EC-DIGIT-CSIRC/openai-cti-summarizer) |
| Security LLaMA2 Fine-tuning                     | 利用LLama2进行微调安全领域                                   | [Security LLaMA2 Fine-tuning](https://github.com/KaitaoQiu/security_llm) |
| LLM-security                                    | ✨✨                                                           | [LLM-security](https://github.com/Anonymous1234343/LLM-security) |
| LLM_Security                                    | 利用RAG与ChatGPT结合实现LLM Security（**RAG框架**）          | [LLM_Security](https://github.com/BoB-Dev-Top30/LLM_Security) |
| LLM Security Chatbot                            | LLM 安全聊天机器人旨在帮助理解和研究网络安全研究。主要是 POC。该聊天机器人使用 Mistral 7B v1 构建，并使用 Streamlit 集成到用户友好的界面中，利用自然语言处理为广泛的安全问题提供深入的分析和潜在的缓解策略 | [LLM Security Chatbot](https://github.com/jwalker/llm_security_chatbot) |
| smartgrid-llm                                   | 在智能电网中实践大型语言模型的风险：威胁建模和验证           | [smartgrid-llm](https://github.com/jiangnan3/smartgrid-llm)  |
| AISploit                                        | AISploit 是一个 Python 包，旨在支持红队和渗透测试人员利用大型语言模型人工智能解决方案。它提供工具和实用程序来自动执行与基于人工智能的安全测试相关的任务。 | [AISploit ](https://github.com/hupe1980/aisploit)            |
| PyRIT                                           | 用于生成 AI 的 Python 风险识别工具 (PyRIT) 是一个开放访问自动化框架，使安全专业人员和机器学习工程师能够使用红队基础模型及其应用程序。 | [PyRIT](https://github.com/Azure/PyRIT)                      |
| Experiment AI Nutrition-Pro                     | 用于威胁建模和安全审查以及使用 OpenAI GPT-4 的研究项目       | [Experiment AI Nutrition-Pro](https://github.com/xvnpw/ai-nutrition-pro-design-gpt4) |
| SecurityGuardianAI                              | SecurityGuardianAI 是一款主动式云安全分析应用程序，旨在帮助识别云基础设施中的潜在安全威胁和漏洞。应用程序应该能够提供实时监控、分析和报告，以跟踪云服务器上可能发生的任何恶意活动【**实际没有用LLMs**】 | [SecurityGuardianAI](https://github.com/vps/SecurityGuardianAI) |
| Admyral                                         | 一款开源网络安全自动化和调查助手。网络安全自动化和调查助理   | [Admyral](https://github.com/Admyral-Security/admyral)       |
| Real-Time-Network-Traffic-Analysis-with-LLM-API | 使用大型语言模型 （LLM） API 进行实时网络流量分析。通过对 DNS 查询进行实时分析和分类，探索大型语言模型 （LLMs） 在网络安全方面的潜力 | [Real-Time-Network-Traffic-Analysis-with-LLM-API](https://github.com/FerdinandPaul/Real-Time-Network-Traffic-Analysis-with-LLM-API) |
| CVE2ATT-CK-LLM                                  | 一种利用LLM（大型语言模型）功能自动将 CVE 描述映射到 ATT&CK 技术的工具。旨在通过弥合漏洞和对抗性策略之间的差距来增强威胁情报和安全意识。 | [CVE2ATT-CK-LLM](https://github.com/vkeilo/CVE-2-ATT-CK-LLM) |
| MitreTagging                                    | 开发 MITRE ATT&CK 标记模型的项目，该模型采用安全发现、描述和分析，并使用适当的 ATT&CK 策略和技术对其进行标记 | [MitreTagging](https://github.com/Lifebloom-AI/MitreTagging) |
| CodeScanGPT                                     | 基于 GPT 和 OpenAI API 构建的实验性静态应用程序安全测试 （SAST） 扫描程序。 | [CodeScanGPT](https://github.com/chasepd/CodeScanGPT)        |


----------------------------------------

### 论文

| 名称                                                         | 时间                                    | 简介                                                         | 链接                                                         |
| ------------------------------------------------------------ | --------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ZeroLeak                                                     | 2023.8.24                               | LLMs来修复程序中的旁路漏洞                                   | [ZeroLeak: Using LLMs for Scalable and Cost Effective Side-Channel Patching](https://arxiv.org/abs/2308.13062) |
| Large Language Models in Cybersecurity: State-of-the-Art     | 2024.1.30                               | 对网络安全领域内的防御性和对抗性应用提供了全面的描述。       | https://arxiv.org/abs/2402.00891                             |
| CySecBERT: A Domain-Adapted Language Model for the Cybersecurity Domain | 2022.12.6                               | 一种基于 BERT的词嵌入模型，用于分析网络安全文本，专门针对网络安全领域定制的语言模型，它可以作为处理自然语言的网络安全系统的基本构建块。 | https://arxiv.org/abs/2212.02974                             |
| A survey on cybersecurity knowledge graph construction       | 2023.10.1                               | 网络安全知识图谱构建综述                                     | [网络安全知识图谱构建综述 - ScienceDirect --- A survey on cybersecurity knowledge graph construction - ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0167404823004340?via%3Dihub) |
| AttacKG: Constructing Technique Knowledge Graph from Cyber Threat Intelligence Reports | v1:2021.11.13<br />v2:2022.5.29         | AttacKG自动从CTI报告中提取结构化攻击行为图，并识别所采用的攻击技术。然后，我们汇总跨报告的网络威胁情报，以收集技术的不同方面，并将攻击行为图增强为技术知识图谱 （TKG） | https://arxiv.org/abs/2111.07093                             |
| EXTRACTOR: Extracting Attack Behavior from Threat Reports    | 2021.4.17                               | EXTRACTOR从CTI报告中精确地自动提取简明的攻击行为。EXTRACTOR 对文本不做任何强有力的假设，并且能够从非结构化文本中提取攻击行为作为来源图。 | https://arxiv.org/abs/2104.08618                             |
| TINKER: A framework for Open source Cyberthreat Intelligence | v1:2021.2.10<br />...<br />v6:2023.1.19 | 基于半监督开源知识图谱的框架 TINKER，用于捕获网络威胁信息及其上下文，生成网络威胁情报知识图谱（CTI-KG），并使用不同的用例演示其用法 | https://arxiv.org/abs/2102.05571                             |
| Cybersecurity knowledge graphs                               | 2023.4.29                               | 安全领域中使用的最著名的基于图的数据模型，以及定义正式网络知识表示中使用的概念和属性的知识组织系统，以获取有关实际系统或攻击的背景知识和特定专家知识。网络安全知识图如何支持机器学习并促进网络知识的自动推理 | [Cybersecurity knowledge graphs (springer.com)](https://link.springer.com/content/pdf/10.1007/s10115-023-01860-3.pdf)<br />[网络安全知识图谱](https://link.springer.com/article/10.1007/s10115-023-01860-3) |
| Recent Progress of Using Knowledge Graph for Cybersecurity   | 2022.7.22                               | 概述了网络安全知识图谱的核心概念、模式和构建方法。提供了有关信息提取和知识创建工作的相关数据集审查和开源框架，以帮助未来对网络安全知识图的研究。 | [Recent Progress of Using Knowledge Graph for Cybersecurity (semanticscholar.org)](https://pdfs.semanticscholar.org/df3e/68ea2190ab3de21a2eb6713b94462dbe9b1e.pdf?_gl=1*15u7ivz*_ga*MTA1ODcwNDYzLjE3MTUzOTgyOTY.*_ga_H7P4ZT52H5*MTcxNTQwNDM3Ny4yLjEuMTcxNTQwNDg1MC40Mi4wLjA.) |
| Looking Beyond IoCs: Automatically Extracting Attack Patterns from External CTI | v1:2022.11.1<br />v2:2023.7.11          | LADDER 是一个知识提取框架，可以从 CTI 报告中大规模提取基于文本的攻击模式。该框架通过捕获 Android 和企业网络中的攻击阶段来表征攻击模式，并将其系统地映射到 MITRE ATT\&CK 模式框架。安全分析师可以使用 LADDER 来确定与现有和新兴威胁相关的攻击向量的存在，使他们能够主动准备防御。【基准恶意软件数据集来训练未来的网络威胁情报模型】 | https://arxiv.org/abs/2211.01753                             |
| Constructing a Knowledge Graph from Textual Descriptions of Software Vulnerabilities in the National Vulnerability Database | v1:2023.4.30<br />v2:2023.5.15          | 根据国家漏洞数据库（NVD）中的信息构建漏洞知识图的新方法。使用神经模型、启发式规则和知识图嵌入的组合，将命名实体识别 (NER)、关系提取 (RE) 和实体预测结合起来，助修复用于网络安全的知识图中缺失的实体并评估性能。 | https://arxiv.org/abs/2305.00382                             |
| Cyber Threat Intelligence for SOC Analysts                   | 2023                                    | 从非结构化威胁分析报告中以不同粒度级别提取、集成和分析威胁情报的研究。 | [wosoc2023-23014-paper.pdf (ndss-symposium.org)](https://www.ndss-symposium.org/wp-content/uploads/2023/09/wosoc2023-23014-paper.pdf) |
| LLMs Perform Poorly at Concept Extraction in Cyber-security Research Literature | 2023.12.12                              | 名词提取器，并进行了一些统计分析，以从域中提取特定且相关的复合名词 | https://arxiv.org/abs/2312.07110                             |
| Revolutionizing Cyber Threat Detection with Large Language Models: A privacy-preserving BERT-based Lightweight Model for IoT/IIoT Devices | v1:2023.6.25<br />v2:2024.2.8           | SecurityBERT，这是一种利用来自转换器的双向编码器表示 （BERT） 模型进行物联网网络网络威胁检测的新型架构。SecurityBERT在识别14种不同的攻击类型方面取得了令人印象深刻的98.2%的总体准确率，超过了基于GAN转换器的架构和CNN-LSTM模型等混合解决方案之前创下的记录。平均 CPU 的推理时间不到 0.15 秒，紧凑的模型大小仅为 16 个。7MB，SecurityBERT非常适合实际流量分析，是部署在资源受限的物联网设备上的合适选择。 | https://arxiv.org/abs/2306.14263                             |
| A Framework for Cyber Threat Intelligence Extraction from Raw Log Data | 2019.11.1                               | 从原始日志数据中提取网络威胁情报的方法，并通过生成复杂系统行为的可检测模式来结合 IoC 和 TTP 的优势。采用日志数据异常检测来披露可疑的日志事件，这些事件用于迭代聚类、模式识别和细化。 | [2019_cyberhunt.pdf (skopik.at)](https://www.skopik.at/ait/2019_cyberhunt.pdf) |
| Attack Hypotheses Generation Based on Threat Intelligence Knowledge Graph | 2023.11.1                               | AttackDB，这是一个多级威胁知识库，它结合了来自多个威胁情报源的数据，将高级 ATT&CK 技术与行为恶意软件报告中发现的低级遥测技术相关联。提出了攻击假设生成器，它依赖于知识图遍历算法和各种链接预测方法，从一组可观察的工件中自动推断 ATT&CK 技术。 | [Attack Hypotheses Generation Based on Threat Intelligence Knowledge Graph](https://ieeexplore.ieee.org/document/10005832?denied=) |
| Machine learning on knowledge graphs for context-aware security monitoring | 2021.5.18                               | 机器学习在用于入侵检测的知识图谱上的应用，并通过实验评估了用于对工业系统中的异常活动进行评分的链路预测方法。经过最初的无监督训练后，所提出的方法被证明可以在各种场景中产生直观的、经过良好校准和可解释的警报，这暗示了知识图谱上的关系机器学习用于入侵检测的潜在好处。 | https://arxiv.org/abs/2105.08741                             |
| An Overview of Cybersecurity Knowledge Graphs Mapped to the MITRE ATT&CK Framework Domains | 2023.10.2                               | 关于当前网络安全知识图是否映射了主要 MITRE ATT&CK 矩阵的研究结果。 | [An Overview of Cybersecurity Knowledge Graphs Mapped to the MITRE ATT&CK Framework Domains](https://ieeexplore.ieee.org/document/10297134?denied=) |
| A review of knowledge graph application scenarios in cyber security | 2022.4.10                               | 简要概述了网络安全知识图谱的基本概念、模式和构建方法。       | https://arxiv.org/abs/2204.04769                             |
| Knowledge Graphs for Cybersecurity: A Framework for Honeypot Data Analysis | 2023.8.22                               | 使用知识图作为增强蜜罐数据分析的工具。介绍了从数据收集和预处理到知识图谱的创建及其后续分析的整个过程。支持复杂的查询分析，并提供对特定会话中攻击者命令的顺序和模式的洞察，以及源自特定 IP 地址的活动的摘要。然而，转换过程的适应性可能会根据源文档的特征而变化。 | [Knowledge Graphs for Cybersecurity: A Framework for Honeypot Data Analysis ](https://ieeexplore.ieee.org/document/10276627) |
| Infer the missing facts of D3FEND using knowledge graph representation learning | 2023.8.16                               | 提出一种使用链接预测任务来预测缺失事实的自动化方法，利用嵌入作为表示学习。有利于网络安全对策策略。 | [Infer the missing facts of D3FEND using knowledge graph representation learning ](https://www.emerald.com/insight/content/doi/10.1108/IJWIS-03-2023-0042/full/html) |
| Open-CyKG: An Open Cyber Threat Intelligence Knowledge Graph | 2021.12.5                               | Open-CyKG：一种开放网络威胁情报（CTI）知识图（KG）框架，该框架使用基于注意力的神经开放信息提取（OIE）模型构建，可从非结构化高级持续威胁中提取有价值的网络威胁信息（ APT）报告。 | [Open-CyKG：开放的网络威胁情报知识图 - ScienceDirect --- Open-CyKG: An Open Cyber Threat Intelligence Knowledge Graph - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0950705121007863?via%3Dihub) |
| K-CTIAA: Automatic Analysis of Cyber Threat Intelligence Based on a Knowledge Graph | 2023.1.12                               | K-CTIAA的自动CTI分析方法，它可以通过预训练的模型和知识图谱中从非结构化CTI中提取威胁行为。 | [K-CTIAA: Automatic Analysis of Cyber Threat Intelligence Based on a Knowledge Graph](https://www.mdpi.com/2073-8994/15/2/337) |
| CSKG4APT: A Cybersecurity Knowledge Graph for Advanced Persistent Threat Organization Attribution | 2023.6.1                                | 利用知识图谱技术，考虑网络威胁攻击归因的最新研究，深入研究OSCTI高级持续威胁（APT）知识图谱构建和应用过程中的关键相关技术和理论。 | [CSKG4APT: A Cybersecurity Knowledge Graph for Advanced Persistent Threat Organization Attribution ](https://ieeexplore.ieee.org/document/9834133?denied=) |
| Knowledge Graph Construction Research From Multi-source Vulnerability Intelligence | 2022.12.10                              | 以漏洞为核心，按照现有标准进行漏洞情报的知识抽取，建立对应的实体和关系，研究构建相关的、可视化的知识图谱，为漏洞情报的发现和发现提供支撑 | [多源漏洞情报知识图谱构建研究](https://link.springer.com/chapter/10.1007/978-981-19-8285-9_13) |
| SecTKG: A Knowledge Graph for Open-Source Security Tools     | 2023.8.14                               | SecTKG，用于开源安全工具的自动化知识图构建架构。是第一个构建大规模安全工具知识图谱的工作，包含400万个实体和1000万个关系 | [SecTKG: A Knowledge Graph for Open-Source Security Tools (hindawi.com)](https://www.hindawi.com/journals/ijis/2023/4464974/) |
| ThreatLand: Extracting Intelligence from Audit Logs via NLP methods | 2023.8.12                               | ThreatLand，这是一个可以自动从审核日志中提取高级情报和结构化威胁模式的系统。 | [ThreatLand: Extracting Intelligence from Audit Logs via NLP methods ](https://ieeexplore.ieee.org/document/10320173?denied=) |
| CSER: Enhancing Cybersecurity Entity Recognition Through Multidimensional Feature Fusion | 2023.12.15                              | 网络安全实体识别（CSER）模型                                 | [CSER: Enhancing Cybersecurity Entity Recognition Through Multidimensional Feature Fusion ](https://ieeexplore.ieee.org/document/10386941) |
| AnnoCTR: A Dataset for Detecting and Linking Entities, Tactics, and Techniques in Cyber Threat Reports | 2024.4.11                               | AnnoCTR，CC-BY-SA 许可的网络威胁报告数据集。链接到 MITRE ATT&CK 的先前数据集，为每个文档提供单个标签，在脱离上下文的情况下注释句子；数据集以更细粒度的方式注释整个文档。 | https://arxiv.org/abs/2404.07765                             |
| Joint contrastive learning and belief rule base for named entity recognition in cybersecurity | 2024.4.3                                | JCLB，将对比学习和信念规则库结合起来的新型模型，用于网络安全中的 NER。JCLB 结合 D-CMA-ES 算法，显着提高了网络安全中的 NER 准确性。 | [Joint contrastive learning and belief rule base for named entity recognition in cybersecurity ](https://cybersecurity.springeropen.com/articles/10.1186/s42400-024-00206-y) |
| A Span-based Multivariate Information-aware Embedding Network for joint relational triplet extraction of threat intelligence | 2024.4.1                                | 基于跨度的多元信息感知嵌入网络（SMIEN），用于联合提取威胁情报关系三元组 | [A Span-based Multivariate Information-aware Embedding Network for joint relational triplet extraction of threat intelligence](https://www.sciencedirect.com/science/article/abs/pii/S0950705124004635?via%3Dihub) |
| CyberEntRel: Joint extraction of cyber entities and relations using deep learning | 2024.1.1                                | 使用深度学习联合提取网络实体和关系。基于注意力的 RoBERTa-BiGRU-CRF 模型进行顺序标记。最后，在为两个预测实体匹配最合适的关系后，使用关系匹配技术提取关系三元组。 | [CyberEntRel：使用深度学习联合提取网络实体和关系 - ScienceDirect --- CyberEntRel: Joint extraction of cyber entities and relations using deep learning - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0167404823004893?via%3Dihub) |
| CDTier: A Chinese Dataset of Threat Intelligence Entity Relationships | 2023.10.1                               | 构建了中文CTI实体关系数据集——CDTier，其中包括：1）由100份CTI报告、3744个威胁句子和4259个威胁知识对象组成的威胁实体提取数据集； 2）用于实体关系提取的数据集，包括100个CTI报告、2598个威胁句子和2562个知识对象关系。 | [CDTier:中文威胁情报实体关系数据集 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/680587265)<br />[CDTier: A Chinese Dataset of Threat Intelligence Entity Relationships ](https://ieeexplore.ieee.org/document/10029930) |
| A framework for threat intelligence extraction and fusion    | 2023.9.1                                | 网络安全概念的联合实体和关系提取模型。威胁情报提取和融合的框架，该框架能够从结构化和非结构化数据中提取、关联和统一网络安全实体关系三元组。 | [威胁情报提取和融合的框架 - ScienceDirect --- A framework for threat intelligence extraction and fusion - ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S016740482300281X?via%3Dihub) |
| APTNER: A Specific Dataset for NER Missions in Cyber Threat Intelligence Field | 2022.5.4                                | 构建了一个名为 APTNER 的数据集，可用于 CTI 中的 NER 联合学习和多任务学习任务。除了 IP、URL、恶意软件、位置等常见标签之外，APTNER 还包含 21 个类别 | [APTNER: A Specific Dataset for NER Missions in Cyber Threat Intelligence Field ](https://ieeexplore.ieee.org/document/9776031?denied=) |
| Vulcan: Automatic extraction and analysis of cyber threat intelligence from unstructured text | 2022.5.1                                | 从非结构化文本中自动提取和分析网络威胁情报                   | [Vulcan：从非结构化文本中自动提取和分析网络威胁情报 - ScienceDirect --- Vulcan: Automatic extraction and analysis of cyber threat intelligence from unstructured text - ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0167404822001584?via%3Dihub) |
| DNRTI: A Large-scale Dataset for Named Entity Recognition in Threat Intelligence | 2020.12.1                               | 大规模威胁情报命名实体识别数据集（DNRTI）                    | [DNRTI: A Large-Scale Dataset for Named Entity Recognition in Threat Intelligence ](https://ieeexplore.ieee.org/document/9343158?denied=) |
| CTI View: APT Threat Intelligence Analysis System            | 2022.1.3                                | 面向海量非结构化网络空间威胁情报的文本提取和分析的新型自动化系统CTI View （CTI）由各个安全厂商发布。 | [CTI View: APT Threat Intelligence Analysis System ](https://www.semanticscholar.org/reader/456c6e1dc07cadfe0d0302a938aba2cebd673da3) |


### 数据集

| 名称                    | 简介                                                         | 链接                                                         |
| ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| FormAI Dataset          | AI 生成数据集，包含 112,000 个可编译且独立的 C 程序。数据集中的所有程序均由 GPT-3.5-turbo 使用动态零样本提示技术生成，并包含不同复杂程度的程序。一些程序处理复杂的任务，例如网络管理、桌面游戏或加密，而另一些程序则处理更简单的任务，例如字符串操作。每个程序都根据代码中存在的漏洞进行标记，使用基于高效 SMT 的有界模型检查器 (ESBMC) 的形式验证方法。该策略最终识别漏洞，而不会报告误报（由于存在反例）或漏报（达到一定限度）。标记的样本可用于训练大型语言模型（LLMs），因为它们包含软件漏洞的确切程序位置。 | [FormAI Dataset](https://github.com/FormAI-Dataset/FormAI-dataset) |
| security-paper-datasets | 网络安全数据集（427K Rows）                                  | [security-paper-datasets](https://huggingface.co/datasets/clouditera/security-paper-datasets) |
| cyber-security-llm-data | 红队的开源数据集、Meta 的 Bot Adversarial Dialog 数据集      | [cyber-security-llm-data](https://github.com/balavenkatesh3322/cyber-security-llm-list) |
| AnnoCTR                 | AnnoCTR 包含从商业 CTI 供应商获得的 400 份网络威胁报告。这些报告描述了与威胁相关的信息，例如战术、技术、参与者、工具和目标行业。这些报告由领域专家注释了命名实体、时间表达式和网络安全特定概念。这些注释包括提及组织、地点、行业部门、时间表达、代码片段、黑客团体、恶意软件、工具、策略和技术。 | https://github.com/boschresearch/anno-ctr-lrec-coling-2024   |
| CVTIKG                  | 具有23,636个关系三元组的初步威胁情报知识图（CVTIKG）         | https://github.com/wangxtz/CVTIKG                            |
| CDTier                  | 数据集主要分为两部分：实体抽取和关系抽取                     | https://github.com/MuYu-z/CDTier                             |
| APTNER                  | 为网络威胁情报 (CTI) 领域的 NER 任务提供新的数据集。我们定义了 21 种实体类型。 | https://github.com/wangxuren/APTNER                          |
| DNRTI                   | DNRTI-A-大规模数据集，用于威胁情报中的命名实体识别           | https://github.com/SCreaMxp/DNRTI-A-Large-scale-Dataset-for-Named-Entity-Recognition-in-Threat-Intelligence |
| AI Exploits             | 现实世界漏洞的漏洞利用和扫描模板的集合                       | https://github.com/protectai/ai-exploits                     |


### 相关产品

| 名称                           | 公司                       | 简介                                                         | 链接                                                         |
| ------------------------------ | -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Q-GPT安全机器人系统（QAX-GPT） | 奇安信                     | Q-GPT安全机器人系统（QAX-GPT）是面向网络安全领域的革命性产品，专为有大规模安全运营需求的政企客户设计。它充分发挥大语言模型的理解推理能力，通过机器智能模拟人类专家，实现海量告警研判、自动化调查、可执行任务生成。 | [奇安信Q-GPT安全机器人系统（QAX-GPT）](https://www.qianxin.com/product/detail/pid/496) |
| Microsoft 安全 Copilot         | 微软                       | 安全 Copilot 是一种 AI 网络安全产品，使安全专业人员能够快速响应网络威胁、像机器那样快速处理信号，并在数分钟内评估风险暴露。 | [Microsoft 安全 Copilot ](https://www.microsoft.com/zh-cn/security/business/ai-machine-learning/microsoft-copilot-security#Scenarios) |
| Vulnerability detection by AI  | Offective 360（Hacker AI） | Hacker AI 是一种人工智能解决方案，可扫描源代码以识别可能被黑客或恶意行为者利用的潜在安全漏洞。通过识别这些漏洞，组织可以采取措施解决问题并防止安全漏洞。 | [Hacker AI](https://hacker-ai.ai/#hacker-ai)                 |
| Firewall for AI                | Cloudflare                 | AI 防火墙，这是一个新的保护层，可在滥用和攻击到达之前将其识别出来。使用 LLM 的应用程序量身定制。其中将包括一组工具，供部署在应用程序前面，以检测漏洞并为模型所有者提供可见性。 | [AI 防火墙](https://www.cloudflare.com/zh-cn/lp/firewall-for-ai/)<br />[Cloudflare 宣布推出 Firewall for AI](https://blog.cloudflare.com/zh-cn/firewall-for-ai-zh-cn/) |
| AI-SPM                         | Wiz                        | 人工智能安全态势管理产品，旨在保护在软件开发过程中使用人工智能工具 | [Wiz成为第一个提供AI安全态势管理的CNAPP](https://www.wiz.io/blog/ai-security-posture-management) |
| GenAI-Powered Security Tools   | Fortinet                   | GenAI 为 Fortinet AI 增加了一个新维度，允许 SecOps 团队直接与 AI 系统交互，以增强威胁检测、分析和响应、生成报告、构建剧本以及修复易受攻击和受损的系统 | [Fortinet Advisor Applies the Power of GenAI to SecOps](https://www.fortinet.com/blog/business-and-technology/fortinet-advisor-applies-power-of-genai-to-secops) |
|                                |                            |                                                              |                                                              |

### 其他资源

- Github地址：[GPTSecurity](https://github.com/mo-xiaoxi/GPTSecurity)  |  GitBook地址：[GPTSecurity](https://www.gptsecurity.info/) 

  GPTSecurity是一个涵盖了前沿学术研究和实践经验分享的社区，集成了生成预训练 Transformer（GPT）、人工智能生成内容（AIGC）以及大型语言模型（LLM）等安全领域应用的知识。

- [安全人工智能系统开发指南](https://www.ncsc.gov.uk/collection/guidelines-secure-ai-system-development/introduction)

  适用于任何使用人工智能 (AI) 的系统提供商的指南，无论这些系统是从头开始创建的，还是构建在其他人提供的工具和服务之上的。

- [下一代网络安全应用程序：如何开发和部署 AI/ML、搜索和分析应用程序以转变企业网络安全](https://www.snowflake.com/next-generation-cybersecurity-applications/?utm_source=google&utm_medium=paidsearch&utm_campaign=na-us-en-nb-cybersecurity-phrase&utm_content=go-rsa-evg-eb-next-generation-cybersecurity-applications&utm_term=c-g-cyber%20security-p-684401030637&gad_source=1&gclid=CjwKCAjw9IayBhBJEiwAVuc3fqPNPtWoWA8ZagWFXFCV21LxC4l4S9xBoBT6CHLcNIuT1Wd_0sVqihoCvlkQAvD_BwE)

## 贡献

欢迎为这个列表做出贡献！你可以通过提交一个pull request来添加、修改或删除资源。在提交之前，请确保你遵循了以下准则：
- 确保资源的质量上乘，并且与网络安全模型的主题相关。
- 在添加资源时，请按照相应的分类进行排序，并保持列表的整洁。
- 提供资源的清晰描述，包括标题、链接以及简短的介绍。
如果你有任何疑问或建议，请随时通过GitHub的issue与我联系。

## 附录
### 许可证
本项目遵循 [MIT](LICENSE) 许可证

### 点赞历史
[![Star History Chart](https://api.star-history.com/svg?repos=liu673/Awesome-LLM4Security&type=Date)](https://star-history.com/#liu673/Awesome-LLM4Security&Date)

