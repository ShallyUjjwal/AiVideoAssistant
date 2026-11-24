🎙️ AI Meeting Assistant

An AI-powered meeting assistant built with Python and modern LLM technologies to transform meeting recordings into structured, actionable insights.

🚀 Overview

The AI Meeting Assistant helps users process audio and video recordings, generate meaningful meeting summaries, identify important decisions, extract action items, and interact with meeting content through an AI-powered conversational interface.

The goal is to make meetings more productive by reducing manual note-taking and simplifying information retrieval.

✨ Key Features

Audio & Video Processing: Upload meeting recordings for processing.

Speech-to-Text: Convert spoken conversations into text.

Multilingual Transcription: Support for English, Hindi and Hinglish (where configured).

AI Meeting Summarization: Generate concise and structured meeting summaries.

Action Item Extraction: Identify tasks, owners and deadlines.

Decision Tracking: Extract important decisions made during meetings.

Follow-up Identification: Highlight unanswered questions and pending discussions.

AI-Powered Meeting Chat: Ask questions about meeting content using Retrieval-Augmented Generation (RAG).

Report Export: Export meeting insights into downloadable formats (where implemented).

🛠️ Technology Stack

Technology

Purpose

Python

Core application development

LangChain

LLM integration and processing workflows

LangGraph

Agent and workflow orchestration

OpenAI Whisper

Speech recognition

Sarvam AI

Hindi and multilingual transcription

Mistral AI

Language model integration

ChromaDB

Vector storage and retrieval

Hugging Face

Embeddings

Streamlit

User interface

The stack above should be adjusted to match the actual dependencies used in this repository.

🏗️ Architecture

The application follows a modular processing workflow:

Input: Accept an audio/video file or supported video URL.

Audio Processing: Extract and prepare audio for transcription.

Transcription: Convert speech into text.

AI Processing: Generate summaries and structured meeting insights.

Information Extraction: Identify action items, decisions and open questions.

Vector Storage: Generate embeddings and store meeting content.

RAG Pipeline: Retrieve relevant context to answer user questions.

Output: Present meeting insights and reports.
