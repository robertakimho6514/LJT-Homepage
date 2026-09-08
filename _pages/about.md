---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

I am **Junteng Liu**, a Ph.D. candidate in Computer Science at the [Hong Kong University of Science and Technology (HKUST)](https://hkust.edu.hk/) and a member of the HKUST NLP Group. I am advised by **Prof. Junxian He**, who also advised me during my undergraduate studies at Shanghai Jiao Tong University (SJTU).

My research focuses on **natural language processing** and **machine learning**. In particular, I am interested in:

- LLM reasoning and reinforcement learning
- Hallucination in vision-language models
- LLM truthfulness and interpretability

## Publications

The full publication collection is mirrored here so visitors can see my work directly from the landing page. My name is shown in **bold**. You can also view the dedicated [Publications page]({{ base_path }}/publications/) or my [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present
- **B.Eng.**, Shanghai Jiao Tong University, 2020–2024  
  Graduated in June 2024; recipient of the **Zhiyuan Honor Scholarship**.

## Research Experience

- **Research Intern, MINIMAX**, February 2025–Present
- **Research Intern, Tencent WXG**, June 2024–September 2024  
  Advised by Zifei Shan.
- **Research Intern, Shanghai AI Lab**, June 2023–December 2023  
  Advised by Prof. Yu Cheng.

## Research Skills

- Natural language processing and machine learning
- Large language model reasoning and reinforcement learning
- Vision-language model evaluation and hallucination analysis
- LLM truthfulness, internal representations, and interpretability
- Foundation-model evaluation and parameter-efficient methods

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://twitter.com/junteng88716710)
