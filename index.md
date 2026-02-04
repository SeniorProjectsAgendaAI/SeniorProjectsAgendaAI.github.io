---
layout: default
---

<!--Text can be **bold**, _italic_, or ~~strikethrough~~.-->
# CS 426 Senior Project in Computer Science - Spring 2025 - UNR CSE
## [Team 28](https://github.com/SeniorProjectsAgendaAI/AgendaAI)

# Members
* [James Accacio](https://github.com/Wollbey)
* [Biniam Gashaw](https://github.com/BiniamGashaw)
* [Ankush Joshi](https://github.com/aannkooss)
* [Alexander Medal](https://github.com/ItsAlexMedal)

# Instructors and Advisor
* [Dave Feil-Seifer](https://www.unr.edu/cse/people/david-feil-seifer) 
* Vinh Le
* [Emily Hand](https://www.unr.edu/cse/people/emily-hand)


# Demo Video
#### Temporary video for concept/layout
<iframe width="350" height="196" src="https://www.youtube.com/embed/wdLXmoTWq3k?si=wzcOlBFSYZdvI0o9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Project Description
## Problem

In today’s academic world, resources are scattered across different platforms, making it difficult to keep track of everything. For example, assignments are on canvas, online lectures take place on zoom, and emails on all platforms. Since there is such a large spread of where things are, it is easy to miss deadlines and important events. Our project targets this by centralizing information so deadlines and events aren't missed.


## Intended Audience

The intended audience of our project will be students. The intention of the app is to give students with busy schedules from both school and life outside of school a tool that will help them organize their time easily and better manage time. Students in our case refers to undergraduate students, graduate students, and working students that all have different
scheduling requirements. The public interest in this product is that it reduces the number of applications a user must filter through to gain a clear understanding of their schedule. By decreasing cognitive overload and improving time management for students navigating increasingly complex academic environments, AgendaAI helps accurately track the tasks, deadlines, and events necessary for a student’s academic life. This reduces the likelihood that important information is overlooked and allows students to manage their time more effectively.


## Functionality and Capabilities

AgendaAI is an AI powered academic organization tool that integrates multiple student focused services, including Canvas, Gmail, and Google Calendar, through their respective APIs to centralize assignments, events, and announcements into a single platform. The system utilizes a large language model (Gemini) to interpret and process unstructured academic information, such as lengthy emails and complex assignment descriptions, and convert them into actionable items using natural language processing. A key component of AgendaAI is its use of a Model Context Protocol (MCP) agent, which enables the AI to interact directly with connected services and perform tasks on behalf of the user while operating within defined permissions. Users can interact with the system using natural language commands to create tasks, schedule study sessions, and receive organized summaries of their academic responsibilities. The application is designed with an intuitive, visually appealing interface that emphasizes clarity and ease of use, allowing students to efficiently manage their schedules and reduce cognitive overload.



<!--
#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip
-->

# References
## Accessibility Standards
[1] W. W. A. I. (WAI), “WCAG 2 Overview”, Web Accessibility Initiative (WAI), 2024.
https://www.w3.org/WAI/standards-guidelines/wcag/#intro

## Problem-Domain Book - (Citations not directly referenced in this document)
[2] K. STRATIS, Ai Agents with MCP: Model Context Protocol for Building Clients, Services, and End-to-End Agents. S.l.: O’REILLY MEDIA, 2026. 
“AI Agents with MCP” 

A book that highlights exactly how we will implement MCP in our project. It will guide us in designing the architecture for our agent, showing us how to build complete MCP servers in Python, as well as extending agent capabilities for large-scale solutions. In short, this book will be a primary guide for the development for our project
.
## Peer-reviewed Articles  - (Citations not directly referenced in this document)
[3]“SnoopMe-Interactive Task Scheduler mobile application for students,” IEEE Conference Publication | IEEE Xplore, Jan. 01, 2019. https://ieeexplore.ieee.org/abstract/document/8945836
This paper introduces "SnoopMe," 

A mobile app designed to improve student time management by addressing smartphone distractions. The app functions as a smart scheduler, allowing students to set tasks and deadlines. Uniquely, it also monitors their mobile app usage, provides graphical reports, and sends alerts recommending they restrict phone use to complete their work. A study of 30 undergraduate students who used the app for one week provided positive feedback.


[4] J. Von Garrel and J. Mayer, “Artificial Intelligence in studies—use of ChatGPT and AI-based tools among students in Germany,” Humanities and Social Sciences Communications, vol. 10, no. 1, Nov. 2023, doi: 10.1057/s41599-023-02304-7. 

The research on 875 students in Germany reported that 80% of students use AI for tasks like clarifying concepts, writing, and literature. Perceived usefulness was the primary prediction for students to start using AI in their school work. Almost half of all students surveyed mention that ChatGPT was a tool they use for school work. This study shows how AI has integrated itself into a student’s schoolwork.


[5]“Code execution with MCP: building more efficient AI agents.” https://www.anthropic.com/engineering/code-execution-with-mcp

The key benefit of presenting MCP servers as code APIs on a virtual filesystem is that it moves complex logic and heavy data processing out of the model's limited context window and into a dedicated secure execution environment. This approach allows the AI agent to load tools only when needed and filter enormous datasets locally. 
