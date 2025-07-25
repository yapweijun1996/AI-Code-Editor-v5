# Architecture

This document outlines the architecture of the AI-Powered Code Editor.

## Core Components

*   **Frontend**: A single-page application built with HTML, CSS, and JavaScript. It uses the Monaco Editor for the text editor and communicates with the backend via a REST API.
*   **Backend**: A Node.js server using Express. It handles requests from the frontend, communicates with the Google Gemini API, and can execute terminal commands.
*   **AI Agent**: The agent logic is integrated into the frontend, using the Gemini API for tool-calling and chat functionality.
