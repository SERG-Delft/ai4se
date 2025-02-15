---
layout: track
track-id: 1
title: Code Generation and Validation
tu-leader: Annibale Panichella
jb-leader: Pouria Derakhshanfar
phd: Ali Asgari
---

This track focuses on code generation using AI techniques. We aim to explore the strategies for 1) validating this generated code and 2) how this generated code can help developers validate their handwritten code (automated test generation).

## 1. Validating AI Generated Code

One research direction involves applying metamorphic testing to obtain multiple answers for the same query/code request. Metamorphic testing (MT) is a well-known testing strategy that exercises software programs using different input data, but for which the system under test is expected to provide the same output. MT has previously been utilized to evaluate the robustness of ML models in generating method names and code documentation by implementing semantically equivalent transformations to the program, such as replacing a for loop with a while loop. In our context, we intend to apply metamorphic transformations to the code queries for LLMs, meaning we will request the same coding task by altering the text in the queries and analyzing, comparing, and inspecting the generated code. Then, differential testing can be used to identify behavioral differences and problems in the generated code.

Additionally, we plan to use test generation to validate the code created by LLMs w.r.t. bugs and crashes, for example, using fuzzing techniques to identify inputs that may trigger crashes (e.g., null pointer exception). We can then use these inputs or generated tests to refine the request to LLMs. The synergistic relationship between LLMs and test generation would be the core of a co-evolutionary approach, in which code generated by LLM is iteratively evolved based on the feedback (follow-up queries) produced by test generation tools (e.g., fuzzers).

### PhD Student: Ali Asgari
### MSc Students:
- Remco Schrijver: [Thesis](/projects/track-1/2024-07-08-beyond-acceptance-rates-thesis-remco-schrijver)
- Milan de Koning

## 2. Automated Test Generation
Both JetBrains and TUDelft are involve in multiple research studies and tool developments about automated test generation using varios AI-based techniques.

At JetBrains Research, we are working on [TestSpark](https://plugins.jetbrains.com/plugin/21024-testspark) a test generation plugin for IntelliJ IDEA that utilizes LLM-based and evalutionary-based approaches. Also, we have implemented a test generation tool based on symbolic and concolic execution, called [Kex](https://github.com/vorpal-research/kex). Also, TUdelft researchers have worked on tools, such as [Syntest](https://www.syntest.org) and [EvoSuite](https://www.evosuite.org) (both are evolutionary-based unit test generation approaches for javascript and Java, respectively).

We are currently working on assessing different test generation approaches in a systematic way in order to understand the positive and negative impacting factors in each of these techniques. The output of this study will help us to work on a new hybrid test generation approach that can generate tests with higher coverage and fault-detection

Another focus is specifically the validation of automated JavaScript test generation. This involves constructing a benchmarking dataset from diverse JavaScript projects, with an emphasis on backend libraries and mitigating data leakage in LLM-based tools. Static analysis will be employed to select a varied range of projects for evaluation. Test generation tools such as Syntest, JetBrains' AI assistant, and TestPilot will be assessed for both quantitative and qualitative differences in metrics like coverage. Special emphasis is placed on JavaScript’s unique features, including its dynamic typing and flexibility, to understand their impact on test generation performance.

### PhD Student: Azat Abdullin
### MSc Students:
- Sergey Datskiv
- Saga Rut Sunnevudóttir
