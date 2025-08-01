---
layout: project
title: "Proactive AI in IDEs"
tracks: [3]
image: "projects/track-3/nadine-thesis-cover-page.jpg"
publish_date: "18th of July 2025"
authors:
    - Nadine Kuo
    - Maliheh Izadi
    - Agnia Sergeyuk
    - Valerie Chen
publish-url: "https://resolver.tudelft.nl/uuid:53934200-be4e-4515-8ef2-d3dd1a9bfe8a"
artifact-url: ""
abstract: |    
    Recent advances in LLMs have transformed AI coding assistants from simple autocompletion tools into conversational partners that support a wide range of development tasks through natural language interaction. While this shift promotes closer human-AI collaboration, this also places a burden on developers to craft precise prompts and integrate sufficient context to accomplish their task.
    To address this, there is growing interest in proactive AI systems that can anticipate developer intent and surface timely, contextually relevant suggestions - potentially revealing insights developers might not have considered.

    However, existing research on proactive coding assistance has largely been confined to controlled, experimental settings, leaving open questions about its effectiveness and integration in real-world development environments.

    In this work, we design and implement a proactive AI assistant within JetBrains Fleet, a polyglot enterprise IDE. Our system signals AI activity via in-editor cues and delivers context-aware code improvement suggestions via a chat interface. We adopt heuristics based on IDE activity to determine when it is timely to intervene, during various stages across the development workflow: formulating needs, idea execution and committing changes.
    Lastly, we conducted a five-day in-the-wild study with 18 professional developers to evaluate its impact on user experience and engagement patterns.

    Our findings demonstrate that timing is a critical aspect influencing perceived value of proactive AI assistance.
    Suggestions delivered at natural workflow boundaries (e.g. post-commit) achieved the highest engagement, while mid-task interventions were often dismissed.
    The consistent engagement trends (and voluntary continued use) indicate strong potential for integrating proactive AI into everyday software engineering workflows.
    Our study not only underscores the feasibility and practical value of proactive assistance in enterprise development environments, but also provides actionable design insights for future tools.
    While challenges remain - such as improving suggestion relevance and supporting diverse user preferences - these highlight important directions for advancing adaptive, intent-aware proactive systems that can further enhance developer workflows.
---
