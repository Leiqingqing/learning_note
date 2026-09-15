# Qingqing Lei

**Target Role: Frontend Engineer**

- Gender: Female
- Phone: 18815619962
- Email: 480293335@qq.com
- Experience: 7 years

## Education

### Huaibei Normal University

- Degree: Bachelor's
- Major: Network Engineering
- Period: 2015—2019

## Work Experience

### Nokia Shanghai Bell Co., Ltd.

**Frontend Engineer｜August 2025—Present**

- Own core business development for a telecommunications management system.
- Drive coding standards and architecture improvements.
- Abstract reusable business components to speed up page development.
- Upgrade the UI component library.
- Maintain and develop a legacy AngularJS project, including an AngularJS Material upgrade.
- Build business Agents with AI, using Prompt Engineering and Skills to define workflows.

### Shanghai Jinyi E-Commerce Co., Ltd.

**Frontend Engineer｜September 2020—March 2025**

- Developed Python services and UI improvements for coal procurement, sales, and quality-inspection flows in an enterprise procurement system.
- Maintained production modules and delivered ongoing iterations.
- Participated in requirements scoping and developed PC and mini-program clients for multiple business systems from specification documents.
- Built visual reports with BI tools.

### Shanghai Jinyi E-Commerce Co., Ltd.

**Python Developer｜July 2019—August 2020**

## Skills

1. Solid Python fundamentals; familiar with FastAPI, ORM frameworks, routing, middleware, async programming, long-lived connections, and exception handling.
2. Familiar with Next.js, Hono, Zod, and Drizzle ORM; experienced in full-stack development and Monorepo engineering.
3. Proficient with LangChain and LangGraph; experienced in Prompt Engineering, Function Calling, and the MCP protocol.
4. Familiar with agent development, including task decomposition, Skills, multi-agent collaboration, and short-/long-term memory.
5. Hands-on experience building RAG systems from scratch: multi-source heterogeneous data loading, text chunking, embeddings, and retrieval optimization.
6. Regularly use GitHub Copilot and other generative AI tools for requirement breakdown, implementation, unit tests, and code review.
7. Strong React and ecosystem skills, with a working understanding of framework internals and extensive experience extracting reusable components and Hooks.
8. Familiar with Webpack, Vite, and frontend performance optimization; able to design, develop, and troubleshoot large frontend projects end to end.
9. Familiar with MySQL, SQLite, and Vectorize; able to write complex SQL and build data visualization applications with BI dashboards.
10. Proficient with Git and Git workflows, with experience collaborating across large-scale, multi-client business systems.
11. Quick to adapt across tech stacks; quality-focused and able to take on critical work in complex projects and deliver lasting value.
12. Strong English reading and writing skills; comfortable working in an English-speaking development environment.

## Skills (Concise)

Five years of frontend development and one year of backend development, with hands-on experience in both large language models and data-intensive systems. Proficient with LangChain and LangGraph; experienced in Prompt Engineering, Function Calling, and the MCP protocol. Familiar with agent development, including task decomposition, Skills, multi-agent collaboration, and short-/long-term memory. Hands-on experience building RAG systems from scratch, covering multi-source heterogeneous data loading, text chunking, embeddings, and retrieval optimization. Familiar with MySQL, SQLite, and Vectorize. Solid frontend fundamentals in JavaScript, TypeScript, React, Next.js, and related ecosystems, with experience in large enterprise project design, component abstraction, cross-platform development, performance optimization, and complex troubleshooting. Regularly use GitHub Copilot and other generative AI tools for requirement breakdown, implementation, unit tests, and code review.

## Projects

### Access Network Platform Intelligent Assistant

**Overview**

An LLM-powered assistant for the Altiplano access network platform. It hides complex configuration dependencies behind natural-language interaction, so end-to-end configuration can be completed with minimal user effort. The project also builds telecom-industry and enterprise knowledge bases for professional, trustworthy, and source-traceable Q&A, and integrates Playbook tools to support local deployment, upgrades, progress tracking, result verification, and failure recovery.

The system uses a configuration dependency graph and controlled workflows as its execution core, an LLM as the natural-language interface, and a telecom knowledge base as the professional foundation—forming a platform engineering tool that is deterministic, domain-aware, auditable, and recoverable.

**Tech Stack**

Next.js｜React｜TypeScript｜Tailwind CSS｜Hono｜Zod｜Turborepo｜Pnpm｜Cloudflare Workers

**Responsibilities**

1. Unified model and tool invocation with LangChain, and orchestrated Altiplano version confirmation, deployment and upgrades, progress tracking, result verification, failure recovery, and human fallback with LangGraph, reducing the operational complexity of platform deployment and upgrades.
2. Built a multi-agent architecture in which a main Agent calls an Intent Agent for intent recognition and routes tasks to a Knowledge Q&A Agent, a Platform Deployment Agent, or an End-to-End Configuration Agent.
3. Built telecom-industry and enterprise knowledge bases on a RAG architecture: HTML-to-Markdown conversion, structure parsing, semantic chunking, metadata tagging, embeddings, and Milvus retrieval, enabling professional Q&A with source tracing.
4. Improved answer accuracy and trustworthiness through prompt constraints, citation checks, risk rules, and refusal when evidence is insufficient; added Q&A evaluation and stored evaluation results and user feedback for later review and optimization.
5. Built hybrid short-term memory with Redis to store recent conversations, session summaries, and structured key information, using a 24-hour sliding expiration to support follow-up questions, context inheritance, and user corrections in knowledge Q&A.
6. Used Human-in-the-loop for missing configuration parameters, conflict confirmation, and risk approval; wrapped Altiplano operations via Tool Calling and combined them with NETCONF for configuration push, status queries, parameter validation, and result verification, completing end-to-end configuration with minimal interaction.

### Telecommunications Equipment Management System

**Frontend Engineer｜August 2025—December 2025**

**Overview**

A system for centralized management and operations of telecommunications equipment, covering device status monitoring, topology management, configuration updates, and alarm handling. It includes a legacy AngularJS version and a new React version.

**Tech Stack**

React｜Valtio｜Webpack｜npm｜AngularJS

**Responsibilities**

1. Set up and rolled out ESLint + Prettier in the React project to improve code quality and team collaboration.
2. Built device topology views with XFlow, improving visualization and helping users understand device relationships more quickly.
3. Led the UI component library upgrade, improving stability and extensibility without disrupting business features.
4. Quickly learned the legacy AngularJS development model and independently delivered new requirements, shortening delivery cycles.
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

**Responsibilities**

1. Combined Zustand and React Context for global state management, reducing unnecessary re-renders and improving page responsiveness.
2. Built and maintained a customized rich-text component on Lexical to meet business needs.
3. Wrote Node.js scripts with Prisma to convert rich-text JSON to HTML, supporting a smooth migration between old and new platforms.
4. Adopted Vite to speed up builds and improve development efficiency.
5. Set up a Pnpm Monorepo to manage B-end, C-end, and shared components in one place, improving cross-team development efficiency.

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
