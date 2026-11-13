---
layout: post
title: "PsyFusion-RAG: Multi-Source Knowledge Fusion for Psychological Dialogue Generation"
title_zh: "PsyFusion-RAG：多源知识融合的心理对话生成模型"
categories: publication
tags: [RAG, Knowledge Fusion, LLM Applications, Psychological Dialogue]
authors: "<strong>Ruolin Su</strong>, Yongkang Zhou, Junjie Yao, Yuxuan Hou"
thumbnail: "/assets/images/psyfusion.png"
venue_tag: "Journal of Chinese Information Processing, Vol. 40(5), 2026 (CCF Chinese Core)"
venue_tag_zh: "《中文信息学报》2026 年第 40 卷第 5 期（CCF 中文核心）"
#project_page: "[Project Page]"
paper_link: "http://jcip.cipsc.org.cn/cn/article/pdf/preview/10.3969/j.issn.1003-0077.2026.05.014.pdf"
#code_link: "https://..."
---

<div class="lang-en" markdown="1">

PsyFusion-RAG: a multi-source heterogeneous knowledge-fusion RAG framework for psychological dialogue. Stores knowledge by modality (reference-case vector store + symptom–therapy knowledge graph + therapy relational database), driven by an intent-aware 8-dimension user profile and a two-stage cascade retrieval (BGE-M3 dense recall + BGE-reranker cross-encoder + LLM filtering) with a 4-step chain-of-thought to fuse knowledge and suppress hallucination. On the multi-symptom counseling test set it reaches a 70% full-score (5/5) rate and is judged the best response in 70% of samples. Published in the *Journal of Chinese Information Processing*, Vol. 40, No. 5 (2026), pp. 163–174 (a CCF Chinese core journal).

</div>

<div class="lang-zh" markdown="1">

PsyFusion-RAG：面向心理对话的多源异构知识融合 RAG 框架。按模态分别存储知识（参考案例向量库 + 症状–疗法知识图谱 + 疗法关系型数据库），由意图感知的 8 维用户画像驱动，采用两阶段级联检索（BGE-M3 稠密召回 + BGE-reranker 交叉编码器重排 + LLM 过滤），并通过 4 步思维链融合知识、抑制幻觉。在多症状咨询测试集上，满分（5/5）比例达 70%，在 70% 的样本中被评为最佳回复。发表于《中文信息学报》2026 年第 40 卷第 5 期，第 163–174 页（CCF 中文核心期刊）。

</div>
