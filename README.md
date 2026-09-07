# 🧑‍💻 Learning from Scratch

<div align="center">
  
  [Badges from https://img.shields.io/ and https://shieldcn.dev/gen?url=lilyfleetingcraig/learning-from-scratch]: # 
  
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://www.shieldcn.dev/github/last-commit/lilyfleetingcraig/learning-from-scratch.svg?variant=secondary&amp;size=sm&amp;mode=dark"><img alt="Last commit" src="https://www.shieldcn.dev/github/last-commit/lilyfleetingcraig/learning-from-scratch.svg?variant=secondary&amp;size=sm&amp;mode=light"></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://www.shieldcn.dev/github/commits/lilyfleetingcraig/learning-from-scratch.svg?variant=secondary&amp;size=sm&amp;mode=dark"><img alt="Commits" src="https://www.shieldcn.dev/github/commits/lilyfleetingcraig/learning-from-scratch.svg?variant=secondary&amp;size=sm&amp;mode=light"></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://www.shieldcn.dev/github/merged-prs/lilyfleetingcraig/learning-from-scratch.svg?variant=ghost&amp;size=sm&amp;mode=dark"><img alt="Merged PRs" src="https://www.shieldcn.dev/github/merged-prs/lilyfleetingcraig/learning-from-scratch.svg?variant=ghost&amp;size=sm&amp;mode=light"></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://www.shieldcn.dev/github/ci/lilyfleetingcraig/learning-from-scratch.svg?variant=secondary&amp;size=sm&amp;mode=dark"><img alt="CI" src="https://www.shieldcn.dev/github/ci/lilyfleetingcraig/learning-from-scratch.svg?variant=secondary&amp;size=sm&amp;mode=light"></picture>
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://www.shieldcn.dev/github/license/lilyfleetingcraig/learning-from-scratch.svg?variant=ghost&amp;size=sm&amp;mode=dark"><img alt="License" src="https://www.shieldcn.dev/github/license/lilyfleetingcraig/learning-from-scratch.svg?variant=ghost&amp;size=sm&amp;mode=light"></picture>

  [![LaTeX](https://img.shields.io/badge/LaTeX-00A0A0?logo=latex&logoColor=fff)](#)
  [![npm](https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=fff)](#)
  [![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff)](#)
  [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)](#)
  [![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#)
  [![CSS](https://img.shields.io/badge/CSS-639?logo=css&logoColor=fff)](#)
</div>



Web programming is considered an engaging entry point to learning to code, but it comes with its own set of challenges that can push away novices. Block-based programming is a popular solution to this problem, however no accessible system exists for young students. This project investigated the usability of WebBlocks, a new simpliﬁed block-based editor for HTML and CSS. It was found that participants reported signiﬁcantly higher perceptions of ease of web programming after use of the system, though there is room for improvements to be made to support usability for inexperienced users speciﬁcally.

WebBlocks, a new block-based programming environment for web development languages, was produced to oﬀer an accessible and engaging entry point to coding. To be suitable as a ﬁrst exposure to programming under a spiral curriculum approach, the editor presents HTML and CSS code in a plain-English language. The system allows users to program HTML and CSS in separate environments, while viewing a live preview of their site and its rendered code.

An experimental evaluation was performed which generally showed very strong usability among experienced users, and fair usability among inexperienced ones. Most interestingly, users showed statistically signiﬁcant increases after use of WebBlocks in perceptions of ease of web programming in both experienced and inexperienced cohorts, as well as a signiﬁcant increase in conﬁdence in the experienced group.

- [View the dissertation online](https://lilyfleetingcraig.github.io/dissertation/): here you can access the dissertation report.
- `dissertation.pdf`: the dissertation can also be accessed as the original PDF at `dissertation.pdf`.
- [WebBlocks prototype](https://lilyfleetingcraig.github.io/dissertation/webblocks/): here you can view the completed WebBlocks prototype developed over the course of the project.

This project has now been succeeded by web-block:

- [New web-blocks repository](https://github.com/lilyfleetingcraig/web-blocks): here you can see the current continued development of the project on GitHub.
- [New web-blocks system](https://lilyfleetingcraig.github.io/web-blocks/): additionally, the continued development of the project can be viewed live.

### 🎉 Reflection

The biggest constraint on the development of this project was the limited time available. I would have loved to create a more comprehensive solution of the possible features discussed, as this could potentially oﬀer an engaging and widely accessible introduction to coding for children. Further, I would have liked to implement multiple abstraction layers over the language used as this could oﬀer novel contributions to the research community. I also would have been interested to see this system tested in classrooms in the real world, as this could evaluate its eﬀectiveness more reliably. If I was to ﬁnd myself again at the beginning of the project, I would have written a more extensible architecture for the language used in blocks, and their translations to code. I would use inheritance and implementations of interfaces to ensure that new abstraction layers could be seamlessly added without disruption to the overall structure of the system.

## 📃 Dissertation

This project was completed as my final dissertation in BSc Computing Science at the University of Glasgow. The dissertation can be viewed online [here](https://lilyfleetingcraig.github.io/dissertation/), or alternatively as a PDF in `dissertation.pdf`. An overview of the structure of the dissertation is provided below...

### 💭 Introduction

In this chapter, motivations are described for a new programming environment for beginners to web development languages. The aims for the development of the novel WebBlocks block-based web programming system are subsequently deﬁned.

### 🔭 Background

In this chapter, concepts and literature in key problem areas of block-based programming and abstraction levels in scaﬀolded learning are reviewed, and several existing and similar block-based programming environments are presented. The usability of these systems is then contrasted and compared with respect to a design framework, and key heuristics and features to contribute to a positive and accessible experience are outlined. Lastly, a product gap in these solutions is proposed.

### 📌 Analysis

This chapter presents the elicitation and prioritisation of both functional and non-functional software requirements. Personas representing the typical users of the system were produced, which were then used to derive expected use cases in the form of user stories. From these, sets of both functional and non-functional requirements were then created, and assigned a priority through the MoSCoW process. This deﬁned the core minimum viable product for the system in line with its time limitations for production.

### 🎨 Design

In this chapter, a design solution is proposed in line with the speciﬁcation identiﬁed in Chapter 3.3. Wireframes for each page of the site’s core functionality are presented and described with reference to their fulﬁlment of each requirement, as well as relevant design principles under Nielsen’s usability framework.

### 💻 Implementation

In this chapter, the choices made during the course of the project are identiﬁed and described. This includes the development methods used to minimise the time and eﬀort required for implementation, as well as the architecture of the ﬁnal software product, and the problems experienced over the course of its development.

### 👩‍🔬 Evaluation

This chapter describes the process of an experimental evaluation of the new WebBlocks system. Demographics and backgrounds of participants are described, and quantitative measures of task performance using the site are given. Finally, survey responses on usability and favourability are discussed, as well as changes in user perceptions on ability and enjoyability of web programming after use of the system.

### 🎯 Conclusion

This chapter provides an overview of the WebBlocks application which has been implemented over the course of the project, and key ﬁndings of its evaluation are revisited. Reﬂection is made on the progress of the development and the decisions made throughout, as well as areas which may have beneﬁted from a different approach. Lastly, suggestions for future work are given.

## 💻 WebBlocks Code

<div float="left" align="center">
  <img width="45%" src="https://github.com/user-attachments/assets/78d64d05-a413-41f4-8aa3-a7b89f3898b9" />
  <img width="45%" src="https://github.com/user-attachments/assets/7a2d0bfe-1322-4ffc-9768-36b8ae0de63f" />
</div>

WebBlocks is a new block-based programming editor which allows novices users to create websites using a code-by-blocks approach. Users are able to code both the structure and style of the page using separate environments, while viewing a preview of either the rendered site or its compiled code - this is demonstrated above. 

The completed WebBlocks prototype developed over the course of the project can be accessed [here](https://lilyfleetingcraig.github.io/dissertation/webblocks/) - the codebase can be found in `/webblocks/`. If you want to run the code yourself, you can find instructions in `manual.md`. Additionally, if you want to see the current further progress of development, feel free to visit [here](https://lilyfleetingcraig.github.io/web-blocks/), or the [web-blocks repository](https://github.com/lilyfleetingcraig/web-blocks) on GitHub.

WebBlocks uses a simple plain-English language in order to be accessible particularly to young novices of web development languages - however, as this is only an initial prototype demonstration, further work is needed to find a common language that performs well among this demographic rather than the initial choices contained within.