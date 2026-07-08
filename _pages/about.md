---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Jason Xurong Liang is a final-year Ph.D. candidate in Computer Science at the University of Queensland, Australia. His research focuses on **efficient recommender systems**, **lightweight embeddings**, **graph collaborative filtering**, and **LLM-based recommendation**.

He is advised by [Assoc. Prof. Rocky Tong Chen](https://eecs.uq.edu.au/profile/1253/rocky-chen) and [Prof. Hongzhi Yin](https://sites.google.com/view/hongzhi-yin/home). He received his Bachelor of Computer Science with First-Class Honors from the University of Queensland in 2022.

Jason's broader research interests include **data mining**, **recommender systems**, **user modeling**, **natural language processing**, **large language models**, and **scalable machine learning**. His work has been published in venues including **SIGIR**, **RecSys**, **TOIS**, **ICDM**, and **KDD**.

From Oct 2024 to May 2025, Jason worked as an **Applied Scientist Intern at Amazon**, where he conducted research on **LLM-based in-context learning for user cold-start recommendation** in a commercial video streaming platform. This work was published at **RecSys 2025**. During the internship, he also built AWS-based ML/data pipelines using services such as **EMR**, **SageMaker Studio**, **Bedrock**, and **S3** for large-scale user interaction data processing, distributed analysis, and downstream ML modeling. He worked with [Dr. Julien Monteil](https://scholar.google.com/citations?user=ZXFM_O8AAAAJ&hl=en), [Dr. Vu Nguyen](https://vu-nguyen.org/), [Dr. Vuong Le](https://vuongle2.github.io/), and [Dr. Paul Albert](https://scholar.google.com/citations?user=trUhFBEAAAAJ&hl=en).

His thesis submission is expected in **September 2026**, followed by oral defense in **late 2026**. <span style="color: #b00020; font-weight: bold;">He will be available for full-time opportunities from **January 2027**.</span>

When he is not immersed in research 📖 or in front of a computer 👨‍💻, he enjoys traveling 🏖️, fishing 🎣, and watching movies 🍿.


<!---
# 🔥 News
- *2026.09*: Thesis submission expected.
- *2027.01*: Available for full-time research scientist / applied scientist / postdoctoral opportunities.
--->

# 📝 Publications

* `Under Review` **Empowering Compact LLMs with Fusion of Layer-wise Exits for Recommendation**, **Xurong Liang**, Tong Chen, Quoc Viet Hung Nguyen, Jianxin Li, Xiangliang Zhang, Hongzhi Yin
* `RecSys 2025` [In-context Learning for Addressing User Cold-start in Sequential Movie Recommenders](https://dl.acm.org/doi/full/10.1145/3705328.3748109), **Xurong Liang**, Vu Nguyen, Vuong Le, Paul Albert, Julien Monteil
* `TOIS 2025` [Lightweight Embeddings with Graph Rewiring for Collaborative Filtering](https://arxiv.org/abs/2505.18999), **Xurong Liang**, Tong Chen, Wei Yuan, Hongzhi Yin
* `SIGIR 2024` [Lightweight Embeddings for Graph Collaborative Filtering](https://arxiv.org/abs/2403.18479), **Xurong Liang**, Tong Chen, Lizhen Cui, Yang Wang, Meng Wang, Hongzhi Yin [![](https://img.shields.io/github/stars/xurong-liang/LEGCF?style=social&label=Code+Stars)](https://github.com/xurong-liang/LEGCF)
* `KDD 2024` [Hate Speech Detection with Generalizable Target-aware Fairness](https://arxiv.org/abs/2406.00046), Tong Chen, Danny Wang, **Xurong Liang**, Marten Risius, Gianluca Demartini, Hongzhi Yin [![](https://img.shields.io/github/stars/xurong-liang/getfair?style=social&label=Code+Stars)](https://github.com/xurong-liang/getfair)
* `ICDM 2023` [Learning Compact Compositional Embeddings via Regularized Pruning for Recommendation](https://arxiv.org/abs/2309.03518), **Xurong Liang**, Tong Chen, Quoc Viet Hung Nguyen, Jianxin Li, Hongzhi Yin [![](https://img.shields.io/github/stars/xurong-liang/CERP?style=social&label=Code+Stars)](https://github.com/xurong-liang/CERP)


# 💼 Research & Industry Experience

* **Jan 2023 - Present**, **Ph.D. Researcher**, University of Queensland, Australia.
    * Designed and optimized lightweight recommender-system architectures using graph neural networks, large language models, and mixture-of-experts techniques.
    * Developed efficient algorithmic frameworks to reduce embedding storage footprint, memory consumption, and computational overhead for large-scale recommendation.
    * Built model training and data-processing pipelines on high-performance computing clusters using Python, PyTorch, and Slurm.
    * Published first-author research in top-tier venues including SIGIR, RecSys, TOIS, and ICDM.

* **Oct 2024 - May 2025**, **Applied Scientist Intern**, Amazon, Australia.
    * Developed an LLM-based in-context learning framework for user cold-start recommendation in a commercial video streaming platform; the resulting work was published at RecSys 2025.
    * Built an AWS-based ML/data pipeline using EMR, SageMaker Studio, Bedrock, and S3 to process large-scale user interaction data, perform distributed preprocessing and analysis, and support downstream ML modeling.
    * Worked with [Dr. Julien Monteil](https://scholar.google.com/citations?user=ZXFM_O8AAAAJ&hl=en), [Dr. Vu Nguyen](https://vu-nguyen.org/), [Dr. Vuong Le](https://vuongle2.github.io/), and [Dr. Paul Albert](https://scholar.google.com/citations?user=trUhFBEAAAAJ&hl=en).

* **Sep 2021 - Sep 2024**, **Casual Research Assistant**, University of Queensland, Australia.
    * Conducted experiments, data preprocessing, baseline testing, and algorithm implementation for explainable recommender systems and hate speech detection.
    * Contributed to a hate speech detection framework published at KDD 2024.

* **Jun 2021 - Jul 2021**, **Winter Research Scholar**, University of Queensland, Australia.
    * Conducted the project *Dynamic Topic Modelling on Social Media*, using natural language processing to model topic changes on social media during the first 100 days of COVID-19.
    * Supervised by [Prof. Zi (Helen) Huang](https://staff.itee.uq.edu.au/huang/) and [Assoc. Prof. Rocky Tong Chen](https://eecs.uq.edu.au/profile/1253/rocky-chen).
    * Project visualization: [https://topicvis.nifu.me/](https://topicvis.nifu.me/)


# 📖 Education

* **2023 - Late 2026**, Doctor of Philosophy in Computer Science, University of Queensland, Brisbane, Australia.
    * Ph.D. project: *Toward Efficient Lightweight Recommender Systems*
    * Thesis submission expected in September 2026; oral defense anticipated in late 2026.
* **2022**, Bachelor of Computer Science with Honors, University of Queensland, Brisbane, Australia.
    * Honors project: *PEP++: Improved Pruning-Based Embedding Dimension Optimization for Recommender Systems*
    * Awarded First-Class Honors with cumulative GPA 7.000/7.000.
* **2019 - 2021**, Bachelor of Computer Science, University of Queensland, Brisbane, Australia.
    * Major in Data Science.
    * Graduated with cumulative GPA 6.792/7.000.
* **2016 - 2018**, High School Diploma, Indooroopilly State High School, Brisbane, Australia.


# 🧑‍🏫 Teaching

* **Feb 2022 - Jul 2026**, **Head Tutor & Teaching Assistant**, [INFS7901 – Database Principles](https://my.uq.edu.au/programs-courses/course.html?course_code=INFS7901), University of Queensland.
    * Delivered practical and tutorial sessions, managed course administration, and coordinated assignment and examination marking.
    * Helped students understand database design, relational databases, SQL, and related data-management concepts.

* **Feb 2023 - Jul 2026**, **Head Tutor & Teaching Assistant**, [INFS3208/INFS7208 – Cloud Computing](https://my.uq.edu.au/programs-courses/course.html?course_code=INFS3208), University of Queensland.
    * Delivered practical and tutorial sessions on cloud computing, distributed systems, and data-processing pipelines.
    * Mentored student projects using Docker, Docker Swarm, Kubernetes, Spark, HDFS, Amazon S3, Google Cloud Storage, MongoDB, Redis, and Faiss.


# 🎖 Awards

* **2022** Dean’s Commendation for Academic Excellence — Bachelor of Computer Science (Honors), University of Queensland, Australia.
    * Awarded for achieving a grade point average of 6.60/7.00 or higher in a single semester.
* **2019 - Jul 2021** Dean’s Commendation for Academic Excellence — Bachelor of Computer Science, University of Queensland, Australia.
    * Awarded for achieving a grade point average of 6.60/7.00 or higher in a single semester.
* **2021** Cloud Computing INFS3208 Best Project Runner-up Award, University of Queensland, Australia.
* **2020** Prentice Scholar, University of Queensland, Australia.
    * Awarded to undergraduate Computer Science and Information Technology students whose academic performance ranked within the top 5% of their cohort.
* **2017** Subject Prize Award – Information Processing and Technology, Indooroopilly State High School, Australia.
    * Awarded for ranking 1st in the course cohort.


# 🏅 Scholarships

* **2023 - 2026** Australian Government Research Training Program (RTP) Scholarship
* **2024** Google Research Travel Scholarship
* **2022** UQ International Onshore Merit Scholarship
* **2021** Winter Research Scholarship


# 🧰 Skills

* **Programming:** Python, SQL, Java, C, Haskell, Dafny, Scala, MATLAB, Shell/Bash, LaTeX
* **Machine Learning & AI:** PyTorch, Faiss, Scikit-learn, HuggingFace, PyTorch Lightning, NLTK
* **Big Data & Databases:** Spark, HDFS, MongoDB, Redis, relational databases
* **Cloud & Infrastructure:** Docker, Kubernetes, AWS, GCP, OCI, S3, GCS, Slurm/HPC


# More about me...

Want to know more? Please have a look at my [CV](../Xurong_Liang_resume.pdf) 😎.


---

Webpage template cloned from [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io).

<!---
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. | [\[video\]](https://github.com/)
--->
