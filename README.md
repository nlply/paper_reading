# Paper Reading

Reading lists for papers, including but not limited to Natural Language Processing (NLP).

- [Deep Learning in NLP](#deep-learning-in-nlp)
- [Debiasing](#debiasing)
- [Information Theory](#information-theory)
- [Dataset Construction](#dataset-construction)
- [Bias Suppression](#bias-suppression)
***

## Deep Learning in NLP
* **Data Augmentation**: "A Survey of Data Augmentation Approaches for NLP". ACL-Findings(2021) [[PDF]](https://arxiv.org/abs/2105.03075)

## Debiasing

### Survey
* **Empirical Survey**: "An Empirical Survey of the Effectiveness of Debiasing Techniques for Pre-trained Language Models". ACL(2022) [[PDF]](https://aclanthology.org/2022.acl-long.132/)[[CODE]](https://github.com/mcgill-nlp/bias-bench) 


### Pre-trained Language Models
* **Attention-Debiasing**: "Debiasing Pretrained Text Encoders by Paying Attention to Paying Attention". EMNLP(2022) [[PDF]](https://aclanthology.org/2022.emnlp-main.651.pdf) [[CODE]](https://github.com/YacineGACI/AttenD)
* **Debiasing Masks**: "Debiasing Masks: A New Framework for Shortcut Mitigation in NLU". EMNLP(2022) [[PDF]](https://aclanthology.org/2022.emnlp-main.517.pdf) [[CODE]](https://github.com/mariomeissner/shortcut-pruning)
* **DebiasGAN**: "DebiasGAN: Eliminating Position Bias in News Recommendation with Adversarial Learning". EMNLP(2022) [[PDF]](https://aclanthology.org/2022.findings-emnlp.213.pdf) [[CODE]](https://github.com/wuch15/DebiasGAN)
* **DCLR**: "Debiased Contrastive Learning of Unsupervised Sentence Representations". ACL(2022) [[PDF]](https://aclanthology.org/2022.acl-long.423.pdf) [[CODE]](https://github.com/RUCAIBox/DCLR)
* **Self-Debiasing**: "Self-Diagnosis and Self-Debiasing: A Proposal for Reducing Corpus-Based Bias in NLP". TACL(2021) [[PDF]](https://watermark.silverchair.com/tacl_a_00434.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAArYwggKyBgkqhkiG9w0BBwagggKjMIICnwIBADCCApgGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMYGeU2N4-gUef3wyAAgEQgIICafQM-eWrfC20qgWkLpeWW3pgyT48xrTg2fccf0We0h7YjeV52uHi3UsLqAlqmxuWMAvUiVSbLJNPUrgMi8RiWofH1YRb5fX-0sOEvBWVUxVn02nk6arPWkAEex5PVjN1PR0Q5T9SZDK_ulcLhtCsKBua91WHoQ8I8VmNj30wSg2J9rPQxAmKdgMYlajQBIcpsT0uwxg7Y0GJyH9zNyUmtVOSBz6CqLqBylKMVLUmYBrz6hZW-BChC4CI5zpM7xHYC33qQA5CiZb7RW-m2iywa_WrjU6zKihSPKh856xMPaPsVF3CwjMMoEKjN9cAMhBKK0Ml1u7yDWGcL3gZJSQE9GQF6k0gezba8IfQVD9IuIZV6H2tocJxxhrqq-hXlAumiYJqkfsZLUB6vhmJXN3e2jdvnyyRrNTouPIx5f7_ELYKLpdVXLpNFrokqANu4Ok9LXH1aU3dQwG_yY9LccCi0-ahxXtdwTquUxJBnO0cWojEYQnercGIPKyJtrMzi-58behtOPch6vTVUt0xsJvJKk5Iz7UcbzbsPxl9lqgrZ9m91AaTMa0BgFL67EyYNvfiahnhH90ddAamaBsqEi-oaKv2bybpFpZ93k3t2IZ_8JVbJKT7rSiYsxjTEyDODl6ODrm6AoQUICo7JKd1c4BBxZvhWGyQczIde360cvyaW6gU8npAaoM-j7qc0b-n5-e_rjrbJGc26A40ONaopZwg_fj1fURNWsNq5LJ5ICOU8nmioabJk-r6dusErwEWP4M9iOWEe1FhLYaOm47dJC8rnpv4szZPXfzHfHCFU-gnaWI9lNnCeZcPplVo) [[CODE]](https://github.com/timoschick/self-debiasing)
* **SENT-DEBIAS**: "Towards Debiasing Sentence Representations". TACL(2021) [[PDF]](https://aclanthology.org/2020.acl-main.488.pdf) [[CODE]](https://github.com/pliang279/sent_debias)
* **FairFil**: "FairFil: Contrastive Neural Debiasing Method for Pretrained Text Encoders". ICLR(2021) [[PDF]](https://openreview.net/pdf?id=N6JECD-PI5w) 
* **Context-Debias**: "Debiasing Pre-trained Contextualised Embeddings". EACL(2021) [[PDF]](https://aclanthology.org/2021.eacl-main.107) [[CODE]](https://github.com/kanekomasahiro/context-debias)

### Large Language Models
* **Few-Shot Data Interventions**: "Language Models Get a Gender Makeover: Mitigating Gender Bias with Few-Shot Data Interventions". ACL(2023) [[PDF]](https://aclanthology.org/2023.acl-short.30/)[[CODE]](https://github.com/himansh005/data_debias) 


## Information Theory

* **Embedding-MI**: "Estimating Mutual Information Between Dense Word Embeddings". ACL(2020) [[PDF]](https://aclanthology.org/2020.acl-main.741.pdf) [[CODE]](https://github.com/babylonhealth/corrsim)
* **MI-Max**: "A Mutual Information Maximization Perspective of Language Representation Learning". ACL(2020) [[PDF]](https://aclanthology.org/2020.acl-main.741.pdf) [[CODE]](https://github.com/babylonhealth/corrsim)

## Dataset Construction
* **Coscript**: "Distilling Script Knowledge from Large Language Models for Constrained Language Planning". ACL(2023) [[PDF]](https://aclanthology.org/2023.acl-long.236/) [[CODE]](https://github.com/siyuyuan/coscript)
* **Role of Demonstrations**: "Rethinking the Role of Demonstrations: What Makes In-Context Learning Work?". EMNLP(2022) [[PDF]](https://aclanthology.org/2022.emnlp-main.759/) [[CODE]](https://github.com/Alrope123/rethinking-demonstrations)
* **Order Sensitivity**: "Fantastically Ordered Prompts and Where to Find Them: Overcoming Few-Shot Prompt Order Sensitivity". ACL(2022) [[PDF]](https://aclanthology.org/2022.acl-long.556/)


## Bias Suppression
* **Prompt Bias Suppression**: "In-Contextual Gender Bias Suppression for Large Language Models". Findings of EACL(2023) [[PDF]](https://aclanthology.org/2024.findings-eacl) [[CODE]](https://github.com/LivNLP/prompt_bias_suppression.git)

[Back to Top](#paper-reading)
