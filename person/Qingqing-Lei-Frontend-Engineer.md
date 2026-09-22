# Qingqing Lei

**Target Role: Frontend Engineer**

- Gender: Female
- Phone: 18815619962
- Email: [480293335@qq.com](mailto:480293335@qq.com)
- Experience: 7 years

## Summary

Five years of frontend development and one year of backend development. Experienced in frontend–backend separated development and in agent application workflows. Able to adapt quickly across tech stacks, with a strong focus on code quality.Familiar with AWS.Can take on critical work in complex projects and continuously deliver value. Strong English reading and writing skills; comfortable working in a fully English-speaking development environment.

## Education



### Huaibei Normal University

- Degree: Bachelor's
- Major: Network Engineering
- Period: 2015—2019



## Work Experience



### Nokia Shanghai Bell Co., Ltd.

**Full-stack Engineer (OD)｜August 2025—Present**

- Own core business development for a telecommunications equipment management system.
- Drive coding standards and architecture optimization.
- Abstract reusable business components to speed up page development.
- Upgrade the UI component library.
- Develop new requirements for a legacy AngularJS project and complete the AngularJS Material upgrade.
- Build business Agents with AI, using Prompt Engineering and Skills to define workflow processes.



### Shanghai Jinyi E-Commerce Co., Ltd.

**Python Developer / Frontend Engineer｜July 2019—March 2025**

**Frontend Engineer｜September 2020—March 2025**

- Participated in requirements scoping and developed PC and mini-program clients for multiple business systems.

**Python Developer｜July 2019—August 2020**

- Developed coal procurement, sales, and quality-inspection features for an enterprise coal procurement and sales management system; optimized the UI; maintained production modules and delivered ongoing iterations.
- Built visual reports with BI tools.



## Skills

1. Solid Python fundamentals; familiar with FastAPI and SQLAlchemy ORM; proficient in routing, middleware, async programming, long-lived connections, and exception handling.
2. Familiar with Next.js, Hono, Zod, and Drizzle ORM; experienced in full-stack development and Monorepo engineering.
3. Proficient with LangChain, LangGraph, and related frameworks; experienced in Prompt Engineering, Function Calling, and the MCP protocol.
4. Familiar with agent development workflows, including task decomposition, Skills, multi-agent collaboration, and short-/long-term memory.
5. Hands-on experience building RAG systems from scratch: multi-source heterogeneous data loading, text chunking, embeddings, and retrieval optimization.
6. Regularly use GitHub Copilot and other generative AI tools for requirement breakdown, implementation, unit tests, and Code Review.
7. Strong React and ecosystem skills, with a working understanding of framework internals and extensive experience encapsulating and extracting reusable components and Hooks.
8. Familiar with Webpack, Vite, and other frontend build tools, and with frontend performance optimization. Able to design, develop, and troubleshoot large frontend projects end to end.
9. Familiar with MySQL, PostgreSQL, MongoDB, and other databases; able to write complex SQL and build data visualization applications with BI dashboards.
10. Familiar with CI/CD, Jenkins automated deployment, and AWS.
11. Strong English reading and writing skills; comfortable working in a fully English-speaking development environment.



## Projects



### Access Network Platform (Altiplano) Intelligent Assistant

**Full-stack Engineer｜April 2026—Present**

**Overview**

An LLM-powered assistant for the Altiplano access network platform. It hides complex configuration dependencies behind natural-language interaction, so end-to-end configuration can be completed with minimal user effort. The project also builds telecom-industry and enterprise knowledge bases for professional, trustworthy, and source-traceable knowledge Q&A, and integrates Playbook tools to support local deployment, upgrades, progress tracking, result verification, and failure recovery.

**Tech Stack**

Python｜LangChain｜LangGraph｜PostgreSQL｜Milvus｜SQLAlchemy 2.0｜MongoDB

**Highlights**

