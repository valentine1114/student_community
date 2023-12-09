**StudentHUB: AI-Assisted Community Web Application**
Welcome to the GitHub repository of StudentHUB, a groundbreaking AI-Assisted Community Web Application, engineered with a combination of SpringBoot and Vue. This application represents t an integration of advanced technologies and innovative solutions to enhance user experience and application performance.

**Project Overview**
StudentHUB is an interactive platform designed to facilitate an engaging community experience for students. At the heart of this application is an AI-powered chatbot, built on a large language model (LLM), capable of providing real-time, contextually relevant responses to user posts. This feature significantly enhances user interaction and engagement within the community.

**Key Features**

*AI Chatbot Module*
Engineered with LLM: Leveraging the capabilities of large language models for intelligent, content-driven responses in real-time.

*Security and Permissions*
Interceptor Interceptors: Implemented for robust permissions management, ensuring secure user access and operation within the application.
Sensitive Word Filtering: Integrated a prefix tree for efficient and effective filtering of sensitive words, maintaining a respectful and safe community environment.

*Performance Enhancements*

Multi-threaded PDF Report Generation: Developed to generate reports from database queries, achieving a 50% reduction in processing time.
Kafka Integration: Utilized for real-time alerts, contributing to enhanced user responsiveness.
Caffeine+Redis Caching: Incorporated to boost site throughput by 20 times, ensuring faster load times and smoother user experience.
Optimized SQL Queries: Improved using Composite Indexes and mysqlslap for stress testing, reducing average query time from 0.98s to 0.23s under 500 concurrent users.

*Data Management*
High-Capacity Data Services with Druid: Capable of supporting up to 10,000 queries per second (QPS) under peak load conditions of 1 hour.

**Technologies Used**
Backend: SpringBoot
Frontend: Vue
Database: MySQL, Druid
Caching: Caffeine, Redis
Messaging: Kafka
Testing and Optimization: JMeter, mysqlslap



