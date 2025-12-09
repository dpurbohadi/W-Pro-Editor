# W-Pro-Editor

**Intelligent Tutoring System for Web Programming**

**Overview**

This project presents an Intelligent Tutoring System that combines a custom SCORM based editor, cloud based artificial intelligence tools, and teacher guided prompts to support adaptive learning in introductory programming. The system delivers interactive learning modules through a Learning Management System and is designed to enhance student engagement and conceptual understanding.

**Key Features**

- A SCORM based editor that includes an embedded coding environment suitable for web programming courses.
- Structured practice tasks and real time feedback for learners.
- A Node.js middleware that connects SCORM modules with artificial intelligence services for explanations, hints, and short assessments.
- Support for teacher guided prompting through CourseLab packaging so instructors can embed instructions that shape adaptive responses.
- Automatic recording of learner activity through the Learning Management System.

**System Architecture**

- The system consists of three main components.
- The custom SCORM editor manages instructional content and provides the interactive coding space.
- The Node.js middleware handles communication with artificial intelligence services and maintains a stable and secure connection.
- The Learning Management System delivers the modules, stores learner activity, and presents progress information for instructors.

**Purpose**

The system was created to address common challenges in programming education. Students often require timely and personalised guidance, while instructors need accurate and automatic records to monitor learning progress. This project provides technology that supports both needs within a unified SCORM based environment.

**How to Use**

- Prepare learning materials with the SCORM editor (CourseLab 3.x).
- Add prompts in CourseLab to guide the behaviour of the artificial intelligence component.
- Host the middleware on a server that can communicate with the Learning Management System.
- Upload the SCORM package to the Learning Management System and assign it to students.
- Monitor student activity through the log data captured by the system.
