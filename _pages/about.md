---
layout: biography
title: about
permalink: /
subtitle: <a href='#'>Concordia University</a>. haibo<DOT>wang<AT>mail<DOT>concordia<DOT>ca

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
#    <p>555 your office number</p>
#    <p>123 your address street</p>
#    <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Ph.D. candidate in Computer Science at Concordia University, Montréal, Canada, supervised by [Prof. Shin Hwei Tan](https://scholar.google.com/citations?user=1eFjFs8AAAAJ&hl=en). My research lies broadly in **software engineering**, with a focus on **automated software testing**, **software refactoring**, **AI for software engineering**, **green and sustainable software engineering**, and **human aspects of software engineering**.

Before joining Concordia University, I was part of the Joint Ph.D. Program between the Southern University of Science and Technology, China, and the University of Leeds, United Kingdom, under the supervision of [Prof. Shin Hwei Tan](https://scholar.google.com/citations?user=1eFjFs8AAAAJ&hl=en) and [Prof. Zheng Wang](https://scholar.google.com/citations?user=qJ7ZKG8AAAAJ&hl=en). I received my M.Sc. in Computer Technology from Beijing University of Posts and Telecommunications, China, and my B.Sc. in Software Engineering from China University of Petroleum, China.

My research is driven by a central goal: **making software evolution reliable, trustworthy, and sustainable in an AI-assisted world**. Modern software is increasingly written, changed, tested, and maintained with the help of refactoring engines, program transformation tools, automated testing frameworks, and large language models. These tools can significantly improve developer productivity, but they also introduce new risks: refactoring engines may silently change program behavior, Code LLMs may generate incorrect or unsafe code, and AI-assisted development workflows may consume substantial computational resources at scale.

Methodologically, my work combines **empirical software engineering**, **program analysis**, **automated testing**, and **AI-based techniques**. Across these methods, my research follows a common principle: starting from real failures in real software tools, understanding why these failures happen, and building practical techniques to test, validate, and improve modern software development systems.

My research is organized around three connected directions:

1. **Reliable software evolution and transformation.**  
   I study the reliability of software transformation tools, especially refactoring engines. My work investigates refactoring engine bugs in widely used IDEs such as Eclipse, IntelliJ IDEA, and NetBeans, and develops techniques for testing refactoring engines using historical bug reports and LLM-generated program variants. More broadly, I am interested in **behavior-preserving program transformations**, **program simplification**, **refactoring precondition inference**, and **repository-scale refactoring support**.

2. **Trustworthy AI-enabled software development.**  
   I study the reliability, safety, and trustworthiness of Code LLMs and AI-assisted development tools. Instead of evaluating AI-generated code only by whether it compiles or passes tests, my work asks whether the generated code is **correct**, **safe**, **responsible**, and **aligned with developer intent**. This direction includes harmfulness testing for Code LLMs, structured safety auditing of LLM-generated code, ethics testing for generative AI systems, and intent-centered validation of AI-generated software.

3. **Green and sustainable software engineering.**  
   I study the energy impact of software systems and AI-assisted development workflows. My work investigates how refactoring and semantically equivalent program transformations affect software energy consumption, and how LLM-based development tools can be designed to balance **correctness**, **safety**, **developer productivity**, and **energy efficiency**. More broadly, I aim to build practical techniques for energy-aware software development and green AI for software engineering.

My work has been published in top-tier software engineering and programming languages venues, including **FSE**, **ASE**, **PLDI**, and **TOSEM**. Beyond publications, my research has contributed to the open-source community by revealing hundreds of new bugs in widely used software tools and systems, including **Eclipse**, **IntelliJ IDEA**, **NetBeans**, **RefactoringMiner**, and JavaScript engines such as **Google V8**.

More broadly, my long-term research goal is to build **practical, reliable, and sustainable software engineering techniques** that help developers build, evolve, and maintain high-quality software systems in the age of AI.