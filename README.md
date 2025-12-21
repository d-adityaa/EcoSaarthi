# EcoSaarthi

EcoSaarthi is an offline-first eco and cultural tourism safety application designed for rural and forest regions where internet connectivity is weak or unavailable.

## Problem Statement
Travelers visiting rural, forest, and eco-tourism regions often face serious safety challenges due to poor internet connectivity. Existing travel applications depend heavily on real-time internet access and fail completely in offline environments, leaving users without safety guidance, local rules, cultural awareness, or emergency support.

## Solution Overview
EcoSaarthi addresses this problem by providing a dual-mode travel safety companion.

Online Mode:
EcoSaarthi uses Google Maps API to detect the user’s live location and Google Gemini API to generate concise, AI-powered summaries related to general information, activities, accommodation, facilities, transportation, safety rules, skills, and emergency support.

Offline Mode:
EcoSaarthi works without GPS or internet using a Rule-Based Location Inference System. Users answer simple observation-based questions such as terrain, climate, and direction. These inputs are matched against a preloaded regional knowledge base stored locally in JSON format to provide approximate regional guidance, safety instructions, and emergency information.

Offline results are clearly labeled as approximate.

## Safety Features
- Compass navigation using device sensors (offline supported)
- SOS emergency button for quick access to emergency services
- Multilingual support using preloaded language files

## Technologies Used

Google Technologies:
- Google Drive
- Google Sheets
- Google Docs
- Google Slides
- Google Maps API
- Google Gemini API

Development Framework & Tools:
- Flutter
- Android SDK
- JSON for offline data storage

AI & Assistance Tools:
- Google Gemini API (primary AI tool)
- ChatGPT (development and documentation assistance)
- GitHub Copilot (coding assistance)

Note: ChatGPT and GitHub Copilot were used only as development assistance tools. Core AI functionality is powered by Google Gemini API.

## MVP Status
This repository represents the Minimum Viable Product (MVP) of EcoSaarthi and demonstrates the system architecture, offline logic, and safety-focused design.

## Hackathon Compliance
This project was developed entirely during the hackathon timeline. No pre-existing projects, coursework, or plagiarized code were used.

## Conclusion
EcoSaarthi combines Google’s ecosystem with offline intelligence to ensure safe, reliable, and responsible travel experiences in rural and forest regions.
