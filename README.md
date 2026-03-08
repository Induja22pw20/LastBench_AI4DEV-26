# StudySphere – AI-Powered Collaborative Learning Platform

## Overview

StudySphere is an AI-powered collaborative study platform designed to help students learn more effectively using their own study materials. The platform allows users to upload typed or handwritten notes, ask context-aware questions, generate quizzes and flashcards, and collaborate with peers through study groups and discussion channels.

The goal of StudySphere is to make learning more personalized, organized, and accessible while integrating academic preparation with placement readiness.

---

## Problem Statement

Students preparing for semester exams and placements often face several challenges:

* Study materials are scattered across PDFs, handwritten notes, and messaging apps
* Asking doubts directly from personal notes is difficult
* Group study platforms are unstructured and distracting
* Placement preparation resources are separated from academic study tools

StudySphere aims to solve these issues by creating a single platform that combines AI-powered learning assistance with collaborative study.

---

## Key Features

* **Notes & PDF Question Answering**
  Upload typed or handwritten notes and ask AI-powered questions directly from the content.

* **Handwritten Text Extraction**
  AI-based OCR extracts text from handwritten notes and converts it into structured digital content.

* **RAG-Based Answer Generation**
  Uses Retrieval-Augmented Generation to provide context-aware answers strictly from uploaded materials.

* **Quiz & Flashcard Generation**
  Automatically generates revision quizzes and flashcards from study content.

* **Collaborative Study Groups**
  Students can join public or private study groups for discussions and doubt solving.

* **Live Study Rooms**
  Audio-based focused study sessions for collaborative exam preparation.

* **Placement Preparation Modules**
  Technical, aptitude, and interview preparation resources integrated into the platform.

---

## Technology Stack

### Frontend

* Flutter (Cross-platform mobile application)
* Material UI Components

### Backend

* Python
* REST API architecture

### AI & Machine Learning

* Retrieval-Augmented Generation (RAG)
* Google Gemini LLM
* Vision OCR for handwritten notes
* Text embeddings for document search

### Database

* MongoDB (NoSQL database)

---

## System Workflow

1. User uploads typed or handwritten study notes
2. Text is extracted using PDF parsing or OCR
3. Extracted text is split into chunks
4. Embeddings are generated for semantic search
5. RAG retrieves relevant context
6. AI generates answers grounded in the uploaded content
7. System can also generate quizzes and flashcards for revision

---

## Proof of Concept (MVP)

The current Minimum Viable Product includes:

* PDF text extraction
* Handwritten note extraction using AI OCR
* RAG-based question answering
* Quiz and flashcard generation
* Flutter UI screens (Login, Dashboard, Chat interface)
* MongoDB database schema

---

## Future Enhancements

* AI-powered interview preparation sessions
* Mentor-assisted doubt solving
* Performance analytics and study insights
* AI-based exam recommendation system
* Integration with institutional learning systems

---

## Target Users

* College students preparing for semester exams
* Students preparing for placements
* Study groups and collaborative learners
* Institutions seeking AI-enabled learning platforms

---

## Business Model

The platform will follow a **freemium model**:

* Free access to basic study features
* Premium subscription for advanced AI features, unlimited uploads, and placement modules

---

## Project Status

Prototype / MVP Development Phase

---

## License

This project is intended for academic and research purposes.
