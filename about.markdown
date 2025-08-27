---
layout: page
title: About
permalink: /about/
---

## Hi, I'm Kyle

![](/assets/github_pic.jpg){:height="50%" width="50%"}


I'm Kyle Jablon. I currently work at Coinbase on the Search and Recommendations team, working on synthetic data applications. I used to work at Slack on Recommender Systems and Grubhub on the Consumer ML/DS team. Nowadays, I'm really interested in search systems, and augmenting them with synthetic data.

### Education

- MS, Georgia Tech Computer Science (Specialization in Machine Learning)
- BA + BS, UChicago Computer Science and Economics 

### The stack I'm used to working in.

I've mostly been working in Python, and Spark since 2016.

LLM Tools I really like: Pydantic, VLLM.

### Some public stuff I've worked on

- **Slack AI Files and Enterprise Search:** I was part of the team that worked on integrating files into Slack's AI Search Summaries. Previously our search summary only ran on messages, but integrating files ended up resulting rewriting a lot of our core logic, and generalizing our architecture significantly more. We trained post-retrieval ranking models to identify the most relevant files for a given RAG search, and saw significant ~20% citation rate improvements from just training a ranker on fiels engagement rates.  By the time this project was compelted, we were able to generalize our framework out to enterprise search, and apply the same principles there.  See our launch for [Slack AI Enterprise Search](https://slack.com/blog/news/slack-enterprise-search-uncover-knowledge-work-smarter) and our notes on [privacy](https://slack.engineering/how-we-built-enterprise-search-to-be-secure-and-private/).

- **Slack AI:** At Slack, I worked on the initial team that launched [Slack AI](https://slack.com/blog/news/slack-ai-has-arrived). I worked on productionizing, and optimizing cross-encoders for search summary generation. We were able to get significant speed-ups on the order of 10-20x from our initial defaults.

<!-- SLACK AI and cross-encoders -->
<!-- guide to cross-encoders. optimizing cross-encoders. compare with  -->
<!-- will cross-encoders stick around?? -->

- **Slack's Recommend API:** I worked on Slack's [Recommend API](https://slack.engineering/recommend-api/), a generalized framework for recommendation entities at Slack. I worked on integrating XGBoost, SHAP explainability, and an assortment of ML Ops features (model versioning, model logging, and deployment checks). This was the foundational work that later enabled us to apply our recommondation API as a platformized approach across the company.

- **Improving Slack's new user flow with ML:** Launching the first ML models for improving our new user flows to bootstrap the new user flow with recommendations. Unfortunately, there was no public blog post for it's release, but our product designer Mehgan Iulo wrote a great introduction to [Slack's joiner launchpad](https://mehgan.com/projects/joiner-launchpad.html). 

- A blog post on [productionizing machine learning models at GrubHub](https://bytes.grubhub.com/just-what-i-needed-making-machine-learning-scalable-and-accessible-at-grubhub-24734cc4139d)

- I worked on a [machine learning ethics wiki](https://kylej1994.github.io/ml_ethics_wiki/) for my Masters class at Georgia Tech (OMSCS 6460: Education Technology). You can also view my [final presentation](https://drive.google.com/file/d/1RQpeGBAXGq4-BbpkztCL8TmDN43Oijeo/view?usp=sharing) for the class on my google drive.


### Support or Contact

If you have business opportunities contact me on my [linkedin](https://www.linkedin.com/in/kylejablon/). If you need to email me for whatever reason, you can reach me at [first][dot][last] [at] coinbase [com]
