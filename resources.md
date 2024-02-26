---
title: Hackathon resources
menu_title: Resources
menu_icon: journal-code
---

<ul class="grid">

<li class="resource-block" markdown="1">

## Getting Set Up

#### [Slack](https://join.slack.com/share/enQtNjY0MDE3Njc1NjYxMS01NjJlYWJlNTY1ZDcwYTYxMTRhMTIzYTI4NDRlMmY3NzI2MjlmOGQ0NWQzY2RhZTQwMTQ4YjMxNGIwYjNiMmRj) - Join the hackathon's Slack channel to connect with other participants and ask questions.

#### [Project proposals](_/../submission.md) - team leaders should submit their project proposals and form teams

#### Complete the orientation modules

Please complete the following orientation assignments in preparation for the hackathon. These modules are designed to help you get familiar with the tools and concepts you'll need to participate in the hackathon.

- [Intro to Git and GitHub](https://classroom.github.com/a/2rswOlPi)
- [Intro to GitHub Classroom](https://classroom.github.com/a/EaTuZ8L8)

For those looking for a refresher on Python programming, see the following GitHub Classroom assignment and the resources in the next section.

#### Python Programming

Programming expertise is not required, but at least beginner Python programming experience is recommended for participation in code-focused projects of the hackathon.

For those looking for a brief refresher on Python programming, we recommend you complete the following GitHub Classroom assignment:

- [Python refresher](https://classroom.github.com/a/XFCJVXYP)

For those without prior Python experience, we recommend you complete an introductory Python course in preparation for the hackathon.

- [Python for Everybody by University of Michigan](https://www.coursera.org/specializations/python)
- [Learn Python 3 by CodeAcademy](https://www.codecademy.com/learn/learn-python-3)
- [Intro to Python Programming for Materials Engineers](https://youtube.com/playlist?list=PLL0SWcFqypCmkHClksnGlab3wglEVMqNN)
- [Python Beginners Guide for Programmers by Python Software Foundation](https://wiki.python.org/moin/BeginnersGuide/Programmers)

### Bayesian optimization

#### [Bayes Rule by 3Blue1Brown](https://youtu.be/HZGCoVF3YvM) -- explanation of the fundamental concept behind Bayesian methods

{% include youtube.html video="HZGCoVF3YvM" title="" %}

#### [A Gentle Introduction to Bayesian Optimization](https://youtu.be/IVaWl2tL06c) - a recording of the Accelerate '23 training workshop on Bayesian optimization, with a focus on application

{% include youtube.html video="IVaWl2tL06c" title="" %}

#### [A Visual Exploration of Gaussian Processes](https://distill.pub/2019/visual-exploration-gaussian-processes/) - A Distill Pub article explaining a commonly used predictive model in Bayesian optimization with visualizations and mathematical rigor.

#### [Exploring Bayesian Optimization](https://distill.pub/2020/bayesian-optimization/) - A Distill Pub article that provides an overview of active learning, Bayesian optimization with visualizations and mathematical rigor.

#### [Bayesian Optimization Book](https://bayesoptbook.com/) - For those REALLY looking to dive deep into the topic, this book is a comprehensive resource on Bayesian optimization. The book aims to provide a self-contained and comprehensive introduction to Bayesian optimization, starting "from scratch" and carefully developing all the key ideas along the way. The book is free, and even open-source.

</li>

<li class="resource-block" markdown="1">

## BO Tools

Use of the tools listed in this section is not a requirement. A diverse set of packages and implementations is encouraged. Likewise, multiple teams using the same package is not a problem, in part because implementations can remain private during the course of the hackathon.[<sup>(?)</sup>][faq]{:title="Does my GitHub repository need to be public?"} If you'd like to see a specific tool listed here, please navigate to the "Improve this page" link at the bottom of the page and open a pull request.

#### [Acceleration Consortium's curated list of optimization tools](https://github.com/AccelerationConsortium/awesome-self-driving-labs#optimization)

#### BayBE
This hackathon is co-organized by Merck KGaA. You may consider using an internal Merck tool that was recently open-sourced, called the [Bayesian optimization BackEnd (BayBE)](https://github.com/emdgroup/baybe). This tool focuses on real-world experimental campaigns in the physical sciences with support for integrating domain knowledge through custom parameter encodings and built-in chemical encodings. In addition, it allows for custom surrogate models, mixed variable types, and transfer learning.

#### Adaptive Experiment (Ax) Platform
The Ax Platform is a tool developed by Meta's Adaptive Experimentation team. It is a user-friendly, modular, and actively developed general-purpose Bayesian optimization platform with support for simple and advanced optimization tasks. It is a high-level wrapper to the widely used [BoTorch](https://botorch.org/) library, also developed by Meta, which is built on PyTorch.

<li class="resource-block" markdown="1">

## Guidelines

### [Submission](_/../resources/submission.md) - The hackathon's workflow for submissions

</li>