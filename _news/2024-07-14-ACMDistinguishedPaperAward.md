---
layout: news-item
date: 2024-07-14
title: "ACM Distinguished Paper Award at AIWare 2024"
tracks: [2,3]
---

We won an **ACM Distinguished Paper Award** for our study on the smart invocation of autocompletion systems at the ACM International Conference on AI-powered Software ([AIware 2024][aiwareconf]).

**Title of the paper**: A Transformer-Based Approach for Smart Invocation of Automatic Code Completion

**Abstract**: Transformer-based language models are highly effective for code completion, with much research dedicated to enhancing the content of these completions. Despite their effectiveness, these models come with high operational costs and can be intrusive, especially when they suggest too often and interrupt developers who are concentrating on their work. Current research largely overlooks how these models interact with developers in practice and neglects to address when a developer should receive completion suggestions. To tackle this issue, we developed a machine learning model that can accurately predict when to invoke a code completion tool given the code context and available telemetry data. To do so, we collect a dataset of 200k developer interactions with our cross-IDE code completion plugin and train several invocation filtering models. Our results indicate that our small-scale transformer model significantly outperforms the baseline while maintaining low enough latency. We further explore the search space for integrating additional telemetry data into a pre-trained transformer directly and obtain promising results. To further demonstrate our approach’s practical potential, we deployed the model in an online environment with 34 developers and provided real-world insights based on 74k actual invocations.

**Link**: This paper can be found [here][aiware-paper].

**People**: Aral de Moor, Arie van Deursen, and [Maliheh Izadi][mali]

![]({{ 'img/aiware2024_DistinguishedPaperAward.jpg' | relative_url }}){: width="60%" style="float: left"}
_DistinguishedPaperAward at [AIWare 2024][aiwareconf]

[aiware-paper]: https://dl.acm.org/doi/abs/10.1145/3664646.3664760
[aiwareconf]: https://2024.aiwareconf.org/
[mali]: https://malihehizadi.github.io/PersonalWebsite/
