# FixIt AI - Intelligent Maintenance and Issue Resolution Platform

**FixIt AI** is an intelligent maintenance and issue-resolution system designed to automate the reporting, tracking, and resolution of technical or infrastructure problems. The platform leverages AI-driven workflows and a smart chatbot to streamline maintenance operations, reduce manual workload, and accelerate problem resolution.

**Demo Video:**
[Watch on YouTube](https://youtu.be/HTO3lFguL3A?si=v6fjhemwLrI0Rdrs)

---

## Overview

FixIt AI integrates frontend, backend, and AI automation components into a unified system. It features the FixIt AI Chatbot for user interaction, enabling users to report issues, get troubleshooting advice, and monitor repair progress in real time.

---

## System Components

### Frontend

* Built using React.js, JavaScript, HTML, and CSS.
* Provides a responsive and intuitive user interface.
* Enables users to:

  * Report technical issues
  * View issue progress
  * Communicate with technicians through the integrated chatbot

### Backend

* Powered by n8n, a Node.js-based workflow automation platform.
* Handles:

  * Issue validation and routing
  * Workflow execution
  * Notification and technician assignment
* Eliminates the need for manual backend coding through low-code automation.

### Database

* Uses MySQL for secure data storage and management.
* Stores:

  * User information
  * Issue details and statuses
  * Chatbot logs and interactions
  * Technician assignments

### AI Chatbot

* Acts as the primary interface for user support.
* Assists users by:

  * Logging new issues
  * Suggesting troubleshooting steps
  * Providing real-time updates on issue status

### Notification System

* Uses SMTP (Email) notifications to alert users and technicians of new updates, issue assignments, or status changes.

---

## Key Features

* Automated issue logging and management
* AI-powered workflow automation
* Real-time status tracking
* Centralized data management via MySQL
* Reduced manual intervention and faster resolution times

---

## System Workflow

1. **User Reports Issue** – Through the web form or chatbot.
2. **Data Validation & Routing** – n8n backend validates and routes the issue.
3. **Technician Assignment** – Appropriate technician is notified automatically.
4. **Issue Resolution** – Technician investigates and resolves the issue.
5. **User Updates** – Chatbot provides real-time progress and completion alerts.
6. **Issue Closure** – Status is marked resolved, and the user is notified.

---

## Technologies Used

| Component     | Technology                                  |
| ------------- | ------------------------------------------- |
| Frontend      | React.js, JavaScript, HTML, CSS             |
| Backend       | n8n (Node.js-based automation)              |
| Database      | MySQL                                       |
| Chatbot       | Dialogflow / Rasa (or other NLP frameworks) |
| Notifications | SMTP (Email)                                |

---

## Future Enhancements

* Integration with IoT sensors for automatic fault detection
* Advanced analytics dashboard for performance insights
* Mobile application for technicians and users
* Multi-language chatbot support

---

## License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute it for educational or commercial purposes with proper attribution.

---

## Demo

Watch the full system demo on YouTube:
[https://youtu.be/HTO3lFguL3A?si=v6fjhemwLrI0Rdrs](https://youtu.be/HTO3lFguL3A?si=v6fjhemwLrI0Rdrs)
