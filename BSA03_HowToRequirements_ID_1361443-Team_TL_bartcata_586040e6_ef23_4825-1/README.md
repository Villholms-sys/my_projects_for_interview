# Ways to Elicite Requirements

Summary:
In this project, you will learn the ways to elicit requirements and which of them to use in which cases. By applying different methods, you will elicit business requirements, build a functional role model, and learn how to document requirements.

💡 [Tap here](https://new.oprosso.net/p/4cb31ec3f47a4596bc758ea1861fb624) **to leave your feedback on the project**. It's anonymous and will help our team make your educational experience better. We recommend completing the survey immediately after the project.

## Contents

1. [Chapter I](#chapter-i) \
   1.1. [Preamble](#11)
2. [Chapter II](#chapter-ii) \
   2.1. [General Rules](#21)
3. [Chapter III](#chapter-iii) \
   3.1. [Ways to Elicite Requirements](#31) \
   3.2. [Interview, Survey, Role Play](#32) \
   3.3. [Brainstorming, Workshop](#33) \
   3.4. [How to Describe Business Requirements](#34) \
   3.5. [Project Roles and Their Functions](#35)
4. [Chapter IV](#chapter-iv) \
   4.1. [Task 1. Haircut Appointment](#41) \
   4.2. [Task 2. Delivery of Orders](#42)
5. [Chapter V](#chapter-v) \
   5.1. [Exercise 00 — Role-playing Game](#51) \
   5.2. [Exercise 01 — Brainstorming](#52) \
   5.3. [Exercise 02 — Workshop](#53) \
   5.4. [Exercise 03 — Vision](#54)

## Instructions 

How to learn at “School 21”:

- Here, you’ll find a unique learning experience with a lot of freedom. You’re given a task and left to find your own way to solve it, using whatever resources work best for you — whether that’s the Internet or AI tools like GigaChat. Just be mindful of information quality: verify, think critically, analyze, and compare.
- Peer-to-peer (P2P) learning is the exchange of knowledge and experience with peers, where everyone acts as both mentor and student. This approach allows you to gain a deeper understanding of the material by learning from one another.
- Feel free to ask for help: around you are peers who are also navigating this path for the first time. Share your own experience and ideas with others.  Join Rocket.Chat to stay updated with the latest community announcements. 
- Your learning is meaningless if you just copy someone else’s solutions. When receiving help from others, always make sure you fully understand the “why”, “how”, and “purpose” behind the solution. Don’t be afraid to make mistakes. 
- Does the task seem impossible? Take a break, get some fresh air and clear your mind — this has helped many people. Maybe after that, the solution will come to you naturally.
- The learning process is just as important as the result. It’s not just about completing the task — it’s about understanding HOW to solve it.

## Chapter I <div id="chapter-i"></div>

![](misc/images/Illustration_03.jpg)

### Preamble <div id="11"></div>

Nowhere are the interests of all project stakeholders more closely tied to the success of a project than at the requirements elicitation stage. Misunderstood, inconsistent, or incomplete requirements elicitation results in further significant changes to what has already been developed.  Here are the reasons why increased attention should be paid to requirements elicitation:

- The customer knows what they want, but can't put it into words;
- The customer thinks he knows how to solve the problem (he brings the solution);
- The contractor thinks he knows better than the customer.

In this project, you will learn about requirements elicitation techniques and apply some of them to solve your tasks. 

This is a group project. When performing the project tasks, you should first work through all the tasks and then perform them in an integrated manner. The results of the tasks in the form of Business Requirements and Functional Role Model should be placed in a single document: BRD (Business Requirements Document).

### Literature

1. Wiegers, K. (2013). Software Requirements (3rd ed.). Microsoft Press. ISBN 978-0735679665.
2. International Institute of Business Analysis. (2015). A guide to the business analysis body of knowledge (BABOK Guide) (Version 3). Toronto, ON: IIBA.
3. Dean Leffingwell, Don Widrig "Managing Software Requirements", Part 1, Chapter 4.
4. Kaner S., Lind L., Toldi K. "Facilitator's Guide: to Participatory Decision-Making".
5. Ilya Kornipaev "Requirements for Software: Recommendations on Gathering and Documentation".

## Chapter II <div id="chapter-ii"></div>

### General Rules <div id="21"></div>

Before starting, clone the project from GitLab into a repository with the same name.

1. Along the way, you may feel a sense of uncertainty and a severe lack of information: that's OK. Remember, the information in the repository and on Google is always with you. So are your peers and Rocket.Chat. Communicate. Search. Use common sense. Don't be afraid to make mistakes.
2. Pay attention to sources of information. Check. Think. Analyse. Compare. 
3. Look at the text of each assignment. Read it several times. 
4. Read the examples carefully. There may be something in them that is not explicitly stated in the task itself.
5. You may find inconsistencies where something new in the terms of the task or examples conflicts with something you already know. If you come across such an inconsistency, try to work it out. If not, write it down as an open question and find out as you work. Do not leave open questions unanswered. 
6. If a task seems confusing or impossible, it only seems that way. Try to break it down. It is likely that some parts will become clear. 
7. There will be several tasks. Those marked with an asterisk (\*) are for the more meticulous students. These tasks are more difficult and are not compulsory. But doing them will give you extra experience and knowledge.
8. Don't try to fool the system or the people around you. You will fool yourself first.
9. Got a question? Ask your neighbour to the right. If that doesn't help, ask your neighbour on the left.
10. When you use help, you should always understand why and how. Otherwise the help is useless.
11. Always push only to the _develop_ branch! The master branch will be ignored. Work in the _src_ directory.
12. There should be no files in your directory other than those specified in the tasks.

## Chapter III <div id="chapter-iii"></div>

### 1. Ways to Elicite Requirements <div id="31"></div>

Requirements elicitation is a collaborative analytical process with stakeholders. 

Requirements should be discovered:

- discovered — you will not always be told that they exist: for example, legal requirements for mandatory breaks in employee schedules;
- gathered — fixed, written down so you don't lose them; 
- fixed — for example, a constraint on the master's schedule: the client appointment must include the master's lunch break.

Requirements elicitation is something you need to prepare for: 

- Gather information about the stakeholders and their concerns (if possible).
- Familiarize yourself with the domain and terminology.
- Examine what is known about the task and the problems to be solved.
- Understand who is best to engage and with what methods.

Once the requirements have been identified, they need to be agreed with the stakeholders.

Requirements elicitation is probably the most difficult part of the analyst's job. After the first iteration, it usually turns out that something is unclear and the elicitation work needs to continue. If you pass requirements that contain something unclear or ambiguous to the developers, you will have to rework them later. Therefore, it is perfectly normal for elicitation to be performed in an iterative, cyclical manner.

For a more complete understanding of requirements elicitation, it is recommended that you read Chapter 7 by K. Wiegers (see Literature List).

**Ways to Identify Requirements:**

1. Documentation analysis; 
2. System Context Analysis;
3. Study of such systems;
4. Glossary;
5. Interview;
6. Focus Groups;
7. Survey;
8. Workshop;
9. Brainstorming;
10. Prototyping;
11. Business Process Modeling.

In this project, you'll also try using generative models (YandexGPT, GigaChat) as a "virtual interlocutor" to practice interviews and test your questions. 
Note that the AI ​​responses don't reflect real business constraints, but they will help you: 
- practice interview structure; 
- notice which questions are phrased too broadly; 
- practice asking clarifying questions.


### 2. Interview, Survey, Role Play <div id="32"></div>

One of the most common methods of requirements elicitation is the interview. In addition, a survey (questionnaire) is often used. When working on the project in P2P conditions, the method of role-playing is used.

**Interview** is a technique to identify needs, pains, requirements through direct communication, asking appropriate questions and documenting answers.

**Survey/Questionnaire** is a technique for gathering requirements in a systematic way in a short time. A group of respondents is asked the same questions (open or closed) and the answers are analyzed.

**Role-playing game** is a technique that encourages participants to work together to achieve the goal of the game, such as understanding problems and opportunities and finding a solution.

### 3. Brainstorming, Workshop <div id="33"></div>

**Brainstorming** is an effective way to solve problems when there is no solution or the existing solution is ambiguous. It uses "collective intelligence" and stimulates the creativity of the team. The goal of brainstorming is to generate as many ideas as possible and to find the best solution in different ways. 

**Workshop** is an activity used by a group to achieve a chosen goal and develop agreement on that goal. For example, choosing one of the previously generated solutions.

### 4. How to Describe Business Requirements <div id="34"></div>

A business requirement is a high-level business goal of an organization or system's customers. Business requirements describe the key benefits that a new (or upgraded) system will provide to its customers, users, the organization, and its customers. Business requirements define user requirements and system functionality. When describing the business requirements, you should describe:

1. The problem(s) for which the system is being created or improved. 
2. The environment, conditions, situation in which the system or organization finds itself.
3. Opportunities that will solve problems with our system.
4. Business goals of the system — the main goals for the fulfillment of which the system is built.
5. In addition to  thebusiness goals, can be added:
   1. the tasks that must be performed to achieve the business goals;  
   2. the hierarchy of problems and objectives that realize the main business goal; 
   3. the main functions of the system's key roles.
6. System boundaries. It is usually very difficult to delineate boundaries by business requirements. Often the system boundaries are delineated by one of the things listed in item 5.
7. Criteria, metrics for measuring success after system implementation.

Details about the description of business goals are described in chapter 5 of K. Wiegers's book "Software Requirements". The Business Requirements Document can be called many different names: BRD (Business Requirements Document), Vision, Statement of Work, or even Contract Statement of Work. Usually its title and content is determined by the customer or contractor organization. In this project, you will prepare the main sections of such a document.

### 5. Project Roles and Their Functions <div id="35"></div>

Earlier, in the  BSA 02 project, you identified the roles, their needs, and the actions they perform in the project. But that was your understanding, your hypotheses. In this project, as part of the role play game, you should clarify with the participants playing the roles of the stakeholders to what extent your point of view coincides with the views of the stakeholders. In the brainstorming session, you should discuss, confirm your hypotheses or identify other roles of system users and solutions to stakeholder problems.

## Chapter IV <div id="chapter-iv"></div>

### Task 1. Haircut Appointment <div id="41"></div>

The management of a chain of barbershops decided to implement an online booking system. The main objective is to develop the business by expanding the customer base through the possibility of online registration, as well as to reduce employee labour costs and manual labour by automatically informing customers through communication channels. 

Both registered and unregistered visitors can book an appointment on the website. When making an appointment, they can select the type of service: hairdressing or cosmetology, as well as the service itself, the master and the time from the available intervals. The system should provide automatic sending of reminders to clients through the communication channel chosen by the client (Telegram, WhatsApp, VK, SMS) according to the schedule set by the manager. After receiving a service, the system offers the client to evaluate the service and write suggestions on how to improve the work.

The schedule of masters and the services provided by each master should be entered by the manager, who may be more than one person. This person is also responsible for keeping the schedule up to date and adjusting it if necessary, communicating with customers manually, marking the service, charging and accepting payment, sending the payment data to the accounting department. The manager can also receive reports on completed services and view customer feedback.

Each master has the ability to view the schedule and appointments for their services, as well as customer reviews.

### Задача 2. Delivery of Orders <div id="42"></div>

During the lockdown, many grocery stores and food companies dramatically increased their online sales and the need for quick delivery of small quantities to individual customers increased. 

A group of students got together and decided to start a delivery service. The idea is to quickly receive information about orders, pickup location and time, delivery location, desired delivery dates, and distribute this information to couriers who will pick up the order at the pickup location and deliver it to the delivery location. They decided to develop an online system where orders could be collected and quickly sorted for delivery by couriers.

The first step was to collect orders from stores and caterers in any way possible and have the operator enter them into the system in a consistent format, as well as developing a mobile application for the courier. The courier should be able to view order information, select an order from those available, book it, pick it up at the collection point and deliver it to the customer. The result of the courier's actions should be immediately reflected in the system via a mobile application. The system should also include a dispatcher who controls the couriers and reassigns orders if necessary. Information on received orders should be sent to the accounting department (to another IT system) to calculate delivery charges with order suppliers. Order delivery information should also be sent to the accounting department to calculate payment to couriers. Accrued payment should be transferred to the system and displayed in the courier's personal account. And there should also be an administrator's workstation, where couriers are registered and access rights are assigned to all of them.

When analyzing the task, use YandexGPT and GigaChat as AI assistants: 
- to generate possible work scenarios for couriers, the dispatcher, and the operator;
- to clarify the wording of the startup's problems and business goals; 
- to prepare options for formulating business requirements and ideas for the business model (at the hypothesis level).
Important: decisions on requirements are made by the team; AI results are subject to critical evaluation and cannot be considered final without verification.

## Chapter V <div id="chapter-v"></div>

### Exercise 00 — Role-playing Game <div id="51"></div>

**For task 2:**

1. Assign roles:
   - Choose the facilitator.
   - Select a group of clerks — 2-3 people.
   - Assign the roles from the task description to the participants of the game.
   - Include system developers as a team representative.
2. Prepare for the game:
   Define the goals of the game as immersion in the task and identification:
      - Who are we building the system for? What needs do we want to meet? 
      - What problems are we solving? Whose problems are they?
      - What is the motivation behind the activity?
      - What is the basis of the activity, the business? How does it work? What are the roles (people)? What are the processes?
      - Where do the processes of the system occur? Is it the real/virtual world? Is the command distributed in the system?
      - When? What are the periods, time zones, time constraints? 
      - Prepare questions resulting from the study of the task and determine which role to ask these questions.
3. Play a game.
4. Provide a report on the role-playing game. Include:
   - Role assignment of participants;
   - A brief description of each role about themselves;
   - Role needs and emerging issues in the context of the task;
   - Asked questions and answers from roles. 
5. Place the report in the turn-in file ex00\_<product prefix>\_rolegame.docx.

**Recommendations for role-playing:**

1. Define the goal of the game as immersion in the task.
2. After assigning roles to each participant:
   - Get into character.
   - Explore the needs and abilities of the role.
3. Make up a story, prepare a brief narrative about your role.
4. Be prepared to answer questions from other team members.
5. During the role-play stage, do not use AI tools instead of participants. It is important to gain real experience of communication and conflict of viewpoints.


### Exercise 01 — Brainstorming <div id="52"></div>

**For task 2:**

1. Determine brainstorming goals — identify:
   - Suggestions for formulating business requirements;
   - Suggestions on the roles of system users, their problems as is;
   - Suggestions of users' needs and their possible actions in the system to be;
   - Suggestions for problems that are unclear how to solve in the task.

For example, in task 1: how should the master deal with the schedule?

1. Prepare for brainstorming:
   - Choose a team member to briefly describe the problem.
   - Choose a facilitator (a separate facilitator can be used for each goal).
   - Select a writer to record all ideas.
   - Set a time and place for the brainstorming session, and notify participants. 
2. With a help of brainstorming, collect suggestions for each block from item 1.
3. Prepare a protocol for the brainstorming session. Include:
   Results for each block;
   For each block, specify:
      - facilitator, clerk; 
      - Goals, problems;
      - Suggestions, ideas. 
4. Place the protocol in the turn-in file ex01\_<product prefix>\_brainstorming.docx.
5. *Conduct a mini-interview with an AI stakeholder for task 2 and compare it with the role-play among participants:
    - Formulate a short prompt that sets the role (for example, "owner of a grocery store", "delivery service dispatcher", "courier") and the context of task 2.
    - Ask the AI 5–7 key questions prepared for the brainstorming session and record the answers.
    - Compare the AI stakeholder's answers with the answers obtained in the role-play (Exercise 00):
      note the ideas that matched;
      highlight contradictions;
      record new hypotheses that should be checked with real people.
    - In the brainstorming protocol, include this comparison in a separate subsection "Results of the mini-interview with AI".

**Recommendations for brainstorming:**

Before brainstorming:

1. Read or review materials: task conditions, interview reports, ex00 and ex02 results in BSA 02, important documents or internet resources related to the task.
2. Remember your developments for the task.
3. Place the task materials close to the brainstorming area to pick them up when needed.
4. *If possible, use YandexGPT to generate additional questions and roles, but be sure to check all AI prompts for realism and consistency with the task context.

### Exercise 02 — Workshop <div id="53"></div>

**For task 2:**

1. Define the objectives of the workshop as identifying the following:
   - Business Requirements;
   - Roles of the system and their problems as is;
   - Role needs and their possible actions in the to be system;
   - Solutions to the problems discussed in the brainstorming session;
   - System boundaries in the form of functions performed by roles in the system.
2. Prepare for the workshop:
   - Select a facilitator.
   - Select a team of clerks (2-3 people, for substitutes) who will take turns recording the result.
3. Conduct a workshop.
4. Prepare a report on the workshop. Include:
   - Results for each block;
   - Project, task, facilitator, clerks.
5. Place the report in the turn-in file ex02\_<product prefix>\_workshop.docx.

**Recommendations for the workshop:**

1. The facilitator announces the next question to achieve the objectives of the workshop (item 1).
2. Participants select brainstorm ideas. They discuss them, provide arguments for and against.
3. If opinions differ, use voting or weighted calculation.
4. After obtaining the result, the participants identify the functions to be performed by the user roles in order for the system to fulfill the business requirements (the system to achieve the business goals of the system).
5. Apply material developed in previous projects, including stakeholder directory, onion and context diagrams, etc., to identify solutions. 

### Exercise 03 — Vision <div id="54"></div>

**For task 2:**

1. Create a Vision document, specify the name of the system.
2. Create an Introduction, specify:
   - Who the document is meant for;
   - Goal and field of application;
   - Executor.
3. Describe the source information:
   - List of information sources;
   - List of abbreviations, glossary;
   - List of stakeholders, their roles in the system, brief description.
4. Describe the business requirements (see Section 3. "How to Describe Business Requirements"):
   - Problems for which the system is being created or completed;
   - Preconditions, environment, situation;
   - Possibilities to solve problems with our system;
   - Business goal(s) — the main goals for which the system is being built.
5. Describe the scope of the project:
   - The main roles of the system and their functions in the system.
6. Place the document in the turn-in file ex03\_<product prefix>\_vision.docx.
7. *Conduct a review of the final document using AI tools:
   - request suggestions for improving the document structure;
   - if necessary, rephrase individual paragraphs (for example, business goals and problem statements) more clearly and concisely;
   - request a check of the document for logic and the absence of contradictions.

