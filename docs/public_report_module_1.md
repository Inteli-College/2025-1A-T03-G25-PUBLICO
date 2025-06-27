# Public Project Report - Module 1

**Title of the Project:**  
*Use of Artificial Intelligence in OKR Management: Building an Integrated Platform for Goal Setting Based on Market Analysis*

**Authors:**  
Daniel Eduardo da Silva Cunha

**Supervisor:**  
Prof. Ovidio Lopes

**Course/Institution:**  
Software Engineering, Inteli – Instituto de Tecnologia e Liderança

**Date:**  
11/04/2025

---

## 1. Introduction

The project aims to develop an intelligent platform for the management of OKRs (Objectives and Key Results), integrating Artificial Intelligence to support strategic decision-making. The core motivation lies in the growing need for companies to define and monitor goals that are both adaptable and aligned with internal performance indicators and external market movements. By combining internal datasets and market trend analysis, the solution seeks to enhance how organizations formulate, track, and refine their objectives.

This platform is being developed within the context of a beverage company, aiming to address the specific strategic and operational challenges of the industry, such as aligning sales targets with seasonal trends, optimizing distribution efficiency, and adapting goals based on market consumption data.

The general objective of the study is to deliver a system that leverages AI to suggest customized OKRs, monitor their progress, and provide predictive insights. Specifically, the platform is designed to support automated goal recommendations, enable real-time tracking through intuitive dashboards, integrate with both internal and external data sources, and allow secure multi-role access.

---

## 2. Alignment with Proposed Schedule

In terms of schedule alignment, the project has progressed partially according to the initial timeline. While research and development began as planned in early February 2025, and early phases such as stakeholder engagement, requirement gathering, and backend development were initiated on time, some adaptations were made to optimize the workflow. Initially, the frontend development was planned for the second quarter of the year, but part of it was brought forward to the first quarter in order to deliver a complete initial project flow and demonstrate a functional proof of concept (POC).

As a result, the complexity of the backend planned for this phase was reduced to allocate time for frontend development and ensure the feasibility of delivering the POC within the available timeframe. Despite these adjustments, the project maintained a consistent development cadence and ensured overall progress remained aligned with the broader project goals.

---

## 3. Evolution of the Project

Several important stages were completed to build a working platform that uses AI to support OKR management. The project started with the definition of the main needs and use cases, such as creating objectives, linking key results, uploading data, and generating suggestions. This helped shape the platform to meet the demands of professionals like project managers and team leaders.

The backend was developed using NestJS and Prisma, with a PostgreSQL database to store OKR data, user information, and AI suggestions. A REST API was implemented to handle operations such as creating, updating, and deleting objectives and results.

In parallel, the frontend was created using React, Vite, TypeScript, and Tailwind CSS. The interface allows users to register OKRs, upload files, and view AI-generated suggestions through a responsive and accessible layout.

To support data import, a CSV upload feature was added. Uploaded files are stored in an AWS S3 bucket and later processed by the backend, enabling the ingestion of large sets of performance data, such as sales figures and goal-tracking records.

One of the key advancements in the project was the integration of the OpenAI API. The platform sends processed performance data to the AI model, which then returns suggestions for improving objectives and key results. These insights help identify trends, missed targets, or new opportunities based on the analyzed patterns.

---

## 4. Obstacles and Challenges

Despite steady progress, some key challenges were encountered during development. The most significant was the restriction on using real company data, which required the creation of synthetic datasets for validation and limited the training accuracy of AI models. Furthermore, integration with external APIs proved more time-consuming than expected due to limited documentation and unstable endpoints.

To address these challenges, several mitigation strategies were applied. A realistic dataset generator was implemented to simulate enterprise data patterns. Prompt engineering was adapted so that AI models could provide useful results without relying on specific internal data. Integration tasks were divided into smaller deliverables, and feedback from test cases was incorporated into ongoing iterations.

---

## 5. Future Developments

In the next phase of the project, the main focus will be on improving the platform's user interface and enhancing backend reliability. The upcoming trimester will prioritize a design refinement of the frontend, aiming to improve UI/UX consistency, responsiveness across devices, and overall visual quality. The goal is to deliver a more intuitive and professional-looking interface.

At the same time, improvements will be made to backend validations, especially related to CSV file uploads. Stricter checks will be implemented to validate file types, data structure, and formatting before processing, reducing the risk of errors and improving user feedback when incorrect files are submitted.

In addition to these priorities, further enhancements such as integrating authentication and user roles, collecting user feedback on AI suggestions, and preparing the platform for deployment with performance and security optimizations are also planned. These steps will help transition the platform from a working prototype to a polished, reliable solution ready for use in real organizational environments.

---

## 6. Conclusion and Final Reflections

One of the key foundations for the progress of the project, was the initial requirements elicitation phase, which helped align the solution with real user needs and guided decision-making throughout development.

More than just a technical implementation, the project aimed to bring intelligence and clarity to how organizations define and monitor their goals. The integration of AI to generate recommendations added value by offering proactive support, helping to improve improve objectives based on actual performance data.

The project has strong potential for future evolution. With upcoming improvements in design, validation, and AI interaction, the platform is positioned to become a valuable tool for organizations seeking more dynamic, data-driven, and user-friendly goal management processes.


