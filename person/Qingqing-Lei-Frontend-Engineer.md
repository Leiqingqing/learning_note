# Qingqing Lei

**Target Role: Full-stack Engineer (Frontend-focused)**

- Gender: Female
- Phone: 18815619962
- Email: [480293335@qq.com](mailto:480293335@qq.com)
- Experience: 7 years

## Education

### Huaibei Normal University

- Degree: Bachelor's (Full-time)
- Major: Network Engineering
- Period: September 2015—June 2019

## Work Experience

### Nokia Shanghai Co., Ltd.

**Full-stack Engineer｜August 2025—Present**

- Develop device status monitoring, topology management, configuration updates, and related features for a telecommunications equipment management system.
- Build business Agents with AI, using Prompt Engineering and Skills to define workflow processes.

### Shanghai Jinyi E-Commerce Co., Ltd.

**Python Engineer / Frontend Engineer｜July 2019—March 2025**

**Frontend Engineer｜September 2020—March 2025**

- Participated in requirements scoping and developed PC and mini-program clients for multiple transportation-and-sales business systems.

**Python Developer｜July 2019—August 2020**

- Developed coal procurement, sales, and quality-inspection workflows for an enterprise coal procurement-and-sales management system, and maintained production modules through ongoing iterations.
- Built visual reports with BI tools.

## Skills

1. Solid Python fundamentals; familiar with FastAPI and ORM frameworks; proficient in routing, middleware, async programming, long-lived connections, and exception handling.
2. Proficient in React, TypeScript, and the surrounding ecosystem, with a working understanding of framework internals and extensive experience encapsulating and extracting reusable components and Hooks.
3. Proficient with LangChain, LangGraph, and related frameworks; experienced in Prompt Engineering, Function Calling, and the MCP protocol.
4. Familiar with agent development workflows, including task decomposition, Skills, multi-agent collaboration, and short- and long-term memory.
5. Hands-on experience building RAG systems from scratch: multi-source heterogeneous data loading, text chunking, embeddings, and retrieval optimization.
6. Familiar with HTTP/HTTPS, WebSocket long-lived connections, and SSE streaming.
7. Familiar with Webpack, Vite, and other frontend build tools, and with frontend performance optimization. Able to design, develop, and troubleshoot large frontend projects end to end.
8. Familiar with MySQL, SQLite, Vectorize, and other databases; able to write complex SQL and build data-visualization applications with BI dashboards.
9. Familiar with the Taro ecosystem and experienced in cross-platform development.
10. Familiar with CI/CD pipelines and Jenkins automated deployment.
11. Strong English reading and writing skills; comfortable working in a fully English-speaking development environment.

## Projects

### Access Network Platform (Altiplano) Intelligent Assistant

**Full-stack Engineer｜January 2026—Present**

**Overview**

An LLM-powered assistant for the Altiplano access network platform. It hides complex configuration dependencies behind natural-language interaction, so end-to-end configuration can be completed with minimal user effort. The project also builds telecom-industry and enterprise knowledge bases for professional, trustworthy, and source-traceable knowledge Q&A, and integrates Playbook tools for local deployment, upgrades, progress tracking, result verification, and failure recovery.

**Tech Stack**

Python｜LangChain｜LangGraph｜PostgreSQL｜Milvus｜MongoDB｜React｜TypeScript

**Highlights**

1. Unified model and tool invocation with LangChain, and orchestrated Altiplano version confirmation, deployment and upgrades, progress tracking, result verification, failure recovery, and human fallback with LangGraph, reducing the operational complexity of platform deployment and upgrades.
2. Built a Multi-Agent architecture in which a main Agent calls an Intent Agent for intent recognition and routes tasks to a Knowledge Q&A Agent, a Platform Deployment Agent, or an End-to-End Configuration Agent.
3. Built telecom-industry and enterprise knowledge bases on a RAG architecture: HTML-to-Markdown conversion, structure parsing, semantic chunking, metadata tagging, embedding vectorization, and Milvus retrieval, enabling professional Q&A with source tracing.
4. Improved Q&A accuracy and trustworthiness through Prompt constraints, citation checks, risk rules, and refusal when evidence is insufficient; introduced a Q&A evaluation mechanism and stored evaluation results and user feedback as a basis for later review and optimization.
5. Built hybrid short-term memory with Redis to store recent conversations, session summaries, and structured key information, supporting follow-up questions, context inheritance, and user corrections in knowledge Q&A.
6. Used Human-in-the-loop for missing configuration parameters, conflict confirmation, and risk approval; wrapped Altiplano platform operations via Tool Calling and combined them with NETCONF for configuration push, status queries, parameter validation, and result verification, completing end-to-end configuration with minimal interaction.
7. Implemented streaming output with SSE and a typewriter effect on the client.

### Telecommunications Equipment Management System

**Full-stack Engineer｜August 2025—Present**

**Overview**

A system for centralized management and operations of telecommunications equipment, covering device status monitoring, topology management, configuration updates, and alarm handling. It includes a legacy AngularJS version and a new React version.

**Tech Stack**

React｜Valtio｜Webpack｜npm｜AngularJS

**Highlights**

1. Set up and rolled out ESLint + Prettier in the React project, significantly improving code quality and team collaboration.
2. Built device topology views with xyflow, strengthening data visualization and helping users understand structural relationships more quickly.
3. Led the UI component library upgrade, improving system stability and future extensibility without affecting existing business features.
4. Quickly learned the legacy AngularJS development model and independently delivered new requirements, significantly shortening delivery cycles.
5. Optimized the WebSocket connection path to improve duplex-communication stability, and displayed cutover-task progress in real time.
6. Completed the AngularJS Material upgrade, reducing technical debt and improving UI consistency and maintainability.
7. Built an end-to-end Extension testing workflow with Skills and Prompt Engineering, reducing configuration complexity and improving development efficiency.
8. Broke down requirements quickly and used vibe coding to write Java unit tests, achieving code coverage above 90%.

### Online Bidding Management Platform

**Frontend Engineer｜September 2022—March 2025**

**Overview**

A React-based B2C bidding platform covering bidding sessions, material bidding, product listings, and order management. Users can browse products, participate in bidding, and manage teams.

**Tech Stack**

React｜TypeScript｜Formily｜Zustand｜Lexical｜Vite｜Pnpm｜Prisma｜Ant Design

**Highlights**

1. Combined Zustand and React Context for global state management, reducing unnecessary re-renders and improving page responsiveness.
2. Wrote Node.js scripts with Prisma to convert rich-text JSON to HTML, supporting a smooth data migration between the old and new platforms.
3. Adopted Vite to speed up project builds and improve development efficiency.
4. Set up a Pnpm Monorepo to manage B-end, C-end, and shared components in one place, improving overall collaborative development efficiency.
5. Adjusted CI/CD scripts and worked with a Jenkins upgrade to improve the automated deployment pipeline and speed up releases.
6. Used Formily to build complex forms quickly, handling multi-field linkage and dynamic validation and reducing data-entry errors.

