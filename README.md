<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>

<h1>Gemini Talker - AI Chatbot for Admission Counselling</h1>

<h2>Overview</h2>
<p><strong>Gemini Talker</strong> is an AI-powered chatbot designed to assist students during <strong>JEE Mains</strong> and <strong>JOSAA Counselling</strong>. The chatbot provides personalized guidance, including <strong>rank prediction</strong>, <strong>college allocation</strong>, and <strong>counselling support</strong>. Built using <strong>Natural Language Processing (NLP)</strong> and integrated with multilingual capabilities, Gemini Talker improves accessibility for students from various linguistic backgrounds.</p>

<p>The chatbot is developed with <strong>Dialogflow</strong>, <strong>Gemini API</strong>, and deployed using <strong>Firebase</strong>. It handles real-time queries regarding admissions, eligibility, seat matrix, deadlines, and required documentation, ensuring a smoother and more efficient admission experience for students.</p>

<h2>Key Features</h2>
<ul>
    <li><strong>Rank Prediction & College Suggestion</strong>: Uses past data and trained models to estimate rank ranges and suitable institutes.</li>
    <li><strong>Multilingual Support</strong>: Enables students to communicate in regional languages using Google Translate API integration.</li>
    <li><strong>Real-time Chat Support</strong>: Handles student queries regarding the JEE process, eligibility, branch cut-offs, etc., 24x7.</li>
    <li><strong>Document and Deadline Guidance</strong>: Provides step-by-step help for required documents, important dates, and counselling rounds.</li>
</ul>

<h2>Tech Stack</h2>
<ul>
    <li><strong>Gemini API</strong>: AI-powered model for contextual understanding and dynamic response generation.</li>
    <li><strong>Dialogflow</strong>: NLP platform for intent recognition and conversation flow management.</li>
    <li><strong>Google Translate API</strong>: Real-time language translation for multilingual query handling.</li>
    <li><strong>Firebase</strong>: Used for hosting the web-based chatbot frontend and backend webhook integration.</li>
    <li><strong>HTML/CSS/JS</strong>: For basic interface design during testing and deployment.</li>
</ul>

<h2>System Architecture</h2>
<ul>
    <li><strong>User Input</strong>: Student interacts with chatbot via text input (web interface or integrated app).</li>
    <li><strong>Dialogflow Agent</strong>: Recognizes intent and forwards queries to the webhook or Gemini API.</li>
    <li><strong>Gemini API</strong>: Handles contextual understanding and responds intelligently to the query.</li>
    <li><strong>Translation Layer</strong>: Google Translate API enables multilingual input/output handling.</li>
    <li><strong>Firebase Hosting</strong>: Hosts the chatbot and manages webhook communication securely.</li>
</ul>

<h2>Usage</h2>
<ol>
    <li><strong>Students</strong> can enter queries related to JEE rank, college prediction, or counselling steps.</li>
    <li><strong>Chatbot</strong> processes the input via Dialogflow, routes it to Gemini for AI-based answers.</li>
    <li><strong>Response</strong> is translated back (if needed) and displayed to the student with clarity and follow-up prompts.</li>
    <li><strong>Multilingual support</strong> ensures students from different regions can understand and use the service effectively.</li>
</ol>

<h2>Project Outcomes</h2>
<ul>
    <li>Tested successfully with various student queries during mock counselling sessions.</li>
    <li>Reduced dependency on manual help desks during the JEE admission window.</li>
    <li>Highly appreciated by the ECE Department of NIT Jalandhar during final evaluation.</li>
</ul>

<h2>Future Enhancements</h2>
<ul>
    <li>Add voice-based interaction using Speech-to-Text modules.</li>
    <li>Integrate with official JOSAA data sources via APIs for live cut-offs and results.</li>
    <li>Support for state-level counselling (e.g., HSTES, REAP, UPSEE) beyond JOSAA.</li>
</ul>

<h2>Authors</h2>
<ul>
    <li><strong>Hiteshwar Singh</strong> – Data modelling & backend integration</li>
    <li><strong>Gulshan</strong> – NLP pipeline, Gemini integration, multilingual support</li>
    <li><strong>Divya Gupta</strong> – UI/UX testing and deployment</li>
    <li><strong>Daksh Khatkar</strong> – Backend logic, testing, flow optimization</li>
    <li><strong>Supervisor</strong>: Dr. Arun K Khosla, Professor, NIT Jalandhar</li>
</ul>

<h2>License</h2>
<p>This project is intended for academic and educational use only.</p>

</body>
</html>
