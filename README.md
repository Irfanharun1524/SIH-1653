# Smart India Hackathon Workshop
# Date:14/03/2025
## Register Number:212224040122
## Name: IRFAN H
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

1. Objective
The goal is to develop a web-based application that simulates the recruitment and interview process for the DRDO’s Recruitment and Assessment Centre (RAC). This system should simulate interviews with the objective of:

Ensuring an unbiased and objective interviewing process.
Providing a real-life boardroom experience.
Scoring both the interviewer's question relevance and the candidate's response relevance.
Generating an overall score for the candidate based on subject knowledge and suitability for the advertised post.

2. High-Level Features
Boardroom-like Simulation: Create a platform where both interviewers and candidates can interact as though they are in a real-life interview, with video/audio chat options and screen sharing.

Ice-Breaking to In-Depth Questions: Implement question categories that start with basic ice-breaking questions and move to more in-depth, technical questions based on the candidate's expertise and the level of the position.

Real-Time Scoring Mechanism: Develop a system that evaluates both:

The relevance of the questions posed by the interviewer.
The relevance of the candidate's response to the question asked.
Scoring System: The system should generate a score for both the interviewer and the candidate based on the relevancy of questions and responses.

Analytics and Reporting: The system should generate a report summarizing the overall interview performance of the candidate, along with the final suitability score for the position.
## Proposed Solution / Architecture Diagram

![image](https://github.com/user-attachments/assets/ee6bcea7-bbd6-46fe-a7ed-09ee5d129c89)

## Use Cases

Use Case 1: Interview Setup

Actors: Interviewer, Candidate
Description: Interviewer schedules an interview. The system suggests an ice-breaking question based on the job role.
Steps:
Interviewer creates an interview session.
Candidate receives a notification.
Candidate and interviewer join the video session.
Use Case 2: Real-Time Interview Process

Actors: Interviewer, Candidate
Description: The system assists in posing relevant questions based on the candidate's profile, expertise, and job role.
Steps:
Interviewer asks questions, which are suggested by the system based on the job role and candidate expertise.
The candidate answers questions.
The system scores the relevance of the responses.
Use Case 3: Scoring and Feedback

Actors: Interviewer, Candidate
Description: Scoring system evaluates both the relevance of questions and candidate answers.
Steps:
Interviewer rates the quality and relevance of the candidate's answers.
System evaluates the relevance of the questions posed by the interviewer.
The system calculates a final score for the candidate based on the overall assessment.
Use Case 4: Analytics and Reporting

Actors: Administrator
Description: Generate post-interview reports for assessing the candidate’s suitability.
Steps:
Admin reviews candidate scores and feedback.
Generate a suitability report based on the interview scores.

## Technology Stack

1. Frontend: React.j
2. Backend: Node.js, Express.js
3. Database: MongoDB
4. Speech-to-Text Processing: Google Speech API
5. AI/ML Model for Grading: TensorFlow
6. Authentication & Security: OAuth
7. Cloud Hosting: AWS

## Dependencies
1. AI Model Training Data: Previous interview records
2. Secure Storage System: Encryption for recordings & transcripts
3. Speech Processing Module: Integration with NLP services
4. Scoring Algorithm: Machine learning model for question-response analysis
