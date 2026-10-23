# CS255-System-Analysis

DriverPass System Analysis and Design Portfolio

This repository contains the core software engineering deliverables for the DriverPass platform, showcasing a complete workflow from initial business requirements gathering through technical system design.

Project Summary

The client for this project is DriverPass, a company dedicated to helping student drivers prepare for and pass their official driving exams. They needed a central, cloud-hosted web application to streamline their scheduling and training processes. The system I designed automates administrative tasks by letting students book behind-the-wheel lessons from real-time calendars, integrates self-paced practice tests with instant metric tracking, and provides a unified dashboard where instructors can log student progress notes.

Reflection


Project Successes

I think I did particularly well with building out the UML models, especially the activity and sequence diagrams. I was able to take ambiguous human needs from the client interview and map them out into strict, step-by-step logic loops. Making sure that edge cases—like failed payment processing or a selected time slot becoming unavailable—were cleanly handled in the loops before a developer actually writes code felt like a strong achievement.

Areas for Revision and Improvement

If I could go back and revise one part of my work, I would expand the system constraints and boundaries in the requirements phase. While the core scheduling and test modules are solid, I would look deeper into automated data-retention rules or long-term scaling policies. To improve it, I would research cloud database clustering techniques to explicitly outline how the platform would maintain its 2-second response times if the active user base scaled from hundreds of students to tens of thousands.

Interpreting User Needs

To accurately interpret the client's needs, I systematically broke down the interview transcript into specific actions, sorting them into functional and nonfunctional needs. Considering the user’s needs is the most critical part of software design because code doesn't exist in a vacuum. If a system is mathematically perfect but ignores how a non-technical administrator or a busy student actually navigates a screen, the application fails as a business tool. Designing with the user in mind ensures the final software solves real problems rather than introducing new frustrations.

Approach to Designing Software

My approach to software design focuses heavily on planning and visualization before jumping into writing code. This project taught me that spending time creating accurate use case layouts and structural blueprints saves massive amounts of debugging and restructuring time down the line. In future projects, I plan to continue using techniques like structured requirements matrices, containerization planning (like Docker mapping), and early object-oriented class modeling to analyze and design scalable systems efficiently.

~ Jonathan Brennan
