# Paper Reading

Reading lists for papers, including but not limited to Natural Language Processing (NLP).

- [Deep Learning in NLP](#deep-learning-in-nlp)
- [Debiasing](#debiasing)
- [Information Theory](#information-theory)
- [Dataset Construction](#dataset-construction)
- [Bias Suppression](#bias-suppression)
- [Others](#others)
***

## Uncategorized
* **Thinking Fair and Slow**: "“Thinking” Fair and Slow: On the Efficacy of Structured Prompts for Debiasing Language Models". EMNLP(2024) [[PDF]](https://aclanthology.org/2024.emnlp-main.13/)
* **Regard Dataset**: "The Woman Worked as a Babysitter: On Biases in Language Generation". EMNLP-IJCNLP(2019) [[PDF]](https://aclanthology.org/D19-1339/)[[CODE]](https://github.com/ewsheng/nlg-bias)
* **Regard V3**: "Towards Controllable Biases in Language Generation". EMNLP-Findings(2020) [[PDF]](https://aclanthology.org/2020.findings-emnlp.291/)[[CODE]](https://github.com/ewsheng/controllable-nlg-biases)
* **Bias in Bios**: "Bias in Bios: A Case Study of Semantic Representation Bias in a High-Stakes Setting". FAT(2019) [[PDF]](https://arxiv.org/pdf/1901.09451)[[CODE]](https://github.com/Microsoft/biosbias)
* **Tree Structure Reasoning**: "TREA: Tree-Structure Reasoning Schema for Conversational Recommendation". ACL(2023) [[PDF]](https://aclanthology.org/2023.acl-long.167/)[[CODE]](https://github.com/WindyLee0822/TREA)
* **SEER**: "SEER: Facilitating Structured Reasoning and Explanation via Reinforcement Learning". ACL(2024) [[PDF]](https://aclanthology.org/2024.acl-long.321/)[[CODE]](https://github.com/Chen-GX/SEER)
* **TrustLLM**: "Trustllm: Trustworthiness in large language models". ICML(2024) [[PDF]](https://arxiv.org/abs/2401.05561)[[CODE]](https://github.com/HowieHwong/TrustLLM)[[website]](https://howiehwong.github.io/TrustLLM/index.html)
* **Entailment Trees**: "Explaining Answers with Entailment Trees". EMNLP(2021) [[PDF]](https://aclanthology.org/2021.emnlp-main.585/)[[CODE]](https://allenai.org/data/entailmentbank)
* **LLM Data Annotation**: "Large Language Models for Data Annotation and Synthesis: A Survey". EMNLP(2024) [[PDF]](https://aclanthology.org/2024.emnlp-main.54.pdf)
* **Free-Text Explanation**: "Reframing Human-AI Collaboration for Generating Free-Text Explanations". NAACL(2022) [[PDF]](https://aclanthology.org/2022.naacl-main.47.pdf)[[CODE]](https://github.com/allenai/few_shot_explanations/)
* **Bias-NLI**: "On Measuring and Mitigating Biased Inferences of Word Embeddings". AAAI(2019) [[PDF]](https://arxiv.org/pdf/1908.09369)
* **Gaps**: "The Gaps between Pre-train and Downstream Settings in Bias Evaluation and Debiasing". COLING(2025) [[PDF]](https://arxiv.org/pdf/2401.08511)
* **Self-Correction**: "The Capacity for Moral Self-Correction in Large Language Models". ArXiv(2023) [[PDF]](https://arxiv.org/abs/2302.07459)
* **BBQ**: "BBQ: A Hand-Built Bias Benchmark for Question Answering ". ACL-Findings(2022) [[PDF]](https://aclanthology.org/2022.findings-acl.165.pdf)[[CODE]](https://github.com/nyu-mll/BBQ)
* **BNLI**: "Evaluating gender bias of pre-trained language models in natural language inference by considering all labels". LREC-COLING(2024) [[PDF]](https://aclanthology.org/2024.lrec-main.566/)
* **Adversarial NLI**: "Adversarial NLI: A New Benchmark for Natural Language Understanding". ACL(2020) [[PDF]](https://aclanthology.org/2020.acl-main.441.pdf)
* **SEAT**: "On Measuring Social Biases in Sentence Encoders". NAACL(2019) [[PDF]](https://aclanthology.org/N19-1063/)
* **Implicit Rangking** "A Study of Implicit Ranking Unfairness in Large Language Models". EMNLP Findings(2024) [[PDF]](https://aclanthology.org/2024.findings-emnlp.467.pdf) [[CODE]](https://github.com/XuChen0427/Implicit_Rank_Unfairness)
* **OCCUGENDER** "Causally Testing Gender Bias in LLMs: A Case Study on Occupational Bias". NeurIPS(2024) [[PDF]](https://arxiv.org/abs/2212.10678) [[CODE]](https://github.com/chenyuen0103/gender-bias)
* **Salmon Paper** "Stereotyping Norwegian salmon: An inventory of pitfalls in fairness benchmark datasets". ACL(2021) [[PDF]](https://aclanthology.org/2021.acl-long.81/)
* **Romantic Relationship Prediction** "On the Influence of Gender and Race in Romantic Relationship Prediction from Large Language Models". EMNLP(2024) [[PDF]](https://aclanthology.org/2024.emnlp-main.29.pdf)
* **Theory-Grounded** "Theory-Grounded Measurement of U.S. Social Stereotypes in English Language Models". NAACL(2022) [[PDF]](https://aclanthology.org/2022.naacl-main.92/)
* **Marked Personas** "Marked Personas: Using Natural Language Prompts to Measure Stereotypes in Language Models". ACL(2024) [[PDF]](https://aclanthology.org/2023.acl-long.84/)
* **SODAPOP** "SODAPOP: Open-Ended Discovery of Social Biases in Social Commonsense Reasoning Models". EACL(2023) [[PDF]](https://aclanthology.org/2023.eacl-main.116/)
* **DDRel Dataset** "DDRel: A New Dataset for Interpersonal Relation Classification in Dyadic Dialogues" AAAI(2021) [[PDF]](https://arxiv.org/abs/2012.02553)
* **Hiring Decisions** "Do Large Language Models Discriminate in Hiring Decisions on the Basis of Race, Ethnicity, and Gender?". ACL(2024) [[PDF]](https://aclanthology.org/2024.acl-short.37/)
* **First Name Biases** "Nichelle and Nancy: The Influence of Demographic Attributes and Tokenization Length on First Name Biases" ACL(2023) [[PDF]](https://aclanthology.org/2023.acl-short.34/)
* **ORPO** "ORPO: Monolithic Preference Optimization without Reference Model". EMNLP(2024) [[PDF]](https://aclanthology.org/2024.emnlp-main.626.pdf)
* **OPT** "OPT: Open Pre-trained Transformer Language Models". ArXiv(2022) [[PDF]](https://arxiv.org/pdf/2205.01068)
* **Word Meanings Adapt** "Understanding the Semantic Space:  How Word Meanings Dynamically Adapt in the Context of a Sentence". SemSpace(2021) [[PDF]](https://aclanthology.org/2021.semspace-1.1/)
* **Answer is all you need** "Answer is All You Need: Instruction-following Text Embedding via Answering the Question" ACL(2024) [[PDF]](https://aclanthology.org/2024.acl-long.27.pdf)



## Deep Learning in NLP
* **Data Augmentation**: "A Survey of Data Augmentation Approaches for NLP". ACL-Findings(2021) [[PDF]](https://arxiv.org/abs/2105.03075)
* **RAG**: "Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks". NeurIPS(2020) [[PDF]](https://proceedings.neurips.cc/paper/2020/file/6b493230205f780e1bc26945df7481e5-Paper.pdf)
* **DPR**: "Dense Passage Retrieval for Open-Domain Question Answering". EMNLP(2020) [[PDF]](https://aclanthology.org/2020.emnlp-main.550.pdf)

## Debiasing

### Survey
* **Empirical Survey**: "An Empirical Survey of the Effectiveness of Debiasing Techniques for Pre-trained Language Models". ACL(2022) [[PDF]](https://aclanthology.org/2022.acl-long.132/)

### Measure
* **Measure Biases&Harms**: "On Measures of Biases and Harms in NLP". AACL(2022) [[PDF]](https://arxiv.org/pdf/2108.03362)[[CODE]](https://github.com/mcgill-nlp/bias-bench) 


### Static Embeddings
* **Gender-Neutral**: "Gender-preserving Debiasing for Pre-trained Word Embeddings". ACL(2019) [[PDF]](https://aclanthology.org/P19-1160) [[CODE]](https://github.com/kanekomasahiro/gp_debias)



### Pre-trained Language Models
* **Attention-Debiasing**: "Debiasing Pretrained Text Encoders by Paying Attention to Paying Attention". EMNLP(2022) [[PDF]](https://aclanthology.org/2022.emnlp-main.651.pdf) [[CODE]](https://github.com/YacineGACI/AttenD)
* **Debiasing Masks**: "Debiasing Masks: A New Framework for Shortcut Mitigation in NLU". EMNLP(2022) [[PDF]](https://aclanthology.org/2022.emnlp-main.517.pdf) [[CODE]](https://github.com/mariomeissner/shortcut-pruning)
* **DebiasGAN**: "DebiasGAN: Eliminating Position Bias in News Recommendation with Adversarial Learning". EMNLP(2022) [[PDF]](https://aclanthology.org/2022.findings-emnlp.213.pdf) [[CODE]](https://github.com/wuch15/DebiasGAN)
* **DCLR**: "Debiased Contrastive Learning of Unsupervised Sentence Representations". ACL(2022) [[PDF]](https://aclanthology.org/2022.acl-long.423.pdf) [[CODE]](https://github.com/RUCAIBox/DCLR)
* **Self-Debiasing**: "Self-Diagnosis and Self-Debiasing: A Proposal for Reducing Corpus-Based Bias in NLP". TACL(2021) [[PDF]](https://watermark.silverchair.com/tacl_a_00434.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAArYwggKyBgkqhkiG9w0BBwagggKjMIICnwIBADCCApgGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMYGeU2N4-gUef3wyAAgEQgIICafQM-eWrfC20qgWkLpeWW3pgyT48xrTg2fccf0We0h7YjeV52uHi3UsLqAlqmxuWMAvUiVSbLJNPUrgMi8RiWofH1YRb5fX-0sOEvBWVUxVn02nk6arPWkAEex5PVjN1PR0Q5T9SZDK_ulcLhtCsKBua91WHoQ8I8VmNj30wSg2J9rPQxAmKdgMYlajQBIcpsT0uwxg7Y0GJyH9zNyUmtVOSBz6CqLqBylKMVLUmYBrz6hZW-BChC4CI5zpM7xHYC33qQA5CiZb7RW-m2iywa_WrjU6zKihSPKh856xMPaPsVF3CwjMMoEKjN9cAMhBKK0Ml1u7yDWGcL3gZJSQE9GQF6k0gezba8IfQVD9IuIZV6H2tocJxxhrqq-hXlAumiYJqkfsZLUB6vhmJXN3e2jdvnyyRrNTouPIx5f7_ELYKLpdVXLpNFrokqANu4Ok9LXH1aU3dQwG_yY9LccCi0-ahxXtdwTquUxJBnO0cWojEYQnercGIPKyJtrMzi-58behtOPch6vTVUt0xsJvJKk5Iz7UcbzbsPxl9lqgrZ9m91AaTMa0BgFL67EyYNvfiahnhH90ddAamaBsqEi-oaKv2bybpFpZ93k3t2IZ_8JVbJKT7rSiYsxjTEyDODl6ODrm6AoQUICo7JKd1c4BBxZvhWGyQczIde360cvyaW6gU8npAaoM-j7qc0b-n5-e_rjrbJGc26A40ONaopZwg_fj1fURNWsNq5LJ5ICOU8nmioabJk-r6dusErwEWP4M9iOWEe1FhLYaOm47dJC8rnpv4szZPXfzHfHCFU-gnaWI9lNnCeZcPplVo) [[CODE]](https://github.com/timoschick/self-debiasing)
* **SENT-DEBIAS**: "Towards Debiasing Sentence Representations". TACL(2021) [[PDF]](https://aclanthology.org/2020.acl-main.488.pdf) [[CODE]](https://github.com/pliang279/sent_debias)
* **FairFil**: "FairFil: Contrastive Neural Debiasing Method for Pretrained Text Encoders". ICLR(2021) [[PDF]](https://openreview.net/pdf?id=N6JECD-PI5w) 
* **Context-Debias**: "Debiasing Pre-trained Contextualised Embeddings". EACL(2021) [[PDF]](https://aclanthology.org/2021.eacl-main.107) [[CODE]](https://github.com/kanekomasahiro/context-debias)
* **Occupation Data**: "Good Secretaries, Bad Truck Drivers? Occupational Gender Stereotypes in Sentiment Analysis". EACL(2021) [[PDF]](https://aclanthology.org/W19-3809/) [[CODE]](https://github.com/jayadevbhaskaran/gendered-sentiment)

### Large Language Models
* **Few-Shot Data Interventions**: "Language Models Get a Gender Makeover: Mitigating Gender Bias with Few-Shot Data Interventions". ACL(2023) [[PDF]](https://aclanthology.org/2023.acl-short.30/)[[CODE]](https://github.com/himansh005/data_debias) 
* **Label Bias in LLMs**: "Beyond Performance: Quantifying and Mitigating Label Bias in LLMs". NAACL(2024) [[PDF]](https://aclanthology.org/2024.naacl-long.378/)[[CODE]](https://github.com/schwartz-lab-NLP/label-bias) 
* **Conceptor-Aided Debiasing**: "Conceptor-Aided Debiasing of Large Language Models". EMNLP(2023) [[PDF]](https://aclanthology.org/2023.emnlp-main.661)
* **Likelihood-based Mitigation**: "Likelihood-based Mitigation of Evaluation Bias in Large Language Models". ACL(2024) [[PDF]](https://arxiv.org/pdf/2402.15987)[[CODE]](https://github.com/stjohn2007/likelihood_bias) 


## Information Theory
* **Embedding-MI**: "Estimating Mutual Information Between Dense Word Embeddings". ACL(2020) [[PDF]](https://aclanthology.org/2020.acl-main.741.pdf) [[CODE]](https://github.com/babylonhealth/corrsim)
* **MI-Max**: "A Mutual Information Maximization Perspective of Language Representation Learning". ACL(2020) [[PDF]](https://aclanthology.org/2020.acl-main.741.pdf) [[CODE]](https://github.com/babylonhealth/corrsim)

## Dataset Construction
* **Coscript**: "Distilling Script Knowledge from Large Language Models for Constrained Language Planning". ACL(2023) [[PDF]](https://aclanthology.org/2023.acl-long.236/) [[CODE]](https://github.com/siyuyuan/coscript)
* **Role of Demonstrations**: "Rethinking the Role of Demonstrations: What Makes In-Context Learning Work?". EMNLP(2022) [[PDF]](https://aclanthology.org/2022.emnlp-main.759/) [[CODE]](https://github.com/Alrope123/rethinking-demonstrations)
* **Order Sensitivity**: "Fantastically Ordered Prompts and Where to Find Them: Overcoming Few-Shot Prompt Order Sensitivity". ACL(2022) [[PDF]](https://aclanthology.org/2022.acl-long.556/)
* **Holistic Descriptor Dataset**: "I'm sorry to hear that: Finding New Biases in Language Models with a Holistic Descriptor Dataset". EMNLP(2022) [[PDF]](https://aclanthology.org/2022.emnlp-main.625/) [[CODE]](https://github.com/facebookresearch/ResponsibleNLP/tree/main/holistic_bias)


## Bias Suppression
* **Prompt Bias Suppression**: "In-Contextual Gender Bias Suppression for Large Language Models". Findings of EACL(2023) [[PDF]](https://aclanthology.org/2024.findings-eacl) [[CODE]](https://github.com/LivNLP/prompt_bias_suppression.git)

## Impicit Bias
* **Explicit and Implicit Gender**: "Probing Explicit and Implicit Gender Bias through LLM Conditional Text Generation". Findings of EACL(2023) [[PDF]](https://arxiv.org/pdf/2311.00306) 

## Others
* **Wiki Bias**: "Men Are Elected, Women Are Married: Events Gender Bias on Wikipedia". ACL(2021) [[PDF]](https://aclanthology.org/2021.acl-short.45) [[CODE]](https://github.com/PlusLabNLP/ee-wiki-bias)
* **Annotator Demographics Matter**: "When Do Annotator Demographics Matter? Measuring the Influence of Annotator Demographics with the POPQUORN Dataset". LAW-XVII@ACL(2023) [[PDF]](https://aclanthology.org/2023.law-1.25/) [[CODE]](https://github.com/Jiaxin-Pei/potato-prolific-dataset)
* **Label Debias**: "Beyond Performance: Quantifying and Mitigating Label Bias in LLMs". NAACL(2024) [[PDF]](https://aclanthology.org/2024.naacl-long.378) [[CODE]](https://github.com/schwartz-lab-NLP/label-bias)


[Back to Top](#paper-reading)
