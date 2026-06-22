---
layout: post
title: "PsyFusion-RAG: Multi-Source Knowledge Fusion for Psychological Dialogue Generation"
categories: publication
tags: [RAG, Knowledge Fusion, LLM Applications, Psychological Dialogue]
authors: "<strong>Ruolin Su</strong>, Yongkang Zhou, Junjie Yao, Yuxuan Hou"
thumbnail: "/assets/images/psyfusion.png"
venue_tag: "Journal of Chinese Information Processing, Vol. 40(5), 2026 (CCF Chinese Core)"
#project_page: "[Project Page]"
paper_link: "http://jcip.cipsc.org.cn/cn/article/pdf/preview/10.3969/j.issn.1003-0077.2026.05.014.pdf"
#code_link: "https://..."
---

PsyFusion-RAG: a multi-source heterogeneous knowledge-fusion RAG framework for psychological dialogue. Stores knowledge by modality (reference-case vector store + symptom–therapy knowledge graph + therapy relational database), driven by an intent-aware 8-dimension user profile and a two-stage cascade retrieval (BGE-M3 dense recall + BGE-reranker cross-encoder + LLM filtering) with a 4-step chain-of-thought to fuse knowledge and suppress hallucination. On the multi-symptom counseling test set it reaches a 70% full-score (5/5) rate and is judged the best response in 70% of samples. Published in the *Journal of Chinese Information Processing*, Vol. 40, No. 5 (2026), pp. 163–174 (a CCF Chinese core journal).
