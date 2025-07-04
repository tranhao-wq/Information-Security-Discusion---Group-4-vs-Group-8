![image](https://github.com/user-attachments/assets/8dab4626-9693-41e2-993d-71ac00603c5d)# Information-Security-Discusion-Group-4-vs-Group-8
This project is an interactive, single-page web application designed as an educational tool to demonstrate and explain the concepts behind SQL Injection (SQLi) attacks

----------
# Pics
![image](https://github.com/user-attachments/assets/2e4bb989-82fa-41f0-acdb-a291b14e983e)
![image](https://github.com/user-attachments/assets/a088b463-7a9e-426b-9e8e-f5bef62a2c30)
![image](https://github.com/user-attachments/assets/1f94b542-21b1-4361-9e61-ff36517dd03c)
![image](https://github.com/user-attachments/assets/f5490e9f-c7b5-4ad5-9401-a3a54c12ac8c)
![image](https://github.com/user-attachments/assets/7afc538f-26e1-40cc-bef6-817a2ccfb768)
![image](https://github.com/user-attachments/assets/c722688c-003e-4217-9973-56be0bb8a79b)
![image](https://github.com/user-attachments/assets/57c8cdd0-ffd5-4e5e-9048-e1f01ce72627)
![image](https://github.com/user-attachments/assets/fbbb9b38-171f-4d67-929a-48e6a1c7ef88)
![image](https://github.com/user-attachments/assets/eec20bd7-571d-4bd1-8c10-cb798984c18c)
![image](https://github.com/user-attachments/assets/1a63655c-c102-4c5c-a8ba-2a32fff5147a)
![image](https://github.com/user-attachments/assets/76c655b8-11d7-41b0-8016-d4bb50eddcaf)
![image](https://github.com/user-attachments/assets/439ac50d-61b9-4cb4-ae52-89a39faa8ef8)
![image](https://github.com/user-attachments/assets/07d8d1ca-4557-4a0b-b9ef-2c88f3821930)
![image](https://github.com/user-attachments/assets/c960b455-30e7-43bf-9423-2c588b93c5e3)
![image](https://github.com/user-attachments/assets/2c47de5e-33fa-4818-b3d5-284cdd3c8619)
![image](https://github.com/user-attachments/assets/1c6f338f-b598-40a7-af8d-0b0b8a700b83)
![image](https://github.com/user-attachments/assets/8c528c88-71c8-45e3-9fc9-5a6ad32f8243)
![image](https://github.com/user-attachments/assets/fb601db3-0f98-4318-a157-a639680599c5)
![image](https://github.com/user-attachments/assets/987efb5c-bc37-4528-a497-f5a4178355d0)

# SQL Injection: An Interactive Analysis Lab
## 1. Project Overview
This project is an interactive, single-page web application designed as an educational tool to demonstrate and explain the concepts behind SQL Injection (SQLi) attacks. It provides a deep-dive analysis of various SQLi techniques, visual aids to understand attack vectors, and a comprehensive guide to defense strategies.

The standout feature of this application is the AI Attack Lab, powered by the Google Gemini API. This lab allows users to interactively analyze malicious payloads and generate realistic, industry-specific attack scenarios, transforming a static educational page into a dynamic learning experience.

This project was developed for "Group 8" as a presentation and learning tool for a cybersecurity course.

## 2. Key Features
Interactive AI Attack Lab:

Payload Analyzer: Users can input any SQLi payload, and the Gemini API will provide a detailed breakdown of its purpose, type, mechanism, and the most effective countermeasures.

Attack Scenario Generator: Users can select an industry (e.g., E-commerce, Online Banking), and the Gemini API will generate a plausible, step-by-step SQLi attack scenario, including the attacker's goal, the vulnerable parameter, the payload used, and the potential business impact.

Visualized Attack Anatomy: A comprehensive diagram illustrates the three primary SQLi vectors:

In-Band (Direct)

Inferential (Blind)

Out-of-Band

In-depth Attack Matrix: A detailed table classifies different SQLi techniques, providing descriptions, sample payloads, risk levels, and real-world impact.

Defense-in-Depth Strategy: A dedicated section outlines a multi-layered defense strategy, covering best practices like Parameterized Queries, ORM usage, the Principle of Least Privilege, and Input Validation.

Modern, Responsive Design: Built with Tailwind CSS for a clean, professional, dark-mode interface that works seamlessly on all devices.

## 3. Tech Stack
Frontend: HTML5, Tailwind CSS, Vanilla JavaScript

AI & Language Models: Google Gemini API

Markdown Rendering: Marked.js (to display formatted responses from the Gemini API)

## 4. How to Use
Clone or download the repository.

Open the index.html file in any modern web browser.

Scroll down to the "AI Attack Lab" section to interact with the Gemini-powered features.

API Configuration
The JavaScript code is set up to call the Gemini API. For the API calls to function correctly, you need to provide an API key.

In the <script> section of the HTML file, locate the following line:

const apiKey = ""; // API Key is handled by the environment

Replace the empty string with your own Google Gemini API key if you are running this project outside of its original environment.

## 5. Credits
This project was conceptualized and developed for Group 8 for their cybersecurity presentation. The content and structure are tailored to provide a comprehensive and engaging educational experience.
