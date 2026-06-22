# PathBridge AI – Multi-Agent Career Intelligence System

## Overview

PathBridge AI is an intelligent multi-agent career intelligence platform designed to support professionals in discovering relevant opportunities, evaluating profile-job alignment, and generating tailored career assets.

The system leverages a LangGraph-based orchestration framework where specialized AI agents collaborate to analyze user profiles, search job opportunities, optimize CVs, generate cover letters, and identify skill gaps.

This project was developed as part of an Agentic AI Systems program and demonstrates practical application of multi-agent architectures, workflow orchestration, semantic search, and LLM-powered decision support.

---

## Problem Statement

Job seekers often struggle with:

* Finding highly relevant job opportunities
* Understanding skill gaps
* Tailoring CVs for specific roles
* Preparing for interviews efficiently

Traditional job boards provide listings but lack personalized intelligence and guidance.

PathBridge AI addresses this challenge through a coordinated multi-agent workflow that automates career analysis and recommendation processes.

---

## Key Features

### Navigator Agent

* Extracts and structures user profile information
* Identifies goals, skills, and constraints
* Maps career objectives

### Scout Agent

* Retrieves jobs from external job sources
* Performs hybrid ranking and relevance scoring
* Identifies best-fit opportunities

### Coach Agent

* Generates tailored CV recommendations
* Produces customized cover letters
* Creates interview preparation materials

### Evaluator Agent

* Measures job-profile alignment
* Performs skill-gap analysis
* Generates readiness scores and recommendations

### Orchestrator Agent

* Coordinates agent interactions
* Controls workflow execution
* Handles routing and recovery logic

---

## Technology Stack

* Python
* LangGraph
* Azure OpenAI
* Pydantic
* Streamlit
* Semantic Search
* Vector Similarity Scoring
* GitHub

---

## System Architecture

Architecture diagrams and workflow illustrations are provided in the Images section below.

---

## Technical Highlights

* Multi-agent architecture with six specialized agents
* Shared state management using TypedDict schemas
* LangGraph workflow orchestration
* Hybrid semantic and heuristic job scoring
* Structured Pydantic validation
* Skill-gap evaluation framework
* Automated career asset generation

---

## My Contributions

* Multi-agent workflow design
* LangGraph orchestration architecture
* State schema design
* Evaluation framework development
* Prompt engineering and agent interaction design
* Testing and workflow validation

---

## Future Enhancements

* Persistent memory layer
* Workflow monitoring dashboard
* Enhanced job-provider integrations
* Advanced analytics and reporting
* User feedback loops

---

## Disclaimer

This repository is a showcase version created for portfolio and demonstration purposes. Implementation details, proprietary logic, prompts, and production source code are not included.
