---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **B.Sc. in Computer Science & Engineering**, Chittagong University of Engineering & Technology (CUET), Chittagong, Bangladesh, 2020 – 2025
  * CGPA: 3.75 / 4.00
  * Dean's Award — awarded for achieving CGPA above 3.75

Research Experience
======
* **Undergraduate Thesis Research** — Dept. of CSE, CUET, 2024 – 2025
  * Supervisor: Dr. Abu Hasnat Mohammad Ashfak Habib
  * Thesis: *Stress Identification from Bengali Social Media Texts Using Transformer-based Approaches*
  * Proposed a lexicon-augmented Transformer framework that enriches pre-trained Bengali language models (e.g., BanglaBERT) with domain-specific stress lexicons extracted from Bengali social media corpora.
  * Demonstrated that the lexicon-augmented approach consistently outperformed standard fine-tuned Transformer baselines for low-resource affective computing.

* **Undergraduate Researcher** — NLP Research Lab, Dept. of CSE, CUET, January 2024 – May 2025
  * Supervisor: Dr. Mohammed Moshiul Hoque
  * Designed and fine-tuned BERT-based models for fake news detection in Malayalam social media texts (NAACL 2025 workshop).
  * Built deep learning pipelines for hate speech detection in Devanagari-script languages, achieving >85% classification accuracy.
  * Developed multimodal fusion architectures combining visual and textual features for misogyny meme classification.
  * Led team CUET_NLP_Big_O in three ACL shared tasks (DravidianLangTech@NAACL, CHiPSAL@COLING).

Professional Experience
======
* **Software Engineer** — AsthaIT Inc., Dhaka, Bangladesh, October 2025 – Present
  * Build and maintain a large multi-module e-commerce platform on a modern .NET stack using Clean Architecture (separated domain, infrastructure, business, web, API, and serverless layers).
  * Apply CQRS and domain-driven design with SOLID principles, input validation, object mapping, and resilience policies.
  * Deliver features across catalog, cart, checkout, customer, CMS, marketing/discounts, delivery, loyalty/rewards, EMI, CRM, ticketing, and search domains.
  * Implement NoSQL persistence with full-text search indexing, plus distributed caching and data-protection key storage.
  * Develop real-time notification services and background/recurring job processing for scheduled tasks, order workflows, and asynchronous bulk import/export.
  * Integrate cloud services for object storage/CDN, messaging queues, email delivery, secrets management, and serverless functions.
  * Apply event-driven messaging between services for cache invalidation and cross-service workflows.
  * Add structured logging and application monitoring; implement secure authentication with token-based and two-factor mechanisms.
  * Package services as containers and deploy through CI/CD to managed Kubernetes/container registries with health checks; expose APIs via OpenAPI.

* **Software Engineer (AI/NLP)** — Inument Solutions Limited, Dhaka, Bangladesh, July 2025 – September 2025
  * Designed and built **Taxinument**, a Retrieval-Augmented Generation (RAG) system for intelligent querying of financial and tax documents over large PDF corpora.
  * Implemented the full data pipeline: PDF ingestion → text chunking → embedding generation → vector storage in Qdrant → semantic retrieval with re-ranking.
  * Orchestrated multi-step LLM reasoning chains using LangChain with GPT-5, achieving 90%+ retrieval accuracy on benchmark queries.
  * Exposed the system as a production-grade REST API using FastAPI; reduced query latency by 60% through caching and chunk optimization.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!-- Projects
======
* **Task Tracker System** — ASP.NET Core, ReactJS, Redis, MSSQL Server, GitHub Actions, Docker (2025)
  * Full-stack application for software engineers to track tasks using Clean Architecture, CQRS, and CI/CD automation.
* **Connect CUET Alumni Platform** — PHP, MySQL, Bootstrap, jQuery (2023)
  * Alumni networking portal with discussion forums, job boards, and event management for 5000+ alumni.
* **Concurrent Queue Simulation Systems** — Java, Multithreading, Concurrency (2024)
  * Multithreaded bank and grocery queue simulations using locks and semaphores, achieving zero deadlocks.
* **Online Voting System for Student Organizations** — Java, Spring Boot, MySQL, REST API (2024)
  * Secure voting platform with role-based authentication, candidate management, vote validation, and automated results. -->

Technical Skills
======
* **Programming Languages:** Python, C#, Java, JavaScript, C++, C, PHP
* **ML / Deep Learning:** PyTorch, TensorFlow, Scikit-learn, Hugging Face Transformers, m-BERT/RoBERTa/XLM-R, LangChain, OpenAI API
* **NLP Tools:** NLTK, SpaCy, Gensim, FastText, Sentence-Transformers, Tokenizers
* **Data Science:** Pandas, NumPy, Matplotlib, Seaborn, Jupyter, Google Colab
* **Web & Backend:** ASP.NET Core, MVC Razor Pages, React.js, FastAPI, Flask, Node.js
* **Databases & Vector Stores:** MSSQL Server, MongoDB, MySQL, Redis, Qdrant
* **DevOps & Tools:** Git, Docker, Linux, LaTeX, CI/CD (GitHub Actions), VS Code
* **Research Skills:** Experimental Design, Statistical Analysis, Academic Writing, Data Annotation, Literature Review

Honors & Awards
======
* **1st Place, .NET Leaderboard** — Learnathon 3.0, Brain Station 23 (98/100 SonarCloud score), 2025
* **Honorable Mention** — ICPC Dhaka Regional 2022 Programming Contest, 2022
* **13th Position** — RMSTU Bangabandhu Online Divisional Programming Contest, 2021
* **10th Position** — Tech Carnival 1.0 Programming Contest, 2021
* **15th Rank** — BUET STEM Olympiad, MME Department, 2018
* **Education Board Scholarship** — Secondary School Certificate, 2017

Competitive Programming
======
* **Problems Solved:** 1200+ algorithmic problems across major online judges.
* **Platforms:** Codeforces (max rating 1527 — Specialist), CodeChef, AtCoder, HackerRank, LightOJ, UVA.
* **Core Topics:** Dynamic Programming, Graph Theory, Greedy Algorithms, Number Theory, Segment Trees, Binary Search, Sliding Window, Union-Find (DSU), Trie, Bit Manipulation, Modular Arithmetic.

References
======
* **Dr. Mohammed Moshiul Hoque** — Professor, Dept. of CSE, Chittagong University of Engineering & Technology. [moshiul_240@cuet.ac.bd](mailto:moshiul_240@cuet.ac.bd)
* **Dr. Abu Hasnat Mohammad Ashfak Habib** — Professor, Dept. of CSE, Chittagong University of Engineering & Technology. [ashfak@cuet.ac.bd](mailto:ashfak@cuet.ac.bd)
