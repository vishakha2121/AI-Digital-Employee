# 🤖 AI Digital Employee

[![GitHub stars](https://img.shields.io/github/stars/vishakha2121/AI-Digital-Employee)](https://github.com/vishakha2121/AI-Digital-Employee/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/vishakha2121/AI-Digital-Employee)](https://github.com/vishakha2121/AI-Digital-Employee/network)
[![GitHub issues](https://img.shields.io/github/issues/vishakha2121/AI-Digital-Employee)](https://github.com/vishakha2121/AI-Digital-Employee/issues)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## 🌟 Overview

**AI-Digital-Employee** is a generative AI-powered virtual assistant that autonomously attends meetings, transcribes speech, generates comprehensive reports, analyzes documents, and automates office workflows using Google Gemini LLM and speech-to-text technology with React frontend and FastAPI backend.

> 🎯 **Project Status**: Practice/Portfolio Project

---

## ✨ Key Features

### 📅 Meeting Management
- Schedule, attend, and manage virtual meetings
- Real-time speech-to-text transcription
- AI-generated meeting summaries and action items
- Meeting recording and storage

### 📄 Report Generation
- AI-powered report creation and customization
- Multiple export formats (PDF, Word, HTML)
- Template-based report generation
- Collaborative editing capabilities

### 📂 Document Analysis
- Upload and process multiple document types (PDF, DOCX, TXT)
- AI-powered content analysis and summarization
- Keyword extraction and semantic search
- Question-answering on documents

### 🔄 Workflow Automation
- Visual workflow builder with drag-and-drop interface
- Automated task execution and scheduling
- Trigger-based workflows
- Real-time workflow monitoring

### 🧠 Memory System
- Persistent contextual memory
- Learning from user interactions
- Personalized responses and recommendations
- Memory cleanup and optimization

### 🎙️ Speech-to-Text
- Real-time audio transcription
- Multi-language support
- Speaker diarization
- Noise cancellation

---

## 🛠️ Technology Stack

### Frontend
| Technology | Purpose |
|------------|---------|
| **React.js** | UI Framework |
| **Tailwind CSS** | Styling & Design |
| **Axios** | API Communication |
| **React Router** | Navigation |
| **Recharts** | Data Visualization |
| **React Hook Form** | Form Management |

### Backend
| Technology | Purpose |
|------------|---------|
| **Python 3.10+** | Programming Language |
| **FastAPI** | REST API Framework |
| **SQLAlchemy** | ORM & Database Management |
| **Alembic** | Database Migrations |
| **Pydantic** | Data Validation |

### AI & ML
| Technology | Purpose |
|------------|---------|
| **Google Gemini** | LLM Integration |
| **Google Speech-to-Text** | Speech Recognition |
| **Custom Memory System** | Context Management |

### Database & Cache
| Technology | Purpose |
|------------|---------|
| **SQLite** | Primary Database |
| **Redis** | Caching & Task Queue |

### Task Queue
| Technology | Purpose |
|------------|---------|
| **Celery** | Distributed Task Queue |
| **Redis** | Message Broker |

---

## 📊 Project Structure

---

## 🚀 Quick Start Guide

### Prerequisites
- Python 3.10 or higher
- Node.js 18 or higher
- Git
- Redis (optional, for production)

### 1. Clone the Repository
```bash
git clone https://github.com/vishakha2121/AI-Digital-Employee.git
cd AI-Digital-Employee

# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
cp .env.example .env

# Edit .env with your API keys
# Add your Gemini API key: GEMINI_API_KEY=your-key-here

# Run database migrations
alembic upgrade head

# Start the backend server
uvicorn app.main:app --reload

# Open new terminal
cd frontend

# Install dependencies
npm install

# Create .env file
cp .env.example .env

# Start the development server
npm start