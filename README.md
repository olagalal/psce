# PSCE: Problem Solving Contest Environment

A comprehensive system for hosting and managing programming contests, developed as a graduation project.

## 🚀 Project Overview

**PSCE** is a dynamic distributed real-time system designed to manage and control programming contests in a variety of computing environments. It includes support for a variety of programming languages. The system is designed to allow teams to use any language development tool which can be invoked from a command line and generates an executable file. 

It automatically timestamps and archives submitted code. PSCE supports two types of judging. The first type is automated (or computer) judging and second type are manual (or human) judging. These two types used independently or in conjunction with each other. 

It allows students (contestants) to submit programs over the same network to contest judges. The judges can recompile the submitted program, execute it, view the source code and/or execution results, and send a response back to the team. The judge also can retrieve and re-execute archived runs. 

It also provides a mechanism for students to submit clarification requests and queries to the judge, and for the judge to reply to queries and to issue broadcast to students. It can also detect plagiarism and exclude students who are cheating.

## 🧠 System Architecture

The project consists of three main components:

### 1. PSCEClient
A JavaFX-based desktop application for contest participants that allows:
- Secure login to the contest environment
- Viewing and selecting programming problems
- Submitting solutions to problems
- Requesting clarifications from judges
- Receiving feedback and clarification responses

### 2. PSCEServer
The server-side component that handles:
- User registration and authentication
- Problem management
- Submission processing and evaluation
- Code compilation and testing
- Clarification management
- Results tracking and scoring

### 3. ContestV2
A web-based interface providing:
- Contest management dashboard for administrators
- Scoreboard and standings visualization
- Additional interfaces for judges and administrators

## 🗂 Project Hierarchy

```
Project Root
│
├── EDDX/                     # System design diagrams
├── src/                      # Source code
│   ├── PSCEClient/           # Client application
│   │   └── src/              # Client source code
│   │       └── dsproject/    # Client implementation files
│   │
│   ├── PSCEServer/           # Server application
│   │   ├── src/              # Server source code
│   │   ├── Codes/            # Submitted code storage
│   │   ├── Input/            # Problem input files
│   │   ├── Output/           # Expected output files
│   │   └── Answers/          # Clarification answers
│   │
│   └── contestv2/            # Web interface
│       ├── src/              # Web application source
│       └── web/              # Frontend resources
│
├── Software Documentation.pdf # Comprehensive documentation
└── README.md                  # This file
```

## ✨ Features

- **Secure Authentication**: Role-based access control for participants, judges, and administrators
- **Problem Management**: Tools for creating, editing, and managing programming problems
- **Automated Evaluation**: Automatic compilation, execution, and testing of submitted code
- **Clarification System**: Communication channel between contestants and judges
- **Real-time Scoreboard**: Live updates on contest standings and results
- **Multi-language Support**: Ability to submit solutions in various programming languages
- **Scalable Architecture**: Designed to handle multiple concurrent users
- **Plagiarism Detection**: Tools to identify potentially plagiarized code
- **Run Archive**: History of all submitted code with timestamps

## 🛠️ Technologies Used

- **Backend**: Java
- **Client UI**: JavaFX
- **Web Interface**: JSP, HTML, CSS, JavaScript
- **Database**: Relational database for storing problems, submissions, and user data
- **Network Communication**: Socket programming for client-server communication

## 📝 Installation and Setup

1. Clone the repository
2. Configure the server paths in `PC2Server.java`
3. Set up the required database
4. Compile and run the server application
5. Compile and distribute the client application to contestants

## 💻 System Requirements

- **Server**: Java Runtime Environment 8 or higher
- **Client**: Java Runtime Environment 8 or higher
- **Web Interface**: Modern web browser with JavaScript enabled
- **Network**: Stable network connection between clients and server

## 🧑‍🤝‍🧑 Team Members

**Development Team:**
- Ola Galal
- Amr Hassan
- Ahmed Daoush

**University:**
- Menoufia University
- Faculty of Computers and Information
- Computer Science Department
- July 2019

## 📄 Documentation

Comprehensive documentation including:
- Software Documentation (available in PDF and DOCX formats)
- System design diagrams (ERD, DFD, Use Case diagrams)
- Sequence diagrams
- Architecture specifications

## 📜 License

All rights reserved. This project is property of the development team and their academic institution.


© 2019 PSCE Development Team 
