# LLMTS


Some other nice llm for time-series repositories:

[creyesp/large-time-series-model-papers](https://github.com/creyesp/large-time-series-model-papers)

[uctb/TSFM](https://github.com/uctb/TSFM)

[wpf535236337/LLMs4TS](https://github.com/wpf535236337/LLMs4TS)

[songqiang321/Time-Series-Papers](https://github.com/songqiang321/Time-Series-Papers?tab=readme-ov-file#llm-framework)


https://github.com/ddz16/TSFpaper?tab=readme-ov-file#llm-large-language-model

# Content

- <a href = "#LLM-Time-Series-Forecasting">LLM Time Series Forecasting</a>


# [TS Foundation Model](#content)
|  Task  |    Data |   Name|  LLM  | Paper   |    Code    |   Publication    |
| :-: | :-: | :-: | :-: | :-:  | :-: | - |
| Paper Nums:?+ | <img width=150/> | <img width=220/>  |  <img width=150/>  |   | |   <img width=300/> |
| TS Forecasting |  ?  |  Sundial | Transformer  <br> Decoder-Only |  [Sundial: A Family of Highly Capable Time Series Foundation Models](https://arxiv.org/abs/2409.16040) | [Pytorch](https://github.com/Time-MoE/Time-MoE)  <br>![Stars](https://img.shields.io/github/stars/Time-MoE/Time-MoE?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/Time-MoE/Time-MoE?color=critical&style=social)  | ICML 2025
| TS Forecasting |  ?  |  Timer-XL | Transformer  <br> Decoder-Only |  [Timer-XL: Long-Context Transformers for Unified Time Series Forecasting](https://arxiv.org/abs/2410.04803) | [Pytorch](https://github.com/thuml/Timer-XL)  <br>![Stars](https://img.shields.io/github/stars/thuml/Timer-XL?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/thuml/Timer-XL?color=critical&style=social)  | ICLR 2025
| TS Forecasting |  Time300B  |  Time-MoE | Transformer & MoE <br> Decoder-Only |  [Time-MoE: Billion-Scale Time Series Foundation Models with Mixture of Experts](https://arxiv.org/abs/2409.16040) | [Pytorch](https://github.com/Time-MoE/Time-MoE)  <br>![Stars](https://img.shields.io/github/stars/Time-MoE/Time-MoE?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/Time-MoE/Time-MoE?color=critical&style=social)  | ICLR 2025
| TS Forecasting |  ?  |    TTMs|   TSMixer  |  [Tiny Time Mixers (TTMs): Fast Pre-trained Models for Enhanced Zero/Few-Shot Forecasting of Multivariate Time Series](https://arxiv.org/abs/2401.03955) | [Pytorch](https://github.com/ibm-granite/granite-tsfm)  <br>![Stars](https://img.shields.io/github/stars/ibm-granite/granite-tsfm?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/ibm-granite/granite-tsfm?color=critical&style=social)  | NIPS 2024
|  TS Forecasting  <br> probabilistic  |  [monash](https://forecastingdata.org/)  <br> GluonTS   |  Moirai   |  T5 <br> Encoder-Only |  [Unified Training of Universal Time Series Forecasting Transformers](https://proceedings.mlr.press/v235/woo24a.html) | [Pytorch](https://github.com/SalesforceAIResearch/uni2ts)  <br>![Stars](https://img.shields.io/github/stars/SalesforceAIResearch/uni2ts?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/SalesforceAIResearch/uni2ts?color=critical&style=social)  | ICML 2024
|  TS Forecasting  <br> probabilistic  | Google Trends <br> Wiki <br>    Informer ..|  TimeFM   |  Transformer <br> Decoder-Only |  [A decoder-only foundation model for time-series forecasting](https://proceedings.mlr.press/v235/das24c.html) | [Pytorch](https://github.com/google-research/timesfm)  <br>![Stars](https://img.shields.io/github/stars/google-research/timesfm?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/google-research/timesfm?color=critical&style=social)  | ICML 2024
| TS Forecasting |       |     | |  [Less is More: Unlocking Specialization of Time Series Foundation Models via Structured Prunings](https://arxiv.org/abs/2505.23195) | None   | Arxiv 2025
| Foundation <br> ST | TaxiBJ <br> Crawd <br> BikeNYC <br> Cellular <br> TDrive <br> TrafficSH |  Transformer backbone |  UniST | [UniST: A Prompt-Empowered Universal Model for Urban Spatio-Temporal Prediction](https://dl.acm.org/doi/abs/10.1145/3637528.3671662) |  [Pytorch](https://github.com/tsinghua-fib-lab/UniST)  <br>![Stars](https://img.shields.io/github/stars/tsinghua-fib-lab/UniST?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/tsinghua-fib-lab/UniST?color=critical&style=social)  | KDD 2024

# [LLM Time Series Forecasting](#content)
|  Task  |    Data |   Name|  LLM  | Paper   |    Code    |   Publication    |
| :-: | :-: | :-: | :-: | :-:  | :-: | - |
| Paper Nums:?+ | <img width=150/> | <img width=220/>  |  <img width=150/>  |   | |   <img width=300/> |
| TS Forecasting |  Time300B  |    Time-MoE | Transformer & MoE <br> Decoder-Only |  [Time-MoE: Billion-Scale Time Series Foundation Models with Mixture of Experts](https://arxiv.org/abs/2409.16040) | [Pytorch](https://github.com/Time-MoE/Time-MoE)  <br>![Stars](https://img.shields.io/github/stars/Time-MoE/Time-MoE?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/Time-MoE/Time-MoE?color=critical&style=social)  | Arxiv 2024
| Long/Short Forecasting  <br> Imputation  <br> Anomaly  <br> Classification|  LOTSA  |  MOMENT |  Transformer <br> Encoder-Only |  [MOMENT: A Family of Open Time-series Foundation Models](https://proceedings.mlr.press/v235/goswami24a.html) | [Pytorch](https://github.com/moment-timeseries-foundation-model/moment-research)  <br>![Stars](https://img.shields.io/github/stars/moment-timeseries-foundation-model/moment-research?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/moment-timeseries-foundation-model/moment-research?color=critical&style=social)  | ICML 2024
|  TS Forecasting  <br> probabilistic  |  [monash](https://forecastingdata.org/)  <br> GluonTS   |  Moirai   |  T5 <br> Encoder-Only |  [Unified Training of Universal Time Series Forecasting Transformers](https://proceedings.mlr.press/v235/woo24a.html) | [Pytorch](https://github.com/SalesforceAIResearch/uni2ts)  <br>![Stars](https://img.shields.io/github/stars/SalesforceAIResearch/uni2ts?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/SalesforceAIResearch/uni2ts?color=critical&style=social)  | ICML 2024
|  TS Forecasting  <br> probabilistic  | Google Trends <br> Wiki <br>    Informer ..|  TimeFM   |  Transformer <br> Decoder-Only |  [A decoder-only foundation model for time-series forecasting](https://proceedings.mlr.press/v235/das24c.html) | [Pytorch](https://github.com/google-research/timesfm)  <br>![Stars](https://img.shields.io/github/stars/google-research/timesfm?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/google-research/timesfm?color=critical&style=social)  | ICML 2024
|  TS Forecasting  <br> Few Shot <br> Zero Shot  |  [monash](https://forecastingdata.org/)   <br>  LibCity  | TTM  |   TSMixer   |  [Tiny Time Mixers (TTMs): Fast Pre-trained Models for Enhanced Zero/Few-Shot Forecasting of Multivariate Time Series](https://openreview.net/forum?id=3O5YCEWETq&noteId=RdR2bNLzsY) | [Pytorch](https://github.com/ibm-granite/granite-tsfm)  <br>![Stars](https://img.shields.io/github/stars/ibm-granite/granite-tsfm?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/ibm-granite/granite-tsfm?color=critical&style=social)  | ICML 2024
|  TS Forecasting  <br> Few Shot <br> Zero Shot  |  [TimesNet_data](https://github.com/thuml/Time-Series-Library)    |  Time-LLM   | GPT-2 <br> llama2-7B <br> Decoder-Only |  [Time-LLM: Time Series Forecasting by Reprogramming Large Language Models](https://openreview.net/forum?id=Unb5CVPtae) | [Pytorch](https://github.com/KimMeen/Time-LLM)  <br>![Stars](https://img.shields.io/github/stars/KimMeen/Time-LLM?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/KimMeen/Time-LLM?color=critical&style=social)  | ICLR 2024
| Multi City <br>  Long/Short  <br>  Few/Zero |  TaxiBJ <br> Crowd <br> Cellular <br> BikeNYC <br> TrafficJN...   |    UniST  |  Transformer <br> Encoder-Decoder   | [UniST: A Prompt-Empowered Universal Model for Urban Spatio-Temporal Prediction](https://dl.acm.org/doi/abs/10.1145/3589334.3645434) | [Pytorch](https://github.com/tsinghua-fib-lab/UniST)  <br>![Stars](https://img.shields.io/github/stars/tsinghua-fib-lab/UniST?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/tsinghua-fib-lab/UniST?color=critical&style=social)  | KDD 2024
| Cross Domain |  [TimesNet_data](https://github.com/thuml/Time-Series-Library)   |    UniTime  |  GPT-2 <br> Decoder-Only   | [UniTime: A Language-Empowered Unified Model for Cross-Domain Time Series Forecasting](https://dl.acm.org/doi/abs/10.1145/3589334.3645434) | [Pytorch](https://github.com/liuxu77/UniTime)  <br>![Stars](https://img.shields.io/github/stars/liuxu77/UniTime?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/liuxu77/UniTime?color=critical&style=social)  | WWW 2024
| Zero TS Forecasting  <br> probabilistic |  Darts <br> [monash](https://forecastingdata.org/)  <br> Informer  |   LLMTIME |  GPT-2 <br> llama2-70B |  [Large Language Models Are Zero-Shot Time Series Forecasters](https://openreview.net/forum?id=md68e8iZK1&noteId=BYd09USAyS) | [Pytorch](https://github.com/ngruver/llmtime)  <br>![Stars](https://img.shields.io/github/stars/ngruver/llmtime?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/ngruver/llmtime?color=critical&style=social)  | NIPS 2023
| Long/Short <br> Few/Zero  <br> Imputation  <br> Anomaly  <br> Classification |  [TimesNet_data](https://github.com/thuml/Time-Series-Library)  |   GPT4TS |  GPT-2  <br> Decoder-Only  |  [One Fits All: Power General Time Series Analysis by Pretrained LM](https://openreview.net/forum?id=gMS6FVZvmF) | [Pytorch](https://github.com/DAMO-DI-ML/NeurIPS2023-One-Fits-All)  <br>![Stars](https://img.shields.io/github/stars/DAMO-DI-ML/NeurIPS2023-One-Fits-All?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/DAMO-DI-ML/NeurIPS2023-One-Fits-All?color=critical&style=social)  | NIPS 2023
| TS Forecasting  <br> probabilistic |    [monash](https://forecastingdata.org/)  <br> GluonTS  |   Lag-Llama  |  llama-frame  <br> Decoder-Only |  [Lag-Llama: Towards Foundation Models for Time Series Forecasting](https://openreview.net/forum?id=md68e8iZK1&noteId=BYd09USAyS) | [Pytorch](https://github.com/kashif/pytorch-transformer-ts)  <br>![Stars](https://img.shields.io/github/stars/kashif/pytorch-transformer-ts?color=critical&style=social) <br>![Forks](https://img.shields.io/github/forks/kashif/pytorch-transformer-ts?color=critical&style=social)  | NIPS 2023



# [Conferences](#content)

❗ It is highly recommended to utilize [dblp](https://dblp.uni-trier.de/) and [Aminer](https://www.aminer.cn/conf) (in Chinese) to search.

Some more useful websites:
- CCF conference deadlines: https://ccfddl.github.io/
- Conference eye (会议之眼): https://www.conferenceeye.cn/#/layout/home
- Call4Papers: http://123.57.137.208/ccf/ccf-8.jsp
- Conference list: http://www.conferencelist.info/upcoming.html
- PMLR: https://proceedings.mlr.press/    （contains ICML, AISTATS, ACML, UAI, etc）
## Table of Conferences



