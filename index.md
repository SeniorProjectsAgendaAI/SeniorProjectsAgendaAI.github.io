---
## CS 426 Senior Project in Computer Science | Spring 2026 | University of Nevada, Reno | CSE Department

---

##  Project Overview

**Team Number:** 28  
**Team Name:** AgendaAI  
**GitHub Repository:** [SeniorProjectsAgendaAI/AgendaAI](https://github.com/SeniorProjectsAgendaAI/AgendaAI)  
**WebApp:** [Currently Inactive](https://creating-dockerfile.d2i3jqbsdy4snq.amplifyapp.com/)  

---

##  Team Members

<div class="team-list">
<div class="team-member">
<strong>James Accacio</strong>
<a href="https://github.com/Wollbey" aria-label="James Accacio's GitHub profile">GitHub Profile</a>
</div>

<div class="team-member">
<strong>Biniam Gashaw</strong>
<a href="https://github.com/BiniamGashaw" aria-label="Biniam Gashaw's GitHub profile">GitHub Profile</a>
</div>

<div class="team-member">
<strong>Ankush Joshi</strong>
<a href="https://github.com/aannkooss" aria-label="Ankush Joshi's GitHub profile">GitHub Profile</a>
</div>

<div class="team-member">
<strong>Alexander Medal</strong>
<a href="https://github.com/ItsAlexMedal" aria-label="Alexander Medal's GitHub profile">GitHub Profile</a>
</div>
</div>

---

##  Faculty & Advisors

<div class="team-list">
<div class="team-member">
<strong><a href="https://www.unr.edu/cse/people/david-feil-seifer">Dave Feil-Seifer</a></strong>
Advisor | University of Nevada, Reno
</div>

<div class="team-member">
<strong>Vinh Le</strong>
Instructor | University of Nevada, Reno
</div>

<div class="team-member">
<strong><a href="https://www.unr.edu/cse/people/emily-hand">Emily Hand</a></strong>
External Advisor | University of Nevada, Reno
</div>
</div>

---

##  Demo Video -To Be Updated. Temporary Placeholder-

<div class="video-container">
<iframe src="https://www.youtube.com/embed/At6WqP-ymIo?si=0GL_SGeYTtXdBADm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

---

##  Project Description

### The Problem

Students today face significant stress and time management conflicts due to the high level of context switching required to navigate fragmented academic and personal lives. Students often juggle multiple, incompatible platforms like Canvas for coursework, Google Calendar for meetings, and Gmail for updates, leading to a broken overview of their actual availability. AgendaAI introduces a unified, intelligent interface that consolidates data from different to make academic lives easier. AgendaAI addresses this by using Model Context Protocol (MCP) to fetch real-time data and update a student’s calendar accordingly to ensure deadlines aren’t missed.

### Intended Audience: 
AgendaAI primarily targets students from high school to college levels. We want to provide a tool that busy students can use to help them organize their academic and personal lives easier. Our intention is to help reduce the amount of platforms students have to go through just to get a clear sense of their schedule, and by reducing this cognitive load while improving time management skills, AgendaAI helps to accurately track the tasks, deadlines, and events necessary for a student’s academic life. This will also reduce the likelihood of important information being overlooked and allowing students to manage their time more effectively.

### Functionality and Capabilities:
AgendaAI is an AI-powered academic organization tool that uses Canvas, Gmail, and Google Calendar APIs to centralize assignments, events, and announcements into a single platform. Utilizing Google Gemini LLM to interpret and process unstructured academic information, such as lengthy emails and complex assignment descriptions, the agent is able to convert that information into actionable items using natural language processing. The MCP framework is what allows the agent to interact with connected services and execute tasks on the user’s behalf. The application is designed to be intuitive and visually appealing, which allows students to efficiently manage their schedules. 

### Technology Stack:
The frontend is built using Typescript with React to build UI and Axios is used for handling API requests. The backend uses a python base and fastAPI to manage integrations with external services. Natural Language processing command Model Context Protocol agents utilizing Gemini to interact with Canvas, Gmail, and Google Calendar. The Database uses PostgreSQL to store user and scheduling data. Hosting and cloud infrastructure are through AWS. 

---

##  Project Resources

### Problem Domain Book

<ul class="resource-list">
<li><strong>AI Agents with MCP</strong> - K. Stratis, O'Reilly Media (2026). Primary reference guiding the architecture, design, and implementation of Model Context Protocol (MCP) servers in Python for building large-scale agent capabilities.</li>
</ul>

### Websites Useful/Related to Your Project

<ul class="resource-list">
<li><strong>Motion</strong> - <a href="https://www.usemotion.com/" aria-label="Motion app official website">usemotion.com</a> - An AI-powered productivity platform and superapp for work management.</li>
<li><strong>myHomework Student Planner App</strong> - <a href="https://myhomeworkapp.com/" aria-label="myHomework planner app website">myhomeworkapp.com</a> - A mobile iOS application for tracking student classes, tests, and assignments.</li>
<li><strong>Reclaim</strong> - <a href="https://reclaim.ai/" aria-label="Reclaim AI calendar website">reclaim.ai</a> - An AI calendar tool designed to assist with work-life balance and focus hours through Google and Outlook integration.</li>
<li><strong>WCAG 2 Accessibility Guidelines</strong> - <a href="https://www.w3.org/WAI/standards-guidelines/wcag/#intro" aria-label="Web Content Accessibility Guidelines 2.0 Overview">Web Accessibility Initiative (WAI)</a> - Essential substandard guidelines ensuring web content is ADA compliant and accessible to people with disabilities.</li>
</ul>

### Technical Reports, Conference Papers, & Journal Articles

<ul class="resource-list">
<li><strong>SnoopMe: Interactive Task Scheduler for Students</strong> - IEEE Xplore (2019). Study detailing a mobile app designed to improve student time management and monitor smartphone distractions.</li>
<li><strong>AI in Academic Settings</strong> - Humanities and Social Sciences Communications (2023). Journal article analyzing the high adoption rate and perceived usefulness of ChatGPT and AI tools among university students.</li>
<li><strong>Code Execution with MCP</strong> - Anthropic Engineering. Technical report explaining the architectural benefits of MCP servers for executing complex logic and processing enormous datasets locally.</li>
</ul>

---

##  Detailed References

### Websites Useful/Related to Your Project

<div class="references">
<div class="reference">
<strong>[1]</strong> Motion, "Motion | Manage calendars, meetings, & tasks in one app," www.usemotion.com, 2024. <a href="https://www.usemotion.com/" aria-label="Link to Motion website">https://www.usemotion.com/</a>
<br/><em>Motion is self described as an AI Powered SuperApp for work. It is a productivity platform that provides customers with common business management tools such as Gantt charts, virtual project managers, meeting notetakers and integration with other platforms. Motion differs from our platform by focusing on corporate work rather than students in university.</em>
</div>

<div class="reference">
<strong>[2]</strong> "myHomework Student Planner App," Myhomeworkapp.com, 2019. <a href="https://myhomeworkapp.com/" aria-label="Link to myHomework app website">https://myhomeworkapp.com/</a>
<br/><em>The myHomework Student Planner App is a mobile app for ios platforms that allows a student to track classes, tests, assignments into an online calendar that allows use across devices. It can connect to Teachers.io but has no option to connect to canvas.</em>
</div>

<div class="reference">
<strong>[3]</strong> "Reclaim | Make time when there is none," Reclaim.ai, 2020. <a href="https://reclaim.ai/" aria-label="Link to Reclaim AI website">https://reclaim.ai/</a>
<br/><em>Reclaim is an AI calendar that integrates with an existing google calendar or outlook calendar that focuses on assisting with work life balance. The AI will suggest changes to the user’s calendar in order to fit a certain user set goal for focus hours. The goal of reclaim differs from AgendaAi as it focuses on altering the schedule to create gaps, rather than aggregate data from connected services.</em>
</div>

<div class="reference">
<strong>[4]</strong> W. W. A. I. (WAI), "WCAG 2 Overview", Web Accessibility Initiative (WAI), 2024. <a href="https://www.w3.org/WAI/standards-guidelines/wcag/#intro" aria-label="Link to WCAG 2 Overview">https://www.w3.org/WAI/standards-guidelines/wcag/#intro</a>
<br/><em>WCAG 2 is a specific substandard from the Web Accessibility Initiative with the goal of making web content more accessible to people with disabilities. The standard has stipulations regarding the attributes and characteristics of any text, images, colour, controls, or navigation systems within a website. It also contains general recommendations that aren't required but can be used to create a sense of conformity between websites.</em>
</div>
</div>

### Problem-Domain Book

<div class="references">
<div class="reference">
<strong>[5]</strong> K. STRATIS, <em>AI Agents with MCP: Model Context Protocol for Building Clients, Services, and End-to-End Agents</em>. S.l.: O'REILLY MEDIA, 2026.
<br/><em>"AI Agents with MCP" is a book that highlights exactly how we will implement MCP in our project. It will guide us in designing the architecture for our agent, showing us how to build complete MCP servers in Python, as well as extending agent capabilities for large-scale solutions. In short, this book will be a primary guide for the development for our project.</em>
</div>
</div>

### Technical Reports, Conference Papers, and Journal Articles

<div class="references">
<div class="reference">
<strong>[6]</strong> "SnoopMe-Interactive Task Scheduler mobile application for students," <em>IEEE Conference Publication | IEEE Xplore</em>, Jan. 01, 2019. <a href="https://ieeexplore.ieee.org/abstract/document/8945836" aria-label="Link to SnoopMe IEEE paper">https://ieeexplore.ieee.org/abstract/document/8945836</a>
<br/><em>This paper introduces "SnoopMe," a mobile app designed to improve student time management by addressing smartphone distractions. The app functions as a smart scheduler, allowing students to set tasks and deadlines. Uniquely, it also monitors their mobile app usage, provides graphical reports, and sends alerts recommending they restrict phone use to complete their work. A study of 30 undergraduate students who used the app for one week provided positive feedback.</em>
</div>

<div class="reference">
<strong>[7]</strong> J. Von Garrel and J. Mayer, "Artificial Intelligence in studies—use of ChatGPT and AI-based tools among students in Germany," <em>Humanities and Social Sciences Communications</em>, vol. 10, no. 1, Nov. 2023, doi: 10.1057/s41599-023-02304-7.
<br/><em>The research on 875 students in Germany reported that 80% of students use AI for tasks like clarifying concepts, writing, and literature. Perceived usefulness was the primary prediction for students to start using AI in their school work. Almost half of all students surveyed mention that ChatGPT was a tool they use for school work. This study shows how AI has integrated itself into a student’s schoolwork.</em>
</div>

<div class="reference">
<strong>[8]</strong> "Code execution with MCP: building more efficient AI agents." <em>Anthropic Engineering</em>. <a href="https://www.anthropic.com/engineering/code-execution-with-mcp" aria-label="Link to Anthropic Engineering article">https://www.anthropic.com/engineering/code-execution-with-mcp</a>
<br/><em>The key benefit of presenting MCP servers as code APIs on a virtual filesystem is that it moves complex logic and heavy data processing out of the model's limited context window and into a dedicated secure execution environment. This approach allows the AI agent to load tools only when needed and filter enormous datasets locally.</em>
</div>
</div>

---

##  Project Status

**Current Phase:** Development & Integration (Spring 2026)

**Completed Components:**
 Canvas LMS Integration with timezone support  
 Backend API framework (FastAPI)  
 Google Calendar and Gmail support  
 Frontend dashboard interface  
 User authentication with AWS Cognito  

**In Progress:**
 Advanced AI task parsing with Gemini  
 MCP agent implementation  
 Email-to-task conversion  

**Upcoming:**
 Comprehensive testing and QA  
 User feedback integration  
 Performance optimization  
 Full accessibility audit (WCAG 2.1 AA)  

---

For questions or feedback about AgendaAI, please visit our [GitHub repository](https://github.com/SeniorProjectsAgendaAI/AgendaAI).

**Last Updated:** April 18, 2026  
**Project Website:** Maintained as per CS 426 requirements for one year post-semester.  
**Note:** This website will remain available for reference and future project continuation.
