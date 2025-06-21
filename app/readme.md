📧 Cold Email Generator

Automated & Personalized Outreach for Software Services Companies

🚀 Overview

Cold Email Generator is a smart tool designed to automate and personalize the process of sending cold emails. Tailored for software service companies, it analyzes job postings to craft highly customized emails that highlight your company’s strengths and portfolio—helping sales teams connect with potential clients more effectively in a competitive market.

🧠 Problem Solved

Sales teams often send generic, templated emails to potential clients—resulting in low engagement and missed opportunities. This project solves that by:

Automatically understanding client needs from job postings.
Matching those needs with your company’s past work and strengths.
Generating personalized emails that make a real impact.
⚙️ Key Technologies

Tech	Purpose
Llama 3.1	Large Language Model used for understanding job postings and generating emails.
ChromaDB	Vector database for semantic search of portfolio projects and skills.
LangChain	Framework for orchestrating the LLM workflow and handling web scraping (via WebBaseLoader).
Streamlit	Interactive UI for entering job URLs and displaying generated emails.
Grok	Used to enable lightning-fast inference speeds with Llama 3.1.
🔁 Workflow

1. Input
User enters a job posting URL via the Streamlit interface.
2. Web Scraping
WebBaseLoader (LangChain) scrapes the job post content.
3. Information Extraction
Llama 3.1 extracts structured details from the post:
Job role
Required skills
Description
4. Portfolio Matching
Extracted skills and descriptions are used to semantically search ChromaDB for relevant projects from the company’s portfolio.
5. Email Generation
Llama 3.1 composes a tailored cold email using:
Extracted job info
Matching portfolio/project links
6. Output
A ready-to-send cold email crafted to resonate with the target company/client.
📸 UI Preview

Simple Streamlit interface to input job URLs and display generated emails.