1. Unified model and tool invocation with LangChain, and orchestrated Altiplano version confirmation, deployment and upgrades, progress tracking, result verification, failure recovery, and human fallback with LangGraph, reducing the operational complexity of platform deployment and upgrades.
2. Built a Multi-Agent architecture in which a main Agent calls an Intent Agent for intent recognition and routes tasks to a Knowledge Q&A Agent, a Platform Deployment Agent, or an End-to-End Configuration Agent.
3. Built telecom-industry and enterprise knowledge bases on a RAG architecture: HTML-to-Markdown conversion, structure parsing, semantic chunking, metadata tagging, embedding vectorization, and Milvus retrieval, enabling professional Q&A with source tracing.
4. Improved Q&A accuracy and trustworthiness through Prompt constraints, citation checks, risk rules, and refusal when evidence is insufficient; introduced a Q&A evaluation mechanism and stored evaluation results and user feedback as a basis for later review and optimization.
5. Built hybrid short-term memory with Redis to store recent conversations, session summaries, and structured key information, supporting follow-up questions, context inheritance, and user corrections in knowledge Q&A.
6. Used Human-in-the-loop for missing configuration parameters, conflict confirmation, and risk approval; wrapped Altiplano platform operations via Tool Calling and combined them with NETCONF for configuration push, status queries, parameter validation, and result verification, completing end-to-end configuration with minimal interaction.



### Telecommunications Equipment Management System

**Frontend Engineer｜August 2025—Present**

**Overview**

A system for centralized management and operations of telecommunications equipment, covering device status monitoring, topology management, configuration updates, and alarm handling. It includes a legacy AngularJS version and a new React version.

**Tech Stack**

React｜Valtio｜Webpack｜npm｜AngularJS

**Highlights**

1. Set up and rolled out ESLint + Prettier in the React project, improving code quality and team collaboration.
2. Built device topology views with xyflow, improving data visualization and helping users understand structural relationships more quickly.
3. Led the UI component library upgrade, improving system stability and extensibility without disrupting business features.
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

React｜TypeScript｜Formily｜Zustand｜Lexical｜Vite｜Pnpm｜Prisma

**Highlights**

1. Combined Zustand and React Context for global state management, reducing unnecessary re-renders and improving page responsiveness.
2. Wrote Node.js scripts with Prisma to convert rich-text JSON to HTML, supporting a smooth data migration between the old and new platforms.
3. Adopted Vite to speed up project builds and improve development efficiency.
4. Set up a Pnpm Monorepo to manage B-end, C-end, and shared components in one place, improving overall collaborative development efficiency.



### Materials Procurement and Sales Digital Platform

**Frontend Engineer｜August 2021—September 2022**

**Overview**

An enterprise management system covering company administration, materials procurement and sales, warehousing, and finance. Primary work included PC-side development and ongoing maintenance of purchase contracts, acceptance notes, outbound orders, and settlement review.

**Tech Stack**

React｜TypeScript｜Ant Design｜Formily

**Responsibilities**

1. Developed core modules such as purchase contracts with React and React Router, shipped on schedule, and participated in full testing.
2. Used Formily to build complex forms, handling multi-field linkage and dynamic validation, and reducing data-entry errors.
3. Integrated a WebOffice component for online preview of Word, PDF, Excel, and other office files.
4. Adjusted CI/CD scripts and worked with a Jenkins upgrade to improve automated deployment.



### Energy Equipment Visualization Reports

**March 2020—April 2020**

**Overview**

A large-screen visual data report built with FineReport (FanRuan BI).

**Tech Stack**

Navicat｜MySQL｜FineReport

**Responsibilities**

1. Filtered and aggregated energy-equipment operation data, then built reports with BI tools.
2. Added appropriate indexes to data tables to optimize MySQL query performance and speed up report rendering.
3. Used MySQL stored functions to improve SQL reuse and readability, significantly reducing later maintenance cost.



### Raw Coal Procurement Management Platform

**Python｜July 2019—August 2020**

**Overview**

An enterprise business system built with Django, digitizing coal procurement, sales, and quality-inspection processes and supporting complex business requirements.

**Tech Stack**

Python｜Django｜ExtJS｜MySQL

**Responsibilities**

1. Quickly learned Django and mapped the project structure to support later development.
2. Independently developed chemical-product procurement, raw-coal procurement, and related modules covering procurement, lab testing, and settlement.
3. Worked closely with QA to ship features on schedule without major defects.
4. Followed up on production issues, learned warehouse-management workflows, and handled day-to-day maintenance of UI and data issues to keep the system stable.
5. Iterated existing features based on business feedback.



### Logistics Business Management Mini Program

**Frontend Engineer｜August 2020—July 2021**

**Overview**

A mini program for group administrative staff, covering production inspection plans, vehicle operations, internal exams, performance reviews, and cafeteria facility management.

**Tech Stack**

React｜Taro｜TypeScript

**Responsibilities**

1. Quickly learned React, Taro, and TypeScript, and developed mini-program modules for vehicle management, card issuance, and labor-protection registration.
2. Helped build form and display base components, improving reuse and simplifying component logic.
3. Used Yarn to manage npm packages, significantly improving build speed and developer experience.

