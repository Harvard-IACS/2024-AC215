---
layout: page
title: Milestone 5
parent: Projects
nav_order: 5
---

# Milestone 5: Final Project Delivery
**Due Date:** December 11th

**Showcase:** December 9th, 9:00–11:00 AM

---
## Overview
The final milestone focuses on three key areas:
1. Production-ready deployment with Kubernetes and Ansible.
2. Project demonstration and documentation.
3. Public communication of results through a live showcase.

---

## Required Deliverables
### 1. Technical Implementation
- **Kubernetes Deployment**:
  - Deploy the application to a Kubernetes cluster.
  - Demonstrate basic scaling by manually increasing and decreasing the  load.
- **Ansible Playbooks for Automated Deployment**:
  - Write Ansible playbooks to automate the provisioning and deployment of your infrastructure and application, including the kubernetes cluster.
- **CI/CD Pipeline Implementation**:
  - Set up a CI/CD pipeline using *GitHub Actions*. The pipeline should:
    - Run unit test across every container.
    - Run integration tests cross the exposed API on every pull request.
    - Deploy updates to the Kubernetes cluster upon merging changes into the main branch.
    - The test coverage must be at least 70% of the lines. Document what functions and modules lack testing. 

- **Machine Learning Workflow**:
  - Demonstrate a production-ready ML workflow, including:
    - Data preprocessing, model training, and evaluation steps integrated into the pipeline.
    - Automated retraining and deployment triggered by new data or updates to the codebase.
    - Validation checks to ensure only models meeting performance thresholds are deployed.


### 2. Documentation
- **GitHub Repository**:
  - Include a well-structured and modular codebase.
  - Provide a comprehensive README file with the following sections:
    - Prerequisites and setup instructions.
    - Deployment instructions.
    - Usage details and examples.
    - Known issues and limitations.
  - Submit main branch for this deliverable.



### 3. Presentation Materials
- **Video Presentation**:
  - Record a **6-minute video** covering the following:
    - Problem statement and the proposed solution.
    - Technical architecture and key components.
    - Live demo of the application in action.
    - Challenges faced and solutions implemented.
  - Submit the video in **MP4 format** with a minimum resolution of 720p.
- **Blog Post (See [Ed for more details](https://edstem.org/us/courses/58478/discussion/5770637))**:
  - Write a **600–800 word Medium blog post** summarizing your project for a general audience. The post should highlight the problem, solution, technical approach, and impact.
  - Include visuals or diagrams where appropriate.
- **Self and Peer Review Forms**:
  - Complete self-assessment and peer evaluation forms to provide feedback on team contributions.



### 4. Showcase (Dec 9th)
- **Event Format**:
  - Each team will have **45 minutes** during the live showcase to present their project.
  - Participants will visit your booth to interact with your application and learn about your implementation.
  - Monitors will be provided to most teams. Additional equipment or materials must be arranged by the team.
- **App Requirements**:
  - The app must be fully functional and hosted on **Google Cloud Platform (GCP)** or **AWS**, accessible via a public URL.
  - Include a **QR code** linking to your application to allow visitors to easily access and explore it.
  - Prepare to explain your problem, solution, technical implementation, and business value to participants.
- **Best of Show Award**:
  A committee will evaluate all projects during the showcase to select the **Best of Show**. Evaluation criteria include:
  - Innovation and impact.
  - Technical complexity and robustness.
  - Clarity of presentation and engagement with participants.


## Submission Instructions
- Submit all deliverables (GitHub repository link, video file, blog post link, and self/peer review forms) via the course submission portal by **11:59 PM, December 11th**.
- No late submissions


## Evaluation Criteria
1. **GitHub (35%)**: Technical Depth, Content, Clarity, Coding Style
2. **Documentation (25%)**: README and technical report are clear, complete, and easy to follow.
3. **Presentation and Showcase (40%)**:
   - Video and blog post effectively communicate the project’s value and technical details.
   - Engagement during the live showcase demonstrates clarity and understanding.