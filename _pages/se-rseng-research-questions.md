---
title: "Software Engineering Research Questions on Research Software Engineering"
layout: single
permalink: /research-questions/
---
This page lists open research questions for software engineering research on research software engineering.
The original list has been compiled from research questions provided by software engineering researchers before and during the Dagstuhl Seminar. They have been collected by [Prof. Dr. Bernhard Rumpe](https://se-rwth.github.io/staff/Bernhard.Rumpe/) (RWTH Aachen, Germany).

The list is a living document.
This means that can contribute to it, for example

- if you know of work that covers one of the research questions, please add a reference to the respective questions;
- if you have an open research question in this area, please add it to the bottom of the list.

---

Research Software Engineering is the use of Software Engineering practices in research applications.

For a precise understanding we put this into parentheses: ((research software) engineering) research) is a foundational field of research that focuses on the engineering techniques, tools, methods, frameworks, etc. to develop research software. It will take inspiration from (generic) software engineering research and find solutions specific for other research domains.

RSE research has to tackle a number of questions that
address the software as a produced result, but also the assistance for the domain-specific researcher as a human being with limited time and always optimizable skills for software development. Some of these questions are rather fundamental research, other should be accompanied by empirical software engineering or organizational, economic research:

- How does RSE differ from SE and what specific activities have to be addressed by different methods and tools?
- How can classic SE approaches, like the V-Model, RUP, Scrum, or Xtreme Programming be adapted to RSE needs?
- Or is an entirely new development process needed?
- How to run empirical validation in such a context? (At least researchers could understand that empirical validation is needed, and would hopefully assist?)
- How to adapt research software requirements elicitation for RSE? This activity is typically deeply connected with the domain-specific research process itself, which is why traditional requirements engineering techniques don't fit.
- How to define robust architectures that are extensible, maintainable, and allow a reusability for research software, where the forms of extensions, and connections to neighboring functionalities are initially very unpredictable.
- How to assist RSE with domain-specific frameworks and reference models (reference architectures and reference domain data models)?
- How to gain precise understanding of optimal forms of reuse: From (1) simple copy-paste, through (2) branching and (3) black-box reuse up to (4) pre-deployed service reuse? This is needed across heterogenous languages, software-stacks, and hardware infrastructures and it must be seen in the context of long-term evolution.
- How to document and model the desired software with the purpose of (a) effective development, (b) possible code generation, (c) sustainable reproducibility, and (d) comprehension in the sense of FAIR research data management? This is a multidimensional problem, because software needs to evolve, because of (1) bugfixing and (2) evolution of the software stack it is embedded in, such as underlying external data sets and their service APIs, security patches of the operating system or libraries, etc. Docker is only of local help, here. Software also comes in technical and functional variants and is a lively object that very much differs from passive data. Currently, research data management initiatives, such as the German FDMI, are only starting to address this.
- How to manage long-term evolution with fluctuating developer groups?
- How to manage, govern, and analyze variant-aware and variant-rich research software in long-term projects?
- What tools are needed to easily automate various tedious activities that researchers would like to avoid?
- What kinds of software engineering models are of use in RSE?
- How to integrate mathematical models (e.g. based on calculus), Software Engineering models (e.g. UML, SysML) and leverage their effective use in development?
- What are useful domain-specific languages (DSLs) for RSE, either to raise developer efficiency or to decrease quality issues?
- Which RSE activities can be assisted by DSLs?
- How can DSLs bridge the published mathematical, physical, biological, medical, etc. laws and findings on the one hand and the executable code on the other hand?
- Can mathematical / physical laws themselves be codified as DSL models and thus used for validation, testing or even code generation?
- What is appropriate meta-information about research software artifacts, their development states and forms of review, certifications etc. to build trust, enable reusability, and document quality?
- Refactoring the architecture of research software to fit future needs while retaining current capabilities?
- How can software analysis tools contribute to, e.g., checking consistency between mathematical models in published papers and the implemented code? Might this even lead to a change in the forms of our publications?
- How can traditional program analysis tools e.g. for dead code, inefficient code, architecture leaks, or unnecessary complexity effectively help the researchers to improve software quality?
- How to test and what to test in which intensity? Hat are sufficient tests in the context of big data sets or unclear desired outcomes? How to overcome the unknown test oracle problem?
- Is there a notion of test coverage for research software?
- What is high-quality assurance for research software in order to achieve high-quality research results? We need adequate and efficient testing, reasoning, reviewing, and certification procedures.
- How can an intelligent research co-pilot based on large language models help to address coding, testing, design and quality issues?
- How to quantitatively assess and optimize development skills for researchers?
- How much does the human developer play a role in RSE developments?
- How to design software for user studies in social and economic experiments that interact with test subjects?
- How to predict development efforts and costs of a scientific development process? ("CoMoMo for research software?")
- How to deal with legacy software or legacy hardware in a long-lasting software infrastructure setting? How to migrate scientific software?
- How to predict needed computational, storage and networking resources for a software experiment/simulation/study upfront?
- How to measure the scientific quality of research software?

Many of those questions are not specific to RSE, but apply to classic SE as well. While some of these questions are very general, the answers must typically be very domain-specific to gain improvements for the domain-specific challenges. Classic SE has many (and still optimizable) answers to these questions, but it is currently unclear, how they transfer to RSE.
