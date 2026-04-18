---
layout: default
---

# AgendaAI
## CS 426 Senior Project in Computer Science | Spring 2025 | University of Nevada, Reno | CSE Department

---

##  Project Overview

**Team Number:** 28  
**Team Name:** AgendaAI  
**GitHub Repository:** [SeniorProjectsAgendaAI/AgendaAI](https://github.com/SeniorProjectsAgendaAI/AgendaAI)

---

## 👥 Team Members

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

##  Demo Video

<div class="video-container">
<iframe src="https://www.youtube.com/embed/wdLXmoTWq3k?si=wzcOlBFSYZdvI0o9" title="AgendaAI Project Demo Video - Concept and Layout Overview" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

---

## 💡 Project Description

### The Problem

In today's academic world, resources are scattered across different platforms, making it difficult to keep track of everything. Assignments exist on Canvas, online lectures happen on Zoom, emails arrive across multiple platforms, and calendars are fragmented across services. This fragmentation creates significant cognitive overload and makes it easy to miss deadlines and important events.

Students today face a critical pain point: **the necessity to actively juggle and monitor numerous applications to maintain awareness of their academic responsibilities.**

### Target Audience

AgendaAI is designed for:
- **Undergraduate students** managing multiple courses and part-time work
- **Graduate students** balancing research, teaching, and coursework
- **Working students** coordinating school with full-time employment
- **All students** seeking to reduce cognitive overload and improve time management

The public interest in this product is significant—it reduces the number of applications users must filter through to gain a clear understanding of their schedule. By decreasing cognitive overload and improving time management for students navigating increasingly complex academic environments, AgendaAI helps accurately track the tasks, deadlines, and events necessary for academic success while allowing students to manage their time more effectively.

### How It Works

AgendaAI is an **AI-powered academic organization tool** that:

1. **Integrates Multiple Services** - Connects Canvas, Gmail, and Google Calendar through their official APIs to centralize assignments, events, and announcements
2. **Processes Unstructured Information** - Utilizes advanced language models (Gemini LLM) to interpret complex assignment descriptions, lengthy emails, and event details
3. **Powers AI Assistance** - Employs a Model Context Protocol (MCP) agent that interacts directly with connected services, executing tasks with user-defined permissions
4. **Natural Language Interaction** - Allows users to interact via natural language commands to create tasks, schedule study sessions, and receive organized summaries
5. **Intuitive Interface** - Provides a visually appealing, clarity-focused design that emphasizes ease of use

### Key Features

-  **Centralized Dashboard** - View all assignments, tasks, and events in one place
-  **Email & Event Integration** - Automatically imports from Gmail, Canvas, and Google Calendar
-  **Natural Language Commands** - Interact with your schedule using simple text commands
-  **Cross-Platform Sync** - Seamless synchronization across all integrated services
-  **Timezone-Aware Scheduling** - Proper handling of assignments and events across timezones

---

##  Project Resources

### Technical & Conceptual Resources

<ul class="resource-list">
<li><strong>AI Agents with MCP</strong> - K. Stratis, O'Reilly Media (2026). Primary reference for implementing Model Context Protocol servers and building scalable AI agents in Python.</li>
<li><strong>WCAG 2 Accessibility Guidelines</strong> - <a href="https://www.w3.org/WAI/standards-guidelines/wcag/#intro" aria-label="Web Content Accessibility Guidelines 2.0">Web Accessibility Initiative (WAI)</a> - Ensures our application meets accessibility standards.</li>
<li><strong>GitHub Repository</strong> - <a href="https://github.com/SeniorProjectsAgendaAI/AgendaAI" aria-label="AgendaAI GitHub repository">SeniorProjectsAgendaAI/AgendaAI</a> - Full source code and development documentation.</li>
<li><strong>Canvas API Documentation</strong> - <a href="https://canvas.instructure.com/doc/api/" aria-label="Canvas LMS API documentation">Canvas Instructure</a> - Official API reference for Canvas LMS integration.</li>
<li><strong>Google Workspace APIs</strong> - <a href="https://developers.google.com/workspace/apis" aria-label="Google Workspace APIs documentation">Google Developers</a> - Documentation for Gmail and Google Calendar integration.</li>
</ul>

### Problem Domain & Related Work

<ul class="resource-list">
<li><strong>SnoopMe: Interactive Task Scheduler for Students</strong> - IEEE Xplore (2019). A mobile app designed to improve student time management by addressing smartphone distractions and providing real-time alerts.</li>
<li><strong>AI in Academic Settings</strong> - Von Garrel & Mayer (2023). Research on 875 German students showing 80% use AI for academic tasks, with high perceived usefulness in schoolwork.</li>
<li><strong>MCP for AI Agents</strong> - Anthropic Engineering. Explores how MCP moves complex logic out of model context windows into dedicated execution environments for efficient AI operations.</li>
</ul>

### News & Updates

- **Spring 2025** - Initial project development and Canvas integration completed
- **Development** - AI-powered task parsing and email integration in progress
- **Ongoing** - User testing and interface refinement with focus on accessibility

---

##  Detailed References

### Accessibility Standards

<div class="references">
<div class="reference">
<strong>[1]</strong> W. W. A. I. (WAI), "WCAG 2 Overview", Web Accessibility Initiative (WAI), 2024. <a href="https://www.w3.org/WAI/standards-guidelines/wcag/#intro">https://www.w3.org/WAI/standards-guidelines/wcag/#intro</a>
<br/><em>The Web Content Accessibility Guidelines 2.0 (WCAG 2.0) form the foundation of our accessibility compliance strategy, ensuring that AgendaAI is usable by all students regardless of abilities.</em>
</div>
</div>

### Problem Domain Book

<div class="references">
<div class="reference">
<strong>[2]</strong> K. STRATIS, <em>AI Agents with MCP: Model Context Protocol for Building Clients, Services, and End-to-End Agents</em>. O'REILLY MEDIA, 2026.
<br/><em>This book provides the foundational architecture and patterns for implementing Model Context Protocol in our project. It guides us through building MCP servers in Python and extending agent capabilities for large-scale solutions—a primary reference for our development approach.</em>
</div>
</div>

### Peer-Reviewed Articles

<div class="references">
<div class="reference">
<strong>[3]</strong> "SnoopMe—Interactive Task Scheduler Mobile Application for Students," <em>IEEE Conference Publication</em> | IEEE Xplore, January 2019. <a href="https://ieeexplore.ieee.org/abstract/document/8945836">https://ieeexplore.ieee.org/abstract/document/8945836</a>
<br/><em>Introduces a mobile app designed to improve student time management by addressing smartphone distractions. Provides direct comparison point for AgendaAI's approach to task scheduling and student engagement. A study of 30 undergraduate students demonstrated positive outcomes for time management applications.</em>
</div>

<div class="reference">
<strong>[4]</strong> J. Von Garrel and J. Mayer, "Artificial Intelligence in Studies—Use of ChatGPT and AI-based Tools Among Students in Germany," <em>Humanities and Social Sciences Communications</em>, vol. 10, no. 1, November 2023, doi: 10.1057/s41599-023-02304-7.
<br/><em>Research on 875 German students showing that 80% of students use AI for tasks like clarifying concepts, writing, and academic work. Nearly 50% use ChatGPT for schoolwork. Validates the market demand for AI-powered academic tools and demonstrates that perceived usefulness is the primary driver of adoption in educational contexts.</em>
</div>

<div class="reference">
<strong>[5]</strong> "Code Execution with MCP: Building More Efficient AI Agents," <em>Anthropic Engineering</em>. <a href="https://www.anthropic.com/engineering/code-execution-with-mcp">https://www.anthropic.com/engineering/code-execution-with-mcp</a>
<br/><em>Explains the architectural benefit of MCP servers as code APIs on virtual filesystems—moving heavy data processing out of the model's limited context window into dedicated execution environments. This approach allows AgendaAI's AI agent to load tools efficiently and filter large datasets locally.</em>
</div>
</div>

---

##  Project Status

**Current Phase:** Development & Integration (Spring 2025)

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

## 📞 Contact & Support

For questions or feedback about AgendaAI, please visit our [GitHub repository](https://github.com/SeniorProjectsAgendaAI/AgendaAI) or contact the team through the provided GitHub profiles.

---

**Last Updated:** April 18, 2025  
**Project Website:** Maintained as per CS 426 requirements for one year post-semester.  
**Note:** This website will remain available for reference and future project continuation.
