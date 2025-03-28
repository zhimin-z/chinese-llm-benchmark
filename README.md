
# CLiB中文大模型能力评测榜单（持续更新）
- 目前已囊括208个大模型，覆盖chatgpt、gpt-4o、o3-mini、谷歌gemini、Claude3.5、智谱GLM-Zero、文心一言、qwen-max、百川、讯飞星火、商汤senseChat、minimax等商用模型，
以及DeepSeek-R1、qwq-32b、deepseek-v3、qwen2.5、llama3.3、phi-4、glm4、gemma3、mistral、书生internLM2.5等开源大模型。
- 模型来源涉及国内外大厂、大模型创业公司、高校研究机构。
- 支持多维度能力评测，包括医疗、教育、法律、行政公务、心理健康、推理与数学计算、语言与指令遵从等7个领域，以及细分的~300个维度（比如牙科、高中语文…）。
- 不仅提供排行榜，也提供规模超100万的大模型错题本！方便广大社区研究分析、改进大模型。

# 目录
- [🔄最近更新](#最近更新)
- [⚓TODO](#todo)
- [📝大模型基本信息](#大模型基本信息)
- [📊排行榜](#-排行榜)
  - [1、综合能力排行榜](#1综合能力排行榜)
    - [1.1 推理类模型排行榜](#11推理类模型排行榜)
    - [1.2 商用大模型排行榜（含开源模型的付费API）](#12商用大模型排行榜含开源模型的付费API)
      - 输出价格30元及以上
      - 输出价格5~30元
      - 输出价格1~5元
      - 输出价格1元以下
    - [1.3 开源大模型排行榜](#13开源大模型排行榜)
      - 5B以下
      - 5B~20B
      - 20B以上
  - [2、医疗排行榜](#2医疗排行榜)    
    - [2.1 医师考试/规培结业](#21-医师考试规培结业)
    - [2.2 医师考试/执业助理医师](#22-医师考试执业助理医师)
    - [2.3 医师考试/执业医师](#23-医师考试执业医师)
    - [2.4 医师考试/中级职称](#24-医师考试中级职称)
    - [2.5 医师考试/高级职称](#25-医师考试高级职称)
    - [2.6 护理考试](#26-护理考试)
    - [2.7 药师考试](#27-药师考试)
    - [2.8 医技考试](#28-医技考试)
    - [2.9 专业知识考试/基础医学](#29-专业知识考试基础医学)
    - [2.10 专业知识考试/临床医学](#210-专业知识考试临床医学)
    - [2.11 专业知识考试/预防医学与公共卫生学](#211-专业知识考试预防医学与公共卫生学)
    - [2.12 专业知识考试/中医学与中药学](#212-专业知识考试中医学与中药学)
    - [2.13 医学考研](#213-医学考研)
  - [3、教育排行榜](#3教育排行榜)
    - [3.1 高考](#31-高考)
    - [3.2 高中学科](#32-高中学科)
    - [3.3 初中学科](#33-初中学科)
    - [3.4 小学学科](#34-小学学科)
  - [4、法律排行榜](#4法律排行榜)
    - [4.1 律师资格考试](#41-律师资格考试)
  - [5、行政公务排行榜](#5行政公务排行榜)
    - [5.1 公务员考试](#51-公务员考试)
  - [6、心理健康排行榜](#6心理健康排行榜)
  - [7、推理与数学计算排行榜](#7推理与数学计算排行榜)
    - [7.1 演绎推理](#71-演绎推理)  
    - [7.2 常识推理](#72-常识推理)
    - [7.3 符号推理BBH](#73-符号推理BBH)
    - [7.4 算术能力](#74-算术能力)
    - [7.5 七八九年级数学](#75-七八九年级数学)
    - [7.6 表格问答](#76-表格问答)
    - [7.7 高中奥林匹克数学竞赛](#77-高中奥林匹克数学竞赛)
  - [8、语言与指令遵从排行榜](#8语言与指令遵从排行榜)
    - [8.1 成语理解](#81-成语理解)
    - [8.2 情感分析](#82-情感分析)  
    - [8.3 文本蕴含](#83-文本蕴含)
    - [8.4 分类能力](#84-分类能力)
    - [8.5 信息抽取](#85-信息抽取)
    - [8.6 阅读理解](#86-阅读理解)
    - [8.7 C3中文阅读理解](#87-C3中文阅读理解)
    - [8.8 代词理解CLUEWSC](#88-代词理解CLUEWSC)
    - [8.9 诗词匹配CCPM](#89-诗词匹配CCPM)
    - [8.10 中文指令遵从](#810-中文指令遵从)
- [🌐各项能力评分](#🌐各项能力评分)
- [⚖️原始评测数据](#⚖️原始评测数据)
- [为什么做榜单？](#为什么做榜单)
- [大模型选型及评测交流群](#大模型选型及评测交流群)

# 最近更新
- [2025/3/27] v3.11版本
  - 新增“医学考研”排行榜，并计入总分，详见[link](#213-医学考研)
  - “教育”领域所有子任务，剔除过于简单的测试样本，重新计算分数，总分也相应改变
- [2025/3/25] v3.10版本
  - 新增“高中奥林匹克数学竞赛”排行榜，并计入总分，详见[link](#77-高中奥林匹克数学竞赛)
  - “推理与数学计算”、“语言与指令遵从”剔除过于简单的测试样本，重新计算分数，总分也相应改变
- [2025/3/23] v3.9版本
  - 新增“专业知识考试/中医学与中药学”排行榜，并计入总分
  - “律师资格考试”排行榜新增“MMCU法律”子项
  - 新增5个模型：hunyuan-turbos-20250313、gemma-3-1b-it、gemma-3-4b-it、gemma-3-12b-it、ERNIE-4.5-8K-Preview
- [2025/3/21] 发布v3.8版本评测榜单
  - 新增“专业知识考试/预防医学与公共卫生学”、“心理健康”排行榜，并计入总分
- [2025/3/19] 发布v3.7版本评测榜单
  - 新增“专业知识考试/临床医学”排行榜（含医学影像学、放射学等22个方向），并计入总分，详见[link](#210-专业知识考试临床医学)
  - 高考排行榜新增政治学科，并增加大量考题，更新所有相关分数
- [2025/3/17] 发布v3.6版本评测榜单
  - 新增“专业知识考试/基础医学”排行榜（含病理生理学、医学心理学等17个方向），并计入总分，详见[link](#29-专业知识考试基础医学)
  - 新增2个模型：谷歌gemma-3-27b-it、Mistral-Small-24B-Instruct-2501
- [2025/3/15] 发布v3.5版本评测榜单 
  - 新增“医技考试”排行榜（含医技士-康复医学治疗技术、医技师-肿瘤学技术等22个方向），并计入总分，详见[link](#28-医技考试)
- [2025/3/13] 发布v3.4版本评测榜单
  - 新增“药师考试”排行榜（含执业西药师、执业中药师等8个方向），并计入总分，详见[link](#27-药师考试)
- [2025/3/11] 发布v3.3版本评测榜单
  - 新增“护理考试”排行榜（含护士执业资格考试、护师资格考试等10个方向），并计入总分，详见[link](#26-护理考试)
  - 新增6个模型：qwq-32b、qwq-plus-2025-03-05、step-2-mini、hunyuan-turbos-20250226、xunfei-spark-lite，☛查看[模型完整信息](https://easyllm.site/static/models.html)
- [2025/3/10] 发布v3.2版本评测榜单
  - 新增“医师考试/高级职称”排行榜（含等消化内科高级职称、普通内科高级职称等8个方向），并计入总分，详见[link](#25-医师考试高级职称)
- [2025/3/7] 发布v3.1版本评测榜单
  - 新增“医师考试/中级职称”排行榜（含超声波医学主治医师、妇产科主治医师等43个方向），并计入总分，详见[link](#24-医师考试中级职称)
- [2025/3/4] 发布v3.0版本评测榜单
  - 综合能力得分计算方式改为：医疗、教育、法律、行政公务、推理与数学计算、语言与指令遵从等6个领域得分的平均值。
  - 新增“医师考试/执业医师”排行榜（含中西医结合执业医师、口腔执业医师等5个方向），并计入总分，详见[link](#23-医师考试执业医师)
- [2025/3/3] 发布v2.22版本评测榜单
  - 新增“医师考试/执业助理医师”排行榜（含临床执业助理医师、口腔执业助理医师等5个方向），并计入总分，详见[link](#22-医师考试执业助理医师)
  - 删除陈旧的模型：SenseChat-Turbo、SenseChat-v4、SenseChat-5、Mixtral-8x7B-Instruct-v0.1
- [2025/2/28] 发布v2.21版本评测榜单
  - 新增“CMB-医师考试-规培结业”排行榜（含外科、皮肤科等18个方向），并计入总分，详见[link](#2医疗医师考试规培结业排行榜)
  - 删除陈旧的模型：Doubao-lite-32k-240428、Doubao-pro-32k-240615、o1-preview、WizardLM-2-8x22B、gemini-2.0-flash-lite-preview-02-05
- [2025/2/24] 发布v2.20版本评测榜单
  - 新增高中学科排行榜、初中学科排行榜、小学学科排行榜，并计入总分
  - 删除陈旧的模型：gpt-4o-2024-08-06、qwen-max-2024-09-19
- [2025/2/22] 发布v2.19版本评测榜单
  - 新增6个模型：kimi-latest-8k、SenseChat-5-beta、chatgpt-4o-latest、Doubao-1.5-pro-32k-250115、Doubao-1.5-lite-32k-250115、360zhinao2-o1，☛查看[模型完整信息](https://easyllm.site/static/models.html)
  - 新增推理类大模型排行榜，详见[link](leaderboard/reasonmodel.md)
- [2025/2/18] 发布v2.18版本评测榜单
  - 新增2个模型：qwen2.5-max、gemini-2.0-flash-thinking-exp-01-21，☛查看[模型完整信息](https://easyllm.site/static/models.html)
  - 新增演绎推理排行榜、C3中文阅读理解排行榜，并计入总分
- [2025/2/14] 发布v2.17版本评测榜单
  - 新增10个模型：GLM-Zero-Preview、MiniMax-Text-01、SenseChat-5-1202、SenseChat-Turbo-1202、GLM-4-FlashX、ERNIE-Lite-8K、ERNIE-Tiny-8K、ERNIE-Lite-Pro-128K、ERNIE-Speed-Pro-128K、qwen2.5-math-72b-instruct，☛查看[模型完整信息](https://easyllm.site/static/models.html)
  - 删除陈旧的模型：GLM4、gemini-1.0-pro、Llama-3.1-70B-Instruct、Meta-Llama-3.1-70B-Instruct-fp8
- [2025/2/13] 发布v2.16版本评测榜单
  - 新增6个模型：qwq-32b-preview、o1-mini、o3-mini、gemini-2.0-pro-exp-02-05、gemini-2.0-flash-lite-preview-02-05、gemini-2.0-flash-001，☛查看[模型完整信息](https://easyllm.site/static/models.html)
- [2025/2/12] 发布v2.15版本评测榜单
  - 新增成语理解排行榜、情感分析排行榜，并计入总分
- [2025/2/10] 发布v2.14版本评测榜单
  - 新增7个模型：DeepSeek-R1、DeepSeek-R1-Distill-Qwen-1.5B、DeepSeek-R1-Distill-Qwen-7B、DeepSeek-R1-Distill-Llama-8B、DeepSeek-R1-Distill-Qwen-14B、DeepSeek-R1-Distill-Qwen-32B、DeepSeek-R1-Distill-Llama-70B，☛查看[模型完整信息](https://easyllm.site/static/models.html)
- [2025/1/29] 发布v2.13版本评测榜单
  - 新增常识推理排行榜、文本蕴含（语言理解）排行榜，并计入总分
  - 阅读理解评测样本增加至600多个，并更新各模型评分
- [2025/1/25] 发布v2.12版本评测榜单
  - 新增高考榜单及各学科细分榜单（生物、化学、语文、地理、历史、数学、物理），并以各科平均分（100分制）计入总分
- [2025/1/23] 发布v2.11版本评测榜单
  - 公务员考试kaogong、律师资格考试JEC-QA开始计入总分
  - 新增4个模型：mistral-small、Hermes-3-Llama-3.1-405B、mistral-large、360gpt2-o1，☛查看[模型完整信息](https://easyllm.site/static/models.html)
- [2025/1/22] 发布v2.10版本评测榜单
  - 新增律师资格考试JEC-QA榜单，暂不计入总分
  - 新增7个模型：ministral-3b、Mistral-7B-Instruct-v0.3、Mistral-Nemo-Instruct-2407、ministral-8b、Mixtral-8x7B-Instruct-v0.1、Llama-3.1-Nemotron-70B-Instruct-fp8、WizardLM-2-8x22B，☛查看[模型完整信息](https://easyllm.site/static/models.html)
- [2025/1/20] 发布v2.9版本评测榜单
  - 新增公务员考试kaogong榜单，暂不计入总分
  - 新增5个模型：Llama-3.2-1B-Instruct、Llama-3.2-3B-Instruct、Llama-3.1-8B-Instruct-fp8、Llama-3.3-70B-Instruct-fp8、Llama-3.1-70B-Instruct-fp8，☛查看[模型完整信息](https://easyllm.site/static/models.html)
- [2025/1/17] 发布v2.8版本评测榜单
  - 新增9个模型：gemini-2.0-flash-exp、phi-4、gemini-1.5-flash-8b、360gpt-turbo、step-1-flash、Llama-3.3-70B-Instruct、360gpt-pro、360gpt2-pro、step-1-8k，☛查看[模型完整信息](https://easyllm.site/static/models.html)
  - 新增o1-mini、o1-preview的初中数学成绩
  - 删除陈旧的模型：abab5.5-chat、abab5.5s-chat
- [2025/1/7] 发布v2.7版本评测榜单
  - 新增代词理解CLUEWSC榜单（比如“他”是指谁）、诗词匹配CCPM榜单
  - 新增5个模型：Claude-3.5-Sonnet、gemma-2-27b-it、Llama-3.1-405B-Instruct、Baichuan4-Air、Baichuan4-Turbo，☛查看[模型完整信息](https://easyllm.site/static/models.html)
  - 删除陈旧的模型：Baichuan3-Turbo、qwen2-72b-instruct、Qwen2-7B-Instruct、qwen2-1.5b-instruct、qwen2-0.5b-instruct、qwen2-57b-a14b-instruct
- [2024/12/28]v2.6版本, [2024/12/27]v2.5版本, [2024/12/25]v2.4版本, [2024/10/20]v2.3版本，[2024/9/29]v2.2版本，[2024/8/27]v2.1版本，[2024/8/7]v2.0版本，[2024/7/26]v1.21版本，[2024/7/15]v1.20版本，[2024/6/29]v1.19版本，[2024/6/2]v1.18版本，[2024/5/8]v1.17版本，[2024/4/13]v1.16版本，[2024/3/20]v1.15版本，[2024/2/28]v1.14版本，[2024/1/29]v1.13版本
- 2023年：[2023/12/10]v1.12版本，[2023/11/22]v1.11版本，[2023/11/5]v1.10版本，[2023/10/11]v1.9版本，[2023/9/13]v1.8版本，[2023/8/29]v1.7版本，[2023/8/13]v1.6版本，[2023/7/26]v1.5版本， [2023/7/18]v1.4版本， [2023/7/2]v1.3版本， [2023/6/17]v1.2版， [2023/6/10]v1.1版本， [2023/6/4]v1版本

各版本更新详情：[CHANGELOG](CHANGELOG.md)

# TODO
- 引入更多维度的评测：代码能力、开放域问答、多轮对话、头脑风暴、翻译……
- 评测维度更细分，比如信息抽取可以细分时间实体抽取能力、地址实体抽取能力……
- 海纳百川，整合各类评测榜单，扩充细分领域榜单（比如教育领域、医疗领域）
- 加入更多评测数据，使得评测得分越来越有说服力

# 大模型基本信息
价格单位：元/1M tokens，即元每百万token   

|model|	producer|open-source|price_input|price_output|直接体验|download|paper|badcase|
|---|---|---|---|---|---|---|---|---|
|GLM-4-Flash|	智谱AI|	No|	0.0|	0.0|[link](https://easyllm.site/static/modelcompare.html)|	/|	[link](https://arxiv.org/abs/2406.12793)|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=GLM-4-Flash)|
|ERNIE-Speed-8K|	百度|	No|	0.0|	0.0|[link](https://easyllm.site/static/modelcompare.html)|	/|	/|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=ERNIE-Speed-8K)|
|internlm2_5-7b-chat|	上海人工智能实验室|	Yes|	0.3|	0.3|[link](https://easyllm.site/static/modelcompare.html)|	[link](https://www.modelscope.cn/models/Shanghai_AI_Laboratory/internlm2_5-7b-chat)|	/|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=internlm2_5-7b-chat)|
|Yi-1.5-9B-Chat|	零一万物|	Yes|	0.4|	0.4|[link](https://easyllm.site/static/modelcompare.html)|	[link](https://www.modelscope.cn/models/01ai/Yi-1.5-9B-Chat/)|	[link](https://arxiv.org/abs/2403.04652)|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=Yi-1.5-9B-Chat)|
|Llama-3.1-8B-Instruct|	meta|	Yes|	0.4|	0.4|[link](https://easyllm.site/static/modelcompare.html)|	[link](https://modelscope.cn/models/llm-research/meta-llama-3.1-8b-instruct)|	[link](https://arxiv.org/abs/2407.21783)|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=Llama-3.1-8B-Instruct)|
|Doubao-lite-32k|	豆包|	No|	0.3|	0.6|[link](https://easyllm.site/static/modelcompare.html)|	/|	/|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=Doubao-lite-32k)|
|glm-4-9b-chat|	智谱AI|	Yes|	0.6|	0.6|[link](https://easyllm.site/static/modelcompare.html)|	[link](https://www.modelscope.cn/models/ZhipuAI/glm-4-9b-chat)|	[link](https://arxiv.org/abs/2406.12793)|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=glm-4-9b-chat)|
|gemma-2-9b-it|	google|	Yes|	0.6|	0.6|[link](https://easyllm.site/static/modelcompare.html)|	[link](https://www.modelscope.cn/models/LLM-Research/gemma-2-9b-it)|	[link](https://arxiv.org/abs/2408.00118)|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=gemma-2-9b-it)|
|qwen2.5-7b-instruct|	阿里巴巴|	Yes|	1.0|	2.0|[link](https://easyllm.site/static/modelcompare.html)|	[link](https://modelscope.cn/models/qwen/Qwen2.5-7B-Instruct)|	/|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=qwen2.5-7b-instruct)|
|gemini-1.5-flash|	google|	No|	0.5|	2.2|[link](https://easyllm.site/static/modelcompare.html)|	/|	/|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=gemini-1.5-flash)|
|gpt-4o-mini|	openAI|	No|	1.1|	4.3|[link](https://easyllm.site/static/modelcompare.html)|	/|	[link](https://arxiv.org/abs/2303.08774)|	[link](https://easyllm.site/static/badcase/badcase-of-llm.html?model=gpt-4o-mini)|
|...|...|...|...|...|...|...|...|...|

更多模型信息详见：
- [大模型资源汇总（商用及开源）](https://easyllm.site/static/models.html)
- [开源大模型发布历史](LLM-history.md)
<br><br>

# 📊 排行榜
## 1、综合能力排行榜
综合能力得分为医疗、教育、法律、行政公务、心理健康、推理与数学计算、语言与指令遵从等7个领域得分的平均值。
![lin](pic/总分.png)    
详细数据见[total](leaderboard/总分.md)<br>

#### 1.1、推理类模型排行榜

|排名|大模型|机构|输出价格|总分| |医疗|教育|法律|行政公务|心理健康|推理与数学计算|语言与指令遵从|
|---|-----|---|-------|---|-|----|---|---|------|-------|-----------|------------|
|1|hunyuan-turbos-20250226(new)☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|腾讯|2.0元|83.7| |                    88.0|88.9|83.3|                    81.6|78.2|                    81.4|84.2|
|2|DeepSeek-R1☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|深度求索|16.0元|81.4| |                    82.1|89.5|74.8|                    88.6|61.5|                    88.5|84.8|
|3|hunyuan-turbos-20250313(new)☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|腾讯|2.0元|80.5| |                    84.1|87.8|72.2|                    80.0|72.9|                    82.0|84.4|
    

完整排行榜见[推理类模型排行榜](leaderboard/reasonmodel.md)<br>
<br>
#### 1.2、商用大模型排行榜（含开源模型的付费API）
##### （1）输出价格30元及以上商用大模型排行榜

|排名|大模型|机构|输出价格|总分| |医疗|教育|法律|行政公务|心理健康|推理与数学计算|语言与指令遵从|
|---|-----|---|-------|---|-|----|---|---|------|-------|-----------|------------|
|1|xunfei-4.0Ultra☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|科大讯飞|70.0元|74.2| |                    75.6|81.9|66.7|                    72.0|61.2|                    79.5|82.3|
|2|GLM-4-Plus☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|智谱AI|50.0元|73.7| |                    74.7|81.3|63.1|                    76.7|59.0|                    77.2|84.1|
|3|xunfei-spark-max☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|科大讯飞|30.0元|73.1| |                    76.4|83.8|66.5|                    70.4|59.0|                    76.6|79.3|
    
  
完整排行榜见[30元及以上商用大模型](leaderboard/commerce1.md)<br><br>

##### （2）输出价格5~30元商用大模型排行榜

|排名|大模型|机构|输出价格|总分| |医疗|教育|法律|行政公务|心理健康|推理与数学计算|语言与指令遵从|
|---|-----|---|-------|---|-|----|---|---|------|-------|-----------|------------|
|1|ERNIE-4.5-8K-Preview(new)☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|百度|16.0元|86.2| |                    91.5|87.0|90.3|                    87.0|75.2|                    83.9|88.4|
|2|DeepSeek-R1☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|深度求索|16.0元|81.4| |                    82.1|89.5|74.8|                    88.6|61.5|                    88.5|84.8|
|3|hunyuan-turbo☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|腾讯|9.6元|79.9| |                    86.3|87.1|75.7|                    76.2|71.8|                    79.9|82.3|
    
   
完整排行榜见[5~30元商用大模型](leaderboard/commerce2.md)<br><br>

##### （3）输出价格1~5元商用大模型排行榜

|排名|大模型|机构|输出价格|总分| |医疗|教育|法律|行政公务|心理健康|推理与数学计算|语言与指令遵从|
|---|-----|---|-------|---|-|----|---|---|------|-------|-----------|------------|
|1|hunyuan-turbos-20250226(new)☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|腾讯|2.0元|83.7| |                    88.0|88.9|83.3|                    81.6|78.2|                    81.4|84.2|
|2|Doubao-1.5-pro-32k-250115☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|豆包|2.0元|81.4| |                    85.8|89.9|72.3|                    78.3|74.4|                    82.8|86.5|
|3|hunyuan-turbos-20250313(new)☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|腾讯|2.0元|80.5| |                    84.1|87.8|72.2|                    80.0|72.9|                    82.0|84.4|
    
  
完整排行榜见[1~5元商用大模型](leaderboard/commerce3.md)<br><br>

##### （4）输出价格1元以下商用大模型排行榜

|排名|大模型|机构|输出价格|总分| |医疗|教育|法律|行政公务|心理健康|推理与数学计算|语言与指令遵从|
|---|-----|---|-------|---|-|----|---|---|------|-------|-----------|------------|
|1|Doubao-1.5-lite-32k-250115☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|豆包|0.6元|75.1| |                    81.1|84.9|63.2|                    70.7|65.8|                    82.8|77.5|
|2|gemini-2.0-flash-thinking-exp-01-21☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|Google|0.0元|71.0| |                    66.3|76.6|47.9|                    85.1|53.5|                    89.3|78.5|
|3|gemini-2.0-pro-exp-02-05☛[去体验](https://easyllm.site/static/modelcompare.html?type=proprietary)|Google|0.0元|71.0| |                    72.4|82.0|45.6|                    73.7|60.6|                    83.9|79.0|
    
   
完整排行榜见[1元以下商用大模型](leaderboard/commerce4.md)<br>

DIY自定义维度筛选榜单：☛ [link](https://easyllm.site/static/benchmarking.html) 

旗舰商用模型badcase: [gpt-4o](http://easyllm.site/static/badcase/badcase-of-llm.html?model=gpt-4o) | 
[deepseek-chat-v3](http://easyllm.site/static/badcase/badcase-of-llm.html?model=deepseek-chat-v3) |
[更多](http://easyllm.site/static/badcase.html)
<br><br>
<br>
#### 1.3、开源大模型排行榜
##### （1）5B以下开源大模型排行榜

|排名|大模型|机构|输出价格|总分| |医疗|教育|法律|行政公务|心理健康|推理与数学计算|语言与指令遵从|
|---|-----|---|-------|---|-|----|---|---|------|-------|-----------|------------|
|1|qwen2.5-3b-instruct☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|阿里巴巴|0.9元|51.6| |                    50.0|58.8|29.2|                    51.3|43.8|                    60.8|67.6|
|2|qwen2.5-1.5b-instruct☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|阿里巴巴|0.0元|42.6| |                    44.1|52.2|29.6|                    40.5|39.6|                    40.4|51.5|
|3|gemma-3-4b-it(new)☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|Google|0.0元|41.4| |                    32.3|43.7|16.5|                    39.5|29.2|                    70.7|58.0|
    
   
完整排行榜见[5B以下开源大模型](leaderboard/opensource1.md)<br><br>

##### （2）5B~20B开源大模型排行榜

|排名|大模型|机构|输出价格|总分| |医疗|教育|法律|行政公务|心理健康|推理与数学计算|语言与指令遵从|
|---|-----|---|-------|---|-|----|---|---|------|-------|-----------|------------|
|1|DeepSeek-R1-Distill-Qwen-14B☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|深度求索|0.7元|66.7| |                    63.0|77.0|42.2|                    68.0|55.6|                    82.3|78.7|
|2|qwen2.5-14b-instruct☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|阿里巴巴|6.0元|66.7| |                    67.7|77.0|47.1|                    67.0|56.1|                    71.7|79.9|
|3|internlm2_5-20b-chat☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|上海人工智能实验室|1.0元|63.4| |                    65.4|70.3|46.4|                    66.4|52.7|                    65.3|77.2|
    
   
完整排行榜见[5B~20B开源大模型](leaderboard/opensource2.md)<br><br>

##### （3）20B以上开源大模型排行榜

|排名|大模型|机构|输出价格|总分| |医疗|教育|法律|行政公务|心理健康|推理与数学计算|语言与指令遵从|
|---|-----|---|-------|---|-|----|---|---|------|-------|-----------|------------|
|1|DeepSeek-R1☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|深度求索|16.0元|81.4| |                    82.1|89.5|74.8|                    88.6|61.5|                    88.5|84.8|
|2|hunyuan-large☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|腾讯|12.0元|79.8| |                    85.9|83.3|83.2|                    75.7|73.2|                    77.1|80.1|
|3|qwq-32b(new)☛[去体验](https://easyllm.site/static/modelcompare.html?type=open-source)|阿里巴巴|6.0元|78.2| |                    76.3|86.1|62.5|                    86.5|63.0|                    87.6|85.2|
    
   
完整排行榜见[20B以上开源大模型](leaderboard/opensource3.md)<br><br>

DIY自定义维度筛选榜单：☛[link](https://easyllm.site/static/benchmarking.html)

<br><br>


## 2、医疗排行榜
☛☛完整排行榜见[医疗](leaderboard/医疗.md)<br>

### 2.1 医师考试/规培结业
医师考试之规培结业，均为选择题，含外科、皮肤科等18个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[医师考试/规培结业](leaderboard/CMB-医师考试-规培结业.md)<br>

 - 外科：[排行榜](leaderboard/CMB-医师考试-规培结业-外科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-外科)
 - 皮肤科：[排行榜](leaderboard/CMB-医师考试-规培结业-皮肤科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-皮肤科)
 - 妇产科：[排行榜](leaderboard/CMB-医师考试-规培结业-妇产科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-妇产科)
 - 耳鼻咽喉科：[排行榜](leaderboard/CMB-医师考试-规培结业-耳鼻咽喉科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-耳鼻咽喉科)
 - 神经内科：[排行榜](leaderboard/CMB-医师考试-规培结业-神经内科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-神经内科)
 - 儿科：[排行榜](leaderboard/CMB-医师考试-规培结业-儿科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-儿科)
 - 麻醉科：[排行榜](leaderboard/CMB-医师考试-规培结业-麻醉科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-麻醉科)
 - 小儿外科：[排行榜](leaderboard/CMB-医师考试-规培结业-小儿外科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-小儿外科)
 - 眼科：[排行榜](leaderboard/CMB-医师考试-规培结业-眼科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-眼科)
 - 临床病理科：[排行榜](leaderboard/CMB-医师考试-规培结业-临床病理科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-临床病理科)
 - 超声科：[排行榜](leaderboard/CMB-医师考试-规培结业-超声科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-超声科)
 - 康复医学科：[排行榜](leaderboard/CMB-医师考试-规培结业-康复医学科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-康复医学科)
 - 骨科：[排行榜](leaderboard/CMB-医师考试-规培结业-骨科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-骨科)
 - 内科：[排行榜](leaderboard/CMB-医师考试-规培结业-内科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-内科)
 - 口腔科：[排行榜](leaderboard/CMB-医师考试-规培结业-口腔科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-口腔科)
 - 医学影像科：[排行榜](leaderboard/CMB-医师考试-规培结业-医学影像科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-医学影像科)
 - 全科医学科：[排行榜](leaderboard/CMB-医师考试-规培结业-全科医学科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-全科医学科)
 - 精神科：[排行榜](leaderboard/CMB-医师考试-规培结业-精神科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-规培结业-精神科)
<br><br><br>


### 2.2 医师考试/执业助理医师
医师考试之执业助理医师，均为选择题，含临床执业助理医师、口腔执业助理医师等5个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[医师考试/执业助理医师](leaderboard/CMB-医师考试-执业助理医师.md)<br>

 - 临床执业助理医师：[排行榜](leaderboard/CMB-医师考试-执业助理医师-临床执业助理医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业助理医师-临床执业助理医师)
 - 中西医结合执业助理医师：[排行榜](leaderboard/CMB-医师考试-执业助理医师-中西医结合执业助理医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业助理医师-中西医结合执业助理医师)
 - 口腔执业助理医师：[排行榜](leaderboard/CMB-医师考试-执业助理医师-口腔执业助理医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业助理医师-口腔执业助理医师)
 - 公共卫生执业助理医师：[排行榜](leaderboard/CMB-医师考试-执业助理医师-公共卫生执业助理医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业助理医师-公共卫生执业助理医师)
 - 中医执业助理医师：[排行榜](leaderboard/CMB-医师考试-执业助理医师-中医执业助理医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业助理医师-中医执业助理医师)
<br><br><br>


### 2.3 医师考试/执业医师
医师考试之执业医师，均为选择题，含中西医结合执业医师、公共卫生执业医师等5个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[医师考试/执业医师](leaderboard/CMB-医师考试-执业医师.md)<br>

 - 中西医结合执业医师：[排行榜](leaderboard/CMB-医师考试-执业医师-中西医结合执业医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业医师-中西医结合执业医师)
 - 中医执业医师：[排行榜](leaderboard/CMB-医师考试-执业医师-中医执业医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业医师-中医执业医师)
 - 公共卫生执业医师：[排行榜](leaderboard/CMB-医师考试-执业医师-公共卫生执业医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业医师-公共卫生执业医师)
 - 临床执业医师：[排行榜](leaderboard/CMB-医师考试-执业医师-临床执业医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业医师-临床执业医师)
 - 口腔执业医师：[排行榜](leaderboard/CMB-医师考试-执业医师-口腔执业医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-执业医师-口腔执业医师)
<br><br><br>


### 2.4 医师考试/中级职称
医师考试之中级职称，均为选择题，含超声波医学主治医师、妇产科主治医师等43个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[医师考试/中级职称](leaderboard/CMB-医师考试-中级职称.md)<br>

 - 超声波医学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-超声波医学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-超声波医学主治医师)
 - 妇产科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-妇产科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-妇产科主治医师)
 - 中医内科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-中医内科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-中医内科主治医师)
 - 精神病学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-精神病学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-精神病学主治医师)
 - 皮肤科：[排行榜](leaderboard/CMB-医师考试-中级职称-皮肤科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-皮肤科)
 - 内科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-内科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-内科主治医师)
 - 康复医学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-康复医学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-康复医学主治医师)
 - 神经内科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-神经内科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-神经内科主治医师)
 - 核医学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-核医学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-核医学主治医师)
 - 口腔内科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-口腔内科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-口腔内科主治医师)
 - 儿科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-儿科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-儿科主治医师)
 - 结核病主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-结核病主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-结核病主治医师)
 - 心血管内科与呼吸内科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-心血管内科与呼吸内科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-心血管内科与呼吸内科主治医师)
 - 重症医学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-重症医学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-重症医学主治医师)
 - 职业病主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-职业病主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-职业病主治医师)
 - 口腔科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-口腔科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-口腔科主治医师)
 - 放射科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-放射科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-放射科主治医师)
 - 耳鼻咽喉科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-耳鼻咽喉科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-耳鼻咽喉科主治医师)
 - 肿瘤学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-肿瘤学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-肿瘤学主治医师)
 - 医院感染：[排行榜](leaderboard/CMB-医师考试-中级职称-医院感染.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-医院感染)
 - 麻醉科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-麻醉科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-麻醉科主治医师)
 - 疼痛科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-疼痛科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-疼痛科主治医师)
 - 病理科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-病理科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-病理科主治医师)
 - 传染病主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-传染病主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-传染病主治医师)
 - 皮肤与性病学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-皮肤与性病学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-皮肤与性病学主治医师)
 - 肾内科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-肾内科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-肾内科主治医师)
 - 口腔修复科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-口腔修复科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-口腔修复科主治医师)
 - 预防医学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-预防医学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-预防医学主治医师)
 - 中医针灸主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-中医针灸主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-中医针灸主治医师)
 - 口腔颌面外科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-口腔颌面外科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-口腔颌面外科主治医师)
 - 风湿与临床免疫主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-风湿与临床免疫主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-风湿与临床免疫主治医师)
 - 消化内科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-消化内科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-消化内科主治医师)
 - 心理治疗学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-心理治疗学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-心理治疗学主治医师)
 - 传染病学：[排行榜](leaderboard/CMB-医师考试-中级职称-传染病学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-传染病学)
 - 全科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-全科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-全科主治医师)
 - 眼科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-眼科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-眼科主治医师)
 - 口腔正畸学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-口腔正畸学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-口腔正畸学主治医师)
 - 中西医结合内科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-中西医结合内科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-中西医结合内科主治医师)
 - 营养学主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-营养学主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-营养学主治医师)
 - 整形外科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-整形外科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-整形外科主治医师)
 - 心理咨询师：[排行榜](leaderboard/CMB-医师考试-中级职称-心理咨询师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-心理咨询师)
 - 骨科：[排行榜](leaderboard/CMB-医师考试-中级职称-骨科.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-骨科)
 - 外科主治医师：[排行榜](leaderboard/CMB-医师考试-中级职称-外科主治医师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-外科主治医师)
<br><br><br>


### 2.5 医师考试/高级职称
医师考试之高级职称，均为选择题，含等消化内科高级职称、普通内科高级职称等8个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[医师考试/高级职称](leaderboard/CMB-医师考试-高级职称.md)<br>

 - 消化内科高级职称：[排行榜](leaderboard/CMB-医师考试-高级职称-消化内科高级职称.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-高级职称-消化内科高级职称)
 - 普通内科高级职称：[排行榜](leaderboard/CMB-医师考试-高级职称-普通内科高级职称.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-高级职称-普通内科高级职称)
 - 普通外科高级职称：[排行榜](leaderboard/CMB-医师考试-高级职称-普通外科高级职称.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-高级职称-普通外科高级职称)
 - 骨科高级职称：[排行榜](leaderboard/CMB-医师考试-高级职称-骨科高级职称.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-高级职称-骨科高级职称)
 - 呼吸内科高级职称：[排行榜](leaderboard/CMB-医师考试-高级职称-呼吸内科高级职称.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-高级职称-呼吸内科高级职称)
 - 内分泌科高级职称：[排行榜](leaderboard/CMB-医师考试-高级职称-内分泌科高级职称.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-高级职称-内分泌科高级职称)
 - 心内科高级职称：[排行榜](leaderboard/CMB-医师考试-高级职称-心内科高级职称.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-高级职称-心内科高级职称)
 - 妇产科学副主任、主任医师职称考试：[排行榜](leaderboard/CMB-医师考试-高级职称-妇产科学副主任、主任医师职称考试.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-高级职称-妇产科学副主任、主任医师职称考试)
<br><br><br>


### 2.6 护理考试
护理考试，均为选择题，含护士执业资格考试、护师资格考试等10个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[护理考试](leaderboard/CMB-护理考试.md)<br>

 - 护士执业资格考试：[排行榜](leaderboard/CMB-护理考试-护士执业资格-护士执业资格考试.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-护士执业资格-护士执业资格考试)
 - 护师资格考试：[排行榜](leaderboard/CMB-护理考试-护师执业资格-护师资格考试.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-护师执业资格-护师资格考试)
 - 儿科主管护师：[排行榜](leaderboard/CMB-护理考试-主管护师-儿科主管护师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-主管护师-儿科主管护师)
 - 内科护理学：[排行榜](leaderboard/CMB-护理考试-主管护师-内科护理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-主管护师-内科护理学)
 - 妇产科护理学：[排行榜](leaderboard/CMB-护理考试-主管护师-妇产科护理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-主管护师-妇产科护理学)
 - 妇产科主管护师：[排行榜](leaderboard/CMB-护理考试-主管护师-妇产科主管护师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-主管护师-妇产科主管护师)
 - 外科主管护师：[排行榜](leaderboard/CMB-护理考试-主管护师-外科主管护师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-主管护师-外科主管护师)
 - 主管护师资格考试：[排行榜](leaderboard/CMB-护理考试-主管护师-主管护师资格考试.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-主管护师-主管护师资格考试)
 - 内科主管护师：[排行榜](leaderboard/CMB-护理考试-主管护师-内科主管护师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-主管护师-内科主管护师)
 - 副主任、主任护师资格考试：[排行榜](leaderboard/CMB-护理考试-高级护师-副主任、主任护师资格考试.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-护理考试-高级护师-副主任、主任护师资格考试)
<br><br><br>


### 2.7 药师考试
药师考试，均为选择题，含执业西药师、执业中药师等8个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[药师考试](leaderboard/CMB-药师考试.md)<br>

 - 执业西药师：[排行榜](leaderboard/CMB-药师考试-执业西药师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-药师考试-执业西药师)
 - 执业中药师：[排行榜](leaderboard/CMB-药师考试-执业中药师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-药师考试-执业中药师)
 - 药士初级考试：[排行榜](leaderboard/CMB-药师考试-初级药士-药士初级考试.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-药师考试-初级药士-药士初级考试)
 - 药师初级考试：[排行榜](leaderboard/CMB-药师考试-初级药师-药师初级考试.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-药师考试-初级药师-药师初级考试)
 - 中药学（士）：[排行榜](leaderboard/CMB-药师考试-初级中药士-中药学（士）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-药师考试-初级中药士-中药学（士）)
 - 中药学（师）：[排行榜](leaderboard/CMB-药师考试-初级中药师-中药学（师）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-药师考试-初级中药师-中药学（师）)
 - 主管药师资格考试：[排行榜](leaderboard/CMB-药师考试-主管药师-主管药师资格考试.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-药师考试-主管药师-主管药师资格考试)
 - 主管中药师：[排行榜](leaderboard/CMB-药师考试-主管中药师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-药师考试-主管中药师)
<br><br><br>


### 2.8 医技考试
医技考试，均为选择题，含医技士-康复医学治疗技术（士）、医技师-肿瘤学技术（师）等22个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[医技考试](leaderboard/CMB-医技考试.md)<br>

 - 康复医学治疗技术（士）：[排行榜](leaderboard/CMB-医技考试-医技士-康复医学治疗技术（士）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-医技士-康复医学治疗技术（士）)
 - 放射学技术（士）：[排行榜](leaderboard/CMB-医技考试-医技士-放射学技术（士）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-医技士-放射学技术（士）)
 - 检验技术（士）：[排行榜](leaderboard/CMB-医技考试-医技士-检验技术（士）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-医技士-检验技术（士）)
 - 肿瘤学技术（士）：[排行榜](leaderboard/CMB-医技考试-医技士-肿瘤学技术（士）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-医技士-肿瘤学技术（士）)
 - 康复医学治疗技术（师）：[排行榜](leaderboard/CMB-医技考试-医技师-康复医学治疗技术（师）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-医技师-康复医学治疗技术（师）)
 - 肿瘤学技术（师）：[排行榜](leaderboard/CMB-医技考试-医技师-肿瘤学技术（师）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-医技师-肿瘤学技术（师）)
 - 放射学技术（师）：[排行榜](leaderboard/CMB-医技考试-医技师-放射学技术（师）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-医技师-放射学技术（师）)
 - 检验技术（师）：[排行榜](leaderboard/CMB-医技考试-医技师-检验技术（师）.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-医技师-检验技术（师）)
 - 肿瘤放射治疗主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-肿瘤放射治疗主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-肿瘤放射治疗主管技师)
 - 超声波医学主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-超声波医学主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-超声波医学主管技师)
 - 输血技术主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-输血技术主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-输血技术主管技师)
 - 微生物检验主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-微生物检验主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-微生物检验主管技师)
 - 放射医学主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-放射医学主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-放射医学主管技师)
 - 病理学主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-病理学主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-病理学主管技师)
 - 理化检验主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-理化检验主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-理化检验主管技师)
 - 病理学技术：[排行榜](leaderboard/CMB-医技考试-主管技师-病理学技术.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-病理学技术)
 - 临床医学检验主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-临床医学检验主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-临床医学检验主管技师)
 - 病案信息主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-病案信息主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-病案信息主管技师)
 - 核医学主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-核医学主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-核医学主管技师)
 - 心电学主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-心电学主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-心电学主管技师)
 - 消毒技术主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-消毒技术主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-消毒技术主管技师)
 - 康复医学与治疗主管技师：[排行榜](leaderboard/CMB-医技考试-主管技师-康复医学与治疗主管技师.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医技考试-主管技师-康复医学与治疗主管技师)
<br><br><br>


### 2.9 专业知识考试/基础医学
专业知识考试/基础医学，均为选择题，包含病理生理学、医学心理学等17个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[基础医学](leaderboard/CMB-专业知识考试-基础医学.md)<br>

 - 病理生理学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-病理生理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-病理生理学)
 - 医学心理学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-医学心理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-医学心理学)
 - 生物化学与分子生物学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-生物化学与分子生物学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-生物化学与分子生物学)
 - 细胞生物学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-细胞生物学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-细胞生物学)
 - 医学免疫学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-医学免疫学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-医学免疫学)
 - 病理学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-病理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-病理学)
 - 医学遗传学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-医学遗传学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-医学遗传学)
 - 寄生虫学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-寄生虫学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-寄生虫学)
 - 系统解剖学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-系统解剖学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-系统解剖学)
 - 生物信息学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-生物信息学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-生物信息学)
 - 生理学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-生理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-生理学)
 - 药理学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-药理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-药理学)
 - 医学微生物学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-医学微生物学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-医学微生物学)
 - 局部解剖学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-局部解剖学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-局部解剖学)
 - 组织学与胚胎学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-组织学与胚胎学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-组织学与胚胎学)
 - 人体寄生虫学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-人体寄生虫学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-人体寄生虫学)
 - 医学统计学：[排行榜](leaderboard/CMB-专业知识考试-基础医学-医学统计学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-医学统计学)
<br><br><br>


### 2.10 专业知识考试/临床医学
专业知识考试/临床医学，均为选择题，包含医学影像学、放射学等22个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[临床医学](leaderboard/CMB-专业知识考试-临床医学.md)<br>

 - 医学影像学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-医学影像学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-医学影像学)
 - 放射学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-放射学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-放射学)
 - 实验诊断学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-实验诊断学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-实验诊断学)
 - 神经病学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-神经病学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-神经病学)
 - 外科学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-外科学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-外科学)
 - 皮肤性病学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-皮肤性病学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-皮肤性病学)
 - 儿科学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-儿科学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-儿科学)
 - 核医学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-核医学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-核医学)
 - 物理诊断学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-物理诊断学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-物理诊断学)
 - 牙体牙髓病学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-牙体牙髓病学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-牙体牙髓病学)
 - 护理学基础：[排行榜](leaderboard/CMB-专业知识考试-临床医学-护理学基础.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-护理学基础)
 - 诊断学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-诊断学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-诊断学)
 - 超声医学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-超声医学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-超声医学)
 - 口腔护理学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-口腔护理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-口腔护理学)
 - 循证医学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-循证医学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-循证医学)
 - 基础护理学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-基础护理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-基础护理学)
 - 流行病学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-流行病学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-流行病学)
 - 口腔组织病理学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-口腔组织病理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-口腔组织病理学)
 - 传染病学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-传染病学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-传染病学)
 - 口腔解剖生理学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-口腔解剖生理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-口腔解剖生理学)
 - 麻醉学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-麻醉学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-麻醉学)
 - 介入放射学：[排行榜](leaderboard/CMB-专业知识考试-临床医学-介入放射学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-临床医学-介入放射学)
<br><br><br>


### 2.11 专业知识考试/预防医学与公共卫生学
专业知识考试/预防医学与公共卫生学，均为选择题，包含预防医学、卫生学、医学伦理学等3个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[预防医学与公共卫生学](leaderboard/CMB-专业知识考试-预防医学与公共卫生学.md)<br>

 - 预防医学：[排行榜](leaderboard/CMB-专业知识考试-预防医学与公共卫生学-预防医学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-预防医学与公共卫生学-预防医学)
 - 卫生学：[排行榜](leaderboard/CMB-专业知识考试-预防医学与公共卫生学-卫生学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-预防医学与公共卫生学-卫生学)
 - 医学伦理学：[排行榜](leaderboard/CMB-专业知识考试-预防医学与公共卫生学-医学伦理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-预防医学与公共卫生学-医学伦理学)
<br><br><br>


### 2.12 专业知识考试/中医学与中药学
专业知识考试/中医学与中药学，均为选择题，包含中医眼科学、金匮要略讲义、中医基础理论等11个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[中医学与中药学](leaderboard/CMB-专业知识考试-中医学与中药学.md)<br>

 - 中医眼科学：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-中医眼科学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-中医眼科学)
 - 金匮要略讲义：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-金匮要略讲义.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-金匮要略讲义)
 - 中医基础理论：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-中医基础理论.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-中医基础理论)
 - 中医诊断学：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-中医诊断学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-中医诊断学)
 - 中医学：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-中医学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-中医学)
 - 温病学：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-温病学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-温病学)
 - 中国医学史：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-中国医学史.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-中国医学史)
 - 中医内科学：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-中医内科学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-中医内科学)
 - 中医儿科学：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-中医儿科学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-中医儿科学)
 - 伤寒论：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-伤寒论.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-伤寒论)
 - 内经讲义：[排行榜](leaderboard/CMB-专业知识考试-中医学与中药学-内经讲义.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-中医学与中药学-内经讲义)
<br><br><br>


### 2.13 医学考研
医学考研，包含外科护理学、基础护理学、西医综合等5个方向，参考[CMB](https://github.com/FreedomIntelligence/CMB)。<br>
☛☛完整排行榜见[医学考研](leaderboard/CMB-医学考研.md)<br>

 - 外科护理学：[排行榜](leaderboard/CMB-医学考研-护理学-外科护理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医学考研-护理学-外科护理学)
 - 基础护理学：[排行榜](leaderboard/CMB-医学考研-护理学-基础护理学.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医学考研-护理学-基础护理学)
 - 考研政治：[排行榜](leaderboard/CMB-医学考研-考研政治.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医学考研-考研政治)
 - 西医综合：[排行榜](leaderboard/CMB-医学考研-西医综合.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医学考研-西医综合)
 - 中医综合：[排行榜](leaderboard/CMB-医学考研-中医综合.md) | [样本举例及badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医学考研-中医综合)
<br><br><br>

    
## 3、教育排行榜
☛☛完整排行榜见[教育](leaderboard/教育.md)<br>

### 3.1 高考
历年高考题，共1500多道，绝大部分为选择题，少部分为填空题。<br>
☛☛完整排行榜见[高考](leaderboard/高考.md)<br>

#### （1）高考生物
评测样本举例：
> 已知(1)酶、(2)抗体、(3)激素、(4)糖原、(5)脂肪、(6)核酸都是人体内有重要作用的物质。下列说法正确的 是    
(A)(1)(2)(3)都是由氨基酸通过肽键连接而成的   
(B)(3)(4)(5)都是生物大分子, 都以碳链为骨架   
(C)(1)(2)(6)都是由含氮的单体连接成的多聚体   
(D)(4)(5)(6)都是人体细胞内的主要能源物质   
>     

完整排行榜见[高考生物](leaderboard/gaokao-biology.md)，☛查看[高考生物badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=gaokao-biology)
<br>

#### （2）高考化学
评测样本举例：
> 以下是中华民族为人类文明进步做出巨大贡献的几个事例, 运用化学知识对其 进行的分析不合理的是 ( )   
(A)四千余年前用谷物酿造出酒和酯, 酿造过程中只发生水解反应   
(B)商代后期铸造出工艺精湛的后（司）母戊鼎, 该鼎属于铜合金制品   
(C)汉代烧制出“明如镜、声如磬”的瓷器，其主要原料为黏土   
(D)屠呦呦用乙醚从青蒿中提取出对治疗疘疾有特效的青高素, 该过程包括萃取操作    
>    

完整排行榜见[高考化学](leaderboard/gaokao-chemistry.md)，☛查看[高考化学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=gaokao-chemistry)
<br>

#### （3）高考语文
评测样本举例：
> 下列各句中，没有语病的一句是   
(A)根据本报和部分出版机构联合开展的调查显示，儿童的阅读启蒙集中在1~2岁之间，并且阅读时长是随着年龄的增长而增加的。   
(B)为了培养学生关心他人的美德，我们学校决定组织开展义工服务活动，三个月内要求每名学生完成20个小时的义工服务。   
(C)在互联网时代，各领域发展都需要速度更快、成本更低的信息网络，网络提速降费能够推动“互联网+”快速发展和企业广泛收益。   
(D)面对经济全球化带来的机遇和挑战，正确的选择是，充分利用一切机遇，合作一切挑战，引导好经济全球化走向。  
>   

完整排行榜见[高考语文](leaderboard/gaokao-chinese.md)，☛查看[高考语文badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=gaokao-chinese)
<br>

#### （4）高考地理
评测样本举例：
> 农业生产中地膜覆盖对土壤理化性状的主要作用是（）   
①保持土壤温度  ②减少水肥流失  ③增加土壤厚度  ④改善土壤质地     
(A)①②    (B)①④   (C)②③   (D)③④   
>    

完整排行榜见[高考地理](leaderboard/gaokao-geography.md)，☛查看[高考地理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=gaokao-geography)
<br>

#### （5）高考历史
评测样本举例：
> “一万年农业，五千年文明，两千年大一统”指的是  
(A)中华文明  (B)埃及文明  (C)印度文明  (D)希腊文明   
>  

完整排行榜见[高考历史](leaderboard/gaokao-history.md)，☛查看[高考历史badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=gaokao-history)
<br>

#### （6）高考数学
评测样本举例：
> 已知 a ∈ R, (1+a*i)i=3+i, (i为虚数单位), 则 a=()  
(A)-1 (B)1 (C)-3 (D)3    

完整排行榜见[高考数学](leaderboard/gaokao-math.md)，☛查看[高考数学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=gaokao-math)
<br>

#### （7）高考物理
评测样本举例：
> 20 世纪 60 年代, 我国以国防为主的尖端科技取得了突破性的发展。1964 年, 我国第一颗原子弹试爆成 功； 1967 年, 我国第一颗氢弹试爆成功。关于原子弹和氢弹, 下列说法正确的是（ ）    
(A)原子弹和氢弹都是根据核裂变原理研制的   
(B)原子弹和氢弹都是根据核聚变原理研制的   
(C)原子弹是根据核裂变原理研制的，氢弹是根据核聚变原理研制的   
(D)原子弹是根据核聚变原理研制的，氢弹是根据核裂变原理研制的   
>     

完整排行榜见[高考物理](leaderboard/gaokao-physics.md)，☛查看[高考物理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=gaokao-physics)
<br>

#### （8）高考政治
评测样本举例：
>  2020年，电影《夺冠》以1981年到2019年期间中国女排十夺世界冠军为主线，通过艺术形式展现了中国女排祖国至上、团结协作、顽强拼搏、永不言败的精神面貌，给观众带来心灵的震撼和鼓舞，受到普遍好评．从中可获得的启示是（    ）   
①人民群众满意与否是衡量文艺作品价值的根本尺度   
②优秀的文艺作品都是对现实生活的真实再现   
③塑造典型艺术形象是艺术创作的根本价值追求   
④反映时代精神的文艺作品能够增强人的精神力量   
（A）③④   （B）①②   （C）②③  （D）①④   
>  

完整排行榜见[高考政治](leaderboard/gaokao-politics.md)，☛查看[高考政治badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=gaokao-politics)
<br><br>


### 3.2 高中学科
☛☛完整排行榜见[高中学科](leaderboard/高中学科.md)<br>

#### （1）高中生物
评测样本举例：
> 回答以下选择题：人体内含有多种多样的蛋白质，每种蛋白质（    ）  
(A) 都具有一定的空间结构   
(B) 都含有21种氨基酸   
(C) 都是在细胞内发挥作用  
(D) 都能调节生物体的生命活动   
>    

完整排行榜见[高中生物](leaderboard/HighSchoolBiology.md)，☛查看[高中生物badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=HighSchoolBiology)
<br>

#### （2）高中化学
评测样本举例：
> 回答以下选择题：实验室需配制一种强酸溶液500mL，c($H^+$)=2mol/L，下列配制方法可行的是   
(A) 取100mL5mol/L$HNO_3$，加水稀释至500mL   
(B) 取100mL5mol/L$H_2SO_4$，加入400mL水   
(C) 取100mL5mol/L$H_2SO_4$，加水稀释至500mL   
(D) 取100mL5mol/LHCl，加水稀释至500mL   
>    

完整排行榜见[高中化学](leaderboard/HighSchoolChemistry.md)，☛查看[高中化学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=HighSchoolChemistry)
<br>

#### （3）高中语文
评测样本举例：
> 回答以下选择题：下列句子中，词语使用不恰当的一项是（ ）   
(A) 说“木叶”不说“树叶”，决非古人标新立异，“木叶”作为意象而言，蕴含着更多的意味，包含着更多的情感，更能体现其艺术特征。   
(B) 我们时常说到乡愁，什么是乡愁？乡愁是我们的百姓对生养自己的故土故乡刻骨铭心的情感与爱恋，是家园真正的精神价值。   
(C) 企业的发展需要通才，所谓通才不是指万金油或叫作万应锭式的人，而是指能在技术研发、成本核算、外交沟通等方面都能挑大梁的人才。   
(D) 无数案例告诉我们，防止电话诈骗，最有效的方法是对陌生电话的求救、告急多问几个为什么，这样就可避免落于言筌。   
>     

完整排行榜见[高中语文](leaderboard/HighSchoolChinese.md)，☛查看[高中语文badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=HighSchoolChinese)
<br>

#### （4）高中英语
评测样本举例：
> 回答以下选择题：For long I’ve been trying to ________ what it is that makes Jack so annoyed.   
(A) stand out   
(B) carry out   
(C) watch out   
(D) figure out   
>  

完整排行榜见[高中英语](leaderboard/HighSchoolEnglish.md)，☛查看[高中英语badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=HighSchoolEnglish)
<br>

#### （5）高中地理
评测样本举例：
> 回答以下选择题：北京时间2017年10月9日12时13分，长征二号丁运载火箭托举着委内瑞拉遥感卫星二号，在酒泉卫星发射中心顺利升空。卫星顺利进入预定轨道，发射任务取得圆满成功。该卫星发射时，我国下列现象可能出现的是(   )   
(A) 地球公转速度正在加快   
(B) 北京昼长夜短   
(C) 上海正午太阳高度达最小值   
(D) 酒泉该日太阳从东北方升起   
>   

完整排行榜见[高中地理](leaderboard/HighSchoolGeography.md)，☛查看[高中地理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=HighSchoolGeography)
<br>

#### （6）高中历史
评测样本举例：
> 回答以下选择题：1992年，邓小平到南方视察，围绕“什么是社会主义、怎样建设社会主义”做了重要讲话，下列与此相关的内容是（ ）   
(A) 社会主义的本质是解放生产力、发展生产力   
(B) 解放思想，实事求是，团结一致向前看   
(C) 以经济建设为中心   
(D) 非公有制经济是社会主义市场经济的重要组成部分   
>  

完整排行榜见[高中历史](leaderboard/HighSchoolHistory.md)，☛查看[高中历史badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=HighSchoolHistory)
<br>

#### （7）高中数学
评测样本举例：
> 回答以下选择题：下列命题中，是正确的全称命题的是( )
(A) 对数函数在定义域上是单调函数.   
(B) 对任意的a,b, 都有a^2+b^2-2a-2b+2<0 ;   
(C) 菱形的两条对角线相等；  
(D) exists x,sqrt(x^2)=x;   
>   

完整排行榜见[高中数学](leaderboard/HighSchoolMathematics.md)，☛查看[高中数学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=HighSchoolMathematics)
<br>

#### （8）高中物理
评测样本举例：
> 回答以下选择题：原计划的“铱”卫星通信系统是在距地球表面780 km的太空轨道上建立一个由77颗小卫星组成的星座。这些小卫星均匀分布在覆盖全球的7条轨道上，每条轨道上有11颗卫星，由于这一方案的卫星排布像化学元素“铱”原子的核外77个电子围绕原子核运动一样，所以称为“铱”星系统。后来改为由66颗卫星，分布在6条轨道上，每条轨道上由11颗卫星组成，仍称它为“铱”星系统。“铱”星系统的66颗卫星，其运行轨道的共同特点是（　　）    
(A) “铱”星运行轨道高于同步卫星轨道   
(B) 以地轴为中心的圆形轨道   
(C) 以地心为中心的圆形轨道  
(D) 轨道平面必须处于赤道平面内   
>  

完整排行榜见[高中物理](leaderboard/HighSchoolPhysics.md)，☛查看[高中物理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=HighSchoolPhysics)
<br>

#### （9）高中政治
评测样本举例：
> 回答以下选择题：国家鼓励民营企业依法进入更多领域,引入非国有资本参与国有企业改革,更好地激发非公有制经济的活力和创造力。这是因为（   ）    
(A) 非公有制经济具有规模小、投资少、经营灵活的特点   
(B) 国有经济在我国重要行业和关键领域占支配地位   
(C) 非公有制经济是我国经济社会发展的重要基础  
(D) 国家引导非公有制经济健康发展   
>   

完整排行榜见[高中政治](leaderboard/HighSchoolPolitics.md)，☛查看[高中政治badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=HighSchoolPolitics)
<br><br>


### 3.3 初中学科
☛☛完整排行榜见[初中学科](leaderboard/初中学科.md)<br>

#### （1）初中生物
评测样本举例：
> 回答以下选择题：日常生活中，下列不利于保护人体呼吸系统的做法是（    ）   
(A) 长时间大声说话能锻炼声带   
(B) 长跑时尽量不用嘴吸气   
(C) 哮喘患者应避免接触花粉等刺激物   
(D) 吃饭时不要边吃边说笑   
>   

完整排行榜见[初中生物](leaderboard/MiddleSchoolBiology.md)，☛查看[初中生物badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MiddleSchoolBiology)
<br>

#### （2）初中化学
评测样本举例：
> 回答以下选择题：下列物质由离子构成的是   
(A) 二氧化碳   
(B) 水银   
(C) 氯化钠   
(D) 水蒸气   
>   

完整排行榜见[初中化学](leaderboard/MiddleSchoolChemistry.md)，☛查看[初中化学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MiddleSchoolChemistry)
<br>

#### （3）初中语文
评测样本举例：
> 回答以下选择题：阅读下面两首诗。 使至塞上 王维 单车欲问边，属国过居延。 征蓬出汉塞，归雁入胡天。 大漠孤烟直，长河落日圆。 萧关逢候骑，都护在燕然。 汉江①临泛 王维 楚塞②三湘接，荆门九派③通。 江流天地外，山色有无中。 郡邑浮前浦，波澜动远空。 襄阳好风日，留醉与山翁。 【注释】①汉江：即汉水。②楚塞：指古代楚国地界。③九派：长江干流及其支流的统称。 对两首诗理解和分析不恰当的一项是（　　）   
(A) 王维的诗以“诗中有画”著称，这两首诗在意境创造上也很好地体现了这一特点。   
(B) 《使至塞上》首联写了诗人奉使出征，独当重任，到边疆察看，过居延属国的内容。   
(C) 《汉江临泛》尾联通过具体细腻的景物描写，表达了诗人对襄阳风物的热爱，也洋溢着积极乐观的情绪。   
(D) 《使至塞上》用一“直”一“圆”展现了边塞的壮阔；《汉江临泛》用一“浮”一“动”渲染了水势的磅礴。    
>    

完整排行榜见[初中语文](leaderboard/MiddleSchoolChinese.md)，☛查看[初中语文badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MiddleSchoolChinese)
<br>

#### （4）初中英语
评测样本举例：
> 回答以下选择题：The boy’s hair is ________ the girl’s hair.    
(A) than   
(B) shorter than   
(C) short than   
(D) shorter   
>    

完整排行榜见[初中英语](leaderboard/MiddleSchoolEnglish.md)，☛查看[初中英语badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MiddleSchoolEnglish)
<br>

#### （5）初中地理
评测样本举例：
> 回答以下选择题：印度的“绿色革命”运动，实现了（   ）   
(A) 促进了旅游业的发展   
(B) 工业产品大量出口   
(C) 提高了粮食产量，实现了粮食自给   
(D) 促进了电脑软件的研发   
>     
完整排行榜见[初中地理](leaderboard/MiddleSchoolGeography.md)，☛查看[初中地理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MiddleSchoolGeography)
<br>

#### （6）初中历史
评测样本举例：
> 回答以下选择题：北宋为了摆脱政治危机，实现富国强兵于1069年实行（ ）   
(A) 行省制  
(B) 商鞅变法  
(C) 王安石变法  
(D) 重文轻武的政策   
>

完整排行榜见[初中历史](leaderboard/MiddleSchoolHistory.md)，☛查看[初中历史badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MiddleSchoolHistory)
<br>

#### （7）初中数学
评测样本举例：
> 回答以下选择题：下列说法正确的是（    ）  
(A) 如果两个数互为倒数，那么它们的积一定是1  
(B) 两个正数互为倒数，其中一个数必大于1  
(C) 一个假分数的倒数一定小于本身  
(D) 如果一个数的倒数是它本身，那么这个数一定是1  
>  

完整排行榜见[初中数学](leaderboard/MiddleSchoolMathematics.md)，☛查看[初中数学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MiddleSchoolMathematics)
<br>

#### （8）初中物理
评测样本举例：
> 回答以下选择题：质量相等的A、B两实心物块，密度之比ρA∶ρB＝3∶2，分别放入足够多的水中，两物块静止时均漂浮且所受浮力分别为FA和FB，则浮力FA与FB之比是（　　）   
(A) 无法确定   
(B) 1∶1   
(C) 2∶3   
(D) 3∶2   
>  

完整排行榜见[初中物理](leaderboard/MiddleSchoolPhysics.md)，☛查看[初中物理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MiddleSchoolPhysics)
<br>

#### （9）初中政治
评测样本举例：
> 回答以下选择题：做自信的中国人要（   ）  
(A) 唯我独尊  
(B) 妄自尊大  
(C) 故步自封  
(D) 不卑不亢   
>  

完整排行榜见[初中政治](leaderboard/MiddleSchoolPolitics.md)，☛查看[初中政治badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MiddleSchoolPolitics)
<br><br>


### 3.4 小学学科
☛☛完整排行榜见[小学学科](leaderboard/小学学科.md)<br>

#### （1）小学语文
评测样本举例：
> 回答以下选择题：下列说法最得体的是（    ）  
(A) “嗨，老头，快告诉我电影院怎么走！”  
(B) “把你的电话号码（mǎ）说一遍。”   
(C) “叔叔，把报纸给我。”  
(D) “奶奶您好，我坐您旁边，可以吗？”   
>  

完整排行榜见[小学语文](leaderboard/PrimarySchoolChinese.md)，☛查看[小学语文badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=PrimarySchoolChinese)
<br>

#### （2）小学英语
评测样本举例：
> 回答以下选择题：—Can I have some water, please? ( )—______  
(A) Yes, I can.  
(B) Look at the watermelon.  
(C) Sure, here you are.  
(D) I’m OK.  
>

完整排行榜见[小学英语](leaderboard/PrimarySchoolEnglish.md)，☛查看[小学英语badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=PrimarySchoolEnglish)
<br>

#### （3）小学数学
评测样本举例：
> 回答以下选择题：某市出租车收费标准如下：3千米及3千米以内5元，超过3千米的部分按每千米1.4元收费（不足1千米时按1千米计算），妈妈打车去离家7.5千米的超市，她应付车费（）元。  
(A) 14   
(B) 11.3  
(C) 12  
(D) 13  
>   

完整排行榜见[小学数学](leaderboard/PrimarySchoolMathematics.md)，☛查看[小学数学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=PrimarySchoolMathematics)
<br>

#### （4）小学道德与法治
评测样本举例：
> 回答以下选择题：谁的想法是正确的（ ）  
(A) 小刚只想和性格一样，习惯一样，兴趣爱好相同的人交朋友  
(B) 晓红是急性子，丽丽是慢性子，但是晓红认为她俩也会相处的很好  
(C) 小明会上网，李刚不懂电脑，所以小明觉得他俩没有共同语言  
(D) 王梅认为不能和“不同”的同学打交道  
>  

完整排行榜见[小学道德与法治](leaderboard/PrimarySchoolEthics.md)，☛查看[小学道德与法治badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=PrimarySchoolEthics)
<br>

#### （5）小学科学
评测样本举例：
> 回答以下选择题：使用过的口罩在垃圾分类中属于（ ）。  
(A) 可回收垃圾  
(B) 其他垃圾  
(C) 有害垃圾  
(D) 厨余垃圾   
>  

完整排行榜见[小学科学](leaderboard/PrimarySchoolScience.md)，☛查看[小学科学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=PrimarySchoolScience)
<br><br><br>


## 4、法律排行榜
☛☛完整排行榜见[法律](leaderboard/法律.md)<br>

### 4.1 律师资格考试
#### （1）JEC-QA-KD
选择题，共1000道，参考[AGIEval](https://github.com/ruixiangcui/AGIEval)。<br>
完整排行榜见[JEC-QA-KD](leaderboard/JEC-QA-KD.md)，☛查看[JEC-QA-KD badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=JEC-QA-KD)
<br>

#### （2）JEC-QA-KD
选择题，共1000道，参考[AGIEval](https://github.com/ruixiangcui/AGIEval)。<br>
完整排行榜见[JEC-QA-CA](leaderboard/JEC-QA-CA.md)，☛查看[JEC-QA-CA badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=JEC-QA-CA)
<br>

#### （3）MMCU法律
完整排行榜见[MMCU法律](leaderboard/MMCU-法律.md)，☛查看[MMCU法律badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MMCU-法律)
<br><br><br>


## 5、行政公务排行榜
☛☛完整排行榜见[行政公务](leaderboard/行政公务.md)<br>

### 5.1 公务员考试
公务员考试行测选择题，共651道，参考[AGIEval](https://github.com/ruixiangcui/AGIEval)。
评测样本举例：
> 某乡镇进行新区规划，决定以市民公园为中心，在东南西北分别建设一个特色社区。这四个社区分别定为，文化区、休闲区、商业区和行政服务区。已知行政服务区在文化区的西南方向，文化区在休闲区的东南方向。   
根据以上陈述，可以得出以下哪项？   
(A)市民公园在行政服务区的北面    
(B)休闲区在文化区的西南   
(C)文化区在商业区的东北   
(D)商业区在休闲区的东南   
>  

完整排行榜见[公务员考试](leaderboard/考公.md)<br>
☛查看[公务员考试badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=kaogong)
<br><br><br>


## 6、心理健康排行榜
目前包含4个子项：MMCU心理，心理治疗学主治医师，心理咨询师，医学心理学。<br>
☛☛完整排行榜见[心理健康](leaderboard/心理健康.md)<br>

#### （1）MMCU心理
完整排行榜见[MMCU心理](leaderboard/MMCU-心理.md)，☛查看[MMCU心理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=MMCU-心理)
<br>

#### （2）心理治疗学主治医师
完整排行榜见[心理治疗学主治医师](leaderboard/CMB-医师考试-中级职称-心理治疗学主治医师.md)，☛查看[心理治疗学主治医师badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-心理治疗学主治医师)
<br>

#### （3）心理咨询师
完整排行榜见[心理咨询师](leaderboard/CMB-医师考试-中级职称-心理咨询师.md)，☛查看[心理咨询师badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-医师考试-中级职称-心理咨询师)
<br>

#### （4）医学心理学
完整排行榜见[医学心理学](leaderboard/CMB-专业知识考试-基础医学-医学心理学.md)，☛查看[医学心理学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CMB-专业知识考试-基础医学-医学心理学)
<br><br><br>


## 7、推理与数学计算排行榜
☛☛完整排行榜见[推理与数学计算](leaderboard/推理与数学计算.md)<br>

### 7.1 演绎推理
演绎推理（modus_tollens）选择题，共123道，参考[ISP](https://arxiv.org/abs/2306.09479)。

评测样本举例：
> 考虑以下语句：  
1.如果约翰是个好父母，那么约翰就是严格但公平的。   
2.约翰不严格但公平。   
结论：因此，约翰不是一个好父母。   
问题：根据陈述1.和2.，结论是否正确？   
回答：   
(A) 否   
(B) 是   
>   

完整排行榜见[演绎推理](leaderboard/演绎推理.md)<br>
☛查看[演绎推理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=dedReason)
<br><br><br>


### 7.2 常识推理
常识推理选择题，共99道，参考[ISP](https://arxiv.org/abs/2306.09479)。

评测样本举例：
> 以下是关于常识的选择题。   
问题：当某人把土豆放到篝火边的余烬中，此时余烬并没有在   
A、释放热量  
B、吸收热量   
>      

完整排行榜见[常识推理](leaderboard/常识推理.md)<br>
☛查看[常识推理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=commonsense)
<br><br><br>


### 7.3 符号推理BBH
学术界最常用的符号推理评测集，包含23个子任务，详细介绍见[BBH](https://easyllm.site/static/benchmarks.html)。
评测样本举例：
> Task description: Answer questions about which times certain events could have occurred.  
Q: Today, Emily went to the museum. Between what times could they have gone?   
We know that:   
Emily woke up at 1pm.   
Elizabeth saw Emily reading at the library from 2pm to 4pm.   
Jessica saw Emily watching a movie at the theater from 4pm to 5pm.    
Leslie saw Emily waiting at the airport from 5pm to 6pm.   
William saw Emily buying clothes at the mall from 6pm to 7pm.   
The museum was closed after 7pm.   
Between what times could Emily have gone to the museum?   
Options:   
(A) 1pm to 2pm   
(B) 6pm to 7pm   
(C) 5pm to 6pm   
(D) 2pm to 4pm   
A:    
> 

完整排行榜见[BBH](leaderboard/符号推理BBH.md)<br>
☛查看[BBH符号推理badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=BBH)
<br><br><br>


### 7.4 算术能力
考查大模型的数学基础能力之算数能力，测试题目为1000以内的整数加减法、不超过2位有效数字的浮点数加减乘除。
举例：166 + 215 + 53 = ？，0.97 + 0.4 / 4.51 = ？

完整排行榜见[arithmetic](leaderboard/arithmetic.md)<br>
☛查看[算术能力badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=arithmetic)
<br><br><br>


### 7.5 七八九年级数学
七/八/九年级的平均分计入总分。<br>
评分标准：七、八、九年级分别有40道题、21道题、36道题，所有题目都只判断对错（没有中间分数）。对于任何题目，只有模型response完全正确才给分，部分正确或错误都不得分。<br>
评测样本举例：
> 因式分解：3x^2y-12xy+12y

完整排行榜见[初中数学](leaderboard/middle-school-math.md)<br>
☛查看[七年级数学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=Grade7Math-zh)
☛查看[八年级数学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=Grade8Math-zh)
☛查看[九年级数学badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=Grade9Math-zh)
<br><br><br>


### 7.6 表格问答
专门考查大模型对表格的理解分析能力，常用于数据分析。    
评测样本举例：
> 姓名,年龄,性别,国籍,身高(cm),体重(kg),学历   
张三,28,男,中国,180,70,本科   
Lisa,33,女,美国,165,58,硕士   
Paulo,41,男,巴西,175,80,博士   
Miyuki,25,女,日本,160,50,大专   
Ahmed,30,男,埃及,175,68,本科   
Maria,29,女,墨西哥,170,65,硕士   
Antonio,36,男,西班牙,182,75,博士  
基于这个表格回答：学历最低的是哪国人？
> 

完整排行榜见[tableqa](leaderboard/表格问答.md)<br>
☛查看[数据分析badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=tableqa)
<br><br><br>


### 7.7 高中奥林匹克数学竞赛
2024年预赛试题，参考[Math24o](https://github.com/CLUEbenchmark/Math24o)。
评测样本举例：
> 设集合 $S=\{1, 2, 3, \cdots, 9 9 7, 9 9 8 \}$，集合 $S$ 的 $k$ 个 $499$ 元子集 $A_{1},A_{2}, \cdots, A_{k}$ 满足：对 $S$ 中任一二元子集 $B$，均存在 $i \in\{1, 2, \cdots, k \}$，使得 $B \subset A_{i}$。求 $k$ 的最小值。
> 

完整排行榜见[高中奥林匹克数学竞赛](leaderboard/Math24o.md)<br>
☛查看[高中奥林匹克数学竞赛badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=Math24o)
<br><br><br>


## 8、语言与指令遵从排行榜
☛☛完整排行榜见[语言与指令遵从](leaderboard/语言与指令遵从.md)<br>

### 8.1 成语理解
给定上下文，选择最匹配的成语。

评测样本举例：
> 说完作品的优点,咱们再来聊聊为何说它最后的结局____,片子本身提出的话题观点很尖锐,“扶弟魔”也成为众多当代年轻人婚姻里的不定因素,所以对于这种过于敏感的东西,片子的结局仅仅只是以弟弟的可爱化解了姐姐的心结,最后选择陪伴照顾...   
给上文空格处选择最合适的成语或俗语：   
(A) 有条有理   
(B) 偏听偏信   
(C) 狗尾续貂   
(D) 半壁江山   
(E) 身家性命   
(F) 胆小如鼠   
(G) 独善其身    
> 

完整排行榜见[成语理解](leaderboard/成语理解.md)<br>
☛查看[成语理解badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=idiom)
<br><br><br>


### 8.2 情感分析
分析用户评论的情感属性，消极或积极。

评测样本举例：
> 用了几天，发现很多问题，无线网容易掉线，屏幕容易刮花，打开网页容易死掉，不值的买   
以上用户评论是正面还是负面？    
(A) 负面   
(B) 正面   
>    

完整排行榜见[情感分析](leaderboard/情感分析.md)<br>
☛查看[情感分析badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=sentiment)
<br><br><br>


### 8.3 文本蕴含
文本蕴含，判断两个句子之间的语义关系：蕴含、中立、矛盾，参考[OCNLI](https://arxiv.org/abs/2010.05444)。

评测样本举例：
> 句子一：农机具购置补贴覆盖到全国所有农牧业县(场),中央财政拟安排资金130亿元,比上年增加90亿元   
句子二：按农民人数发放补贴  
以上两个句子是什么关系？   
(A)蕴含  
(B)中立  
(C)矛盾   
>   

完整排行榜见[文本蕴含](leaderboard/文本蕴含.md)<br>
☛查看[文本蕴含badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=textEntail)
<br><br><br>


### 8.4 分类能力
评测样本举例：
> 将下列单词按词性分类。    
> 狗，追，跑，大人，高兴，树

完整排行榜见[classification](leaderboard/分类能力.md)<br>
☛查看[分类能力badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=classification)
<br><br><br>


### 8.5 信息抽取
评测样本举例：  
> “中信银行3亿元，交通银行增长约2.7亿元，光大银行约1亿元。”    
> 提取出以上文本中的所有组织机构名称

完整排行榜见[extract](leaderboard/信息抽取.md)<br>
☛查看[信息抽取能力badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=extract)
<br><br><br>


### 8.6 阅读理解
阅读理解能力是一种符合能力，考查针对给定信息的理解能力。
依据给定信息的种类，可以细分为：文章问答、表格问答、对话问答……    
评测样本举例：
> 牙医：好的，让我们看看你的牙齿。从你的描述和我们的检查结果来看，你可能有一些牙齦疾病，导致牙齿的神经受到刺激，引起了敏感。此外，这些黑色斑点可能是蛀牙。  
病人：哦，真的吗？那我该怎么办？   
牙医：别担心，我们可以为你制定一个治疗计划。我们需要首先治疗牙龈疾病，然后清除蛀牙并填充牙洞。在此过程中，我们将确保您感到舒适，并使用先进的技术和材料来实现最佳效果。   
病人：好的，谢谢您，医生。那么我什么时候可以开始治疗？   
牙医：让我们为您安排一个约会。您的治疗将在两天后开始。在此期间，请继续刷牙，使用牙线，并避免吃过于甜腻和酸性的食物和饮料。   
病人：好的，我会的。再次感谢您，医生。   
牙医：不用谢，我们会尽最大的努力帮助您恢复健康的牙齿。   
基于以上对话回答：病人在检查中发现的牙齿问题有哪些？
> 

完整排行榜见[mrc](leaderboard/阅读理解.md)<br>
☛查看[阅读理解能力badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=mrc)
<br><br><br>


### 8.7 C3中文阅读理解
经典中文阅读理解选择题，共763道，参考[C3](https://github.com/nlpdata/c3)。
评测样本举例：
> 我公司现招聘一名经济法方面的律师，要求：年龄在35岁以下，至少会一门外语，有三年以上工作经验。欢迎符合条件者前来应聘。  
根据上文回答以下选择题：应聘这个工作的人必须：   
(A) 超过35岁   
(B) 有管理经验   
(C) 会说普通话   
(D) 工作三年以上    
>    

完整排行榜见[C3](leaderboard/C3中文阅读理解.md)<br>
☛查看[C3中文阅读理解badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=mrcC3)
<br><br><br>


### 8.8 代词理解CLUEWSC
中文指代消解任务，参考[CLUEWSC2020](https://github.com/CLUEbenchmark/CLUEWSC2020)。
评测样本举例：
> 少平仍然不知道怎样给奶奶说清他姐夫的事，就只好随口说：“他犯了点错误，人家让他劳教！”  
上述文本中的“他犯了点错误”中的“他”是指少平吗？   
选项：(A)是   
(B)否      
>    

完整排行榜见[CLUEWSC](leaderboard/代词理解CLUEWSC.md)<br>
☛查看[代词理解CLUEWSC badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CLUEWSC)
<br><br><br>


### 8.9 诗词匹配CCPM
中国古典诗歌匹配，给定中国古典诗歌的现代问描述，要求从候选的四句诗中选出与现代文描述语义匹配的那一句。
利用古典诗歌和现代文翻译的平行语料构建正确选项，并利用正确选项从古代诗歌语料库中利用相似检索构造出错误候选。
参考[CCPM](https://github.com/THUNLP-AIPoet/CCPM)。
评测样本举例：
> 昏暗的灯熄灭了又被重新点亮。   
上述文本最匹配下面哪句诗：   
(A)渔灯灭复明   
(B)残灯灭又然   
(C)残灯暗复明   
(D)残灯灭又明   
>    

完整排行榜见[CCPM](leaderboard/诗词匹配CCPM.md)<br>
☛查看[诗词匹配CCPM badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=CCPM)
<br><br><br>


### 8.10 中文指令遵从
参考谷歌IFEval，并将其翻译和适配到中文，精选9类25种指令，说明如下：
![lin](pic/IFEval.jpg)

完整排行榜见[IFEval](leaderboard/中文指令遵从.md)<br>
☛查看[中文指令遵从badcase](http://easyllm.site/static/badcase/badcase-of-benchmark.html?benchmark=IFEval-zh)
<br><br><br>


## 🌐各项能力评分
评分方法：从各个维度给大模型打分，每个维度都对应一个评测数据集，包含若干道题。
每道题依据大模型回复质量给1~5分，将评测集内所有题的得分累加并归一化为100分制，即作为最终得分。

所有评分数据详见[alldata](leaderboard/alldata.md)
<br><br>


## ⚖️原始评测数据
包含各维度评测集以及大模型输出结果，详见本项目的[eval文件目录](eval)
<br><br>


## 为什么做榜单？
- 大模型百花齐放，也参差不齐。不少媒体的宣传往往夸大其词，避重就轻，容易混淆视听；而某些公司为了PR，也过分标榜自己大模型的能力，动不动就“达到chatgpt水平”，动不动就“国内第一”。
所谓“外行看热闹，内行看门道”，业界急需一股气流，摒弃浮躁，静下心来打磨前沿技术，真真正正用技术实力说话。这就少不了一个公开、公正、公平的大模型评测系统，把各类大模型的优点、不足一一展示出来。
如此，大家既能把握当下的发展水平、与国外顶尖技术的差距，也能更加清晰地看明白未来的努力方向，而不被资本热潮、舆论热潮所裹挟。
- 对于产业界来说，特别是对于不具备大模型研发能力的公司，熟悉大模型的技术边界、高效有针对性地做大模型技术选型，在现如今显得尤为重要。
而一个公开、公正、公平的大模型评测系统，恰好能够提供应有的助力，避免重复造轮子，避免因技术栈不同而导致不必要的争论，避免“鸡同鸭讲”。
- 对于大模型研发人员，包括对大模型技术感兴趣的人、学术界看中实践的人，各类大模型的效果对比，反应出了背后不同技术路线、技术方法的有效性，这就提供了非常好的参考意义。
不同大模型的相互参考、借鉴，帮忙大家躲过不必要的坑、避免重复实验带来的资源浪费，有助于整个大模型生态圈的良性高效发展。

## 大模型选型及评测交流群
先加小编微信，后拉入群，备注“加群”<br>
![lin](pic/qrcode-wxgroup.jpg)
<br><br><br><br>
关注大模型评测微信公众号，及时获取最新评测信息<br>
![lin](pic/qrcode-gzh.jpg)
