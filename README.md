# OmniShield AI - Proactive Cybercrime & Scam Protection
**Developed by:** Applied Technology High School (ATHS) Team  
**Event:** ScamShield AI Hackathon (Abu Dhabi Police & 42 Abu Dhabi)

## 1. Problem & Solution
* **The Problem:** Cybercriminals increasingly use sophisticated phishing links, voice impersonation (Vishing), and deepfakes tailored to local dialects to deceive victims before traditional security tools can react.
* **The Solution:** OmniShield AI is a real-time, multi-modal AI shield that analyzes incoming messages, suspicious URLs, and live voice calls directly on the user's device, providing instant red-alert warnings before any financial or data loss occurs.

## 2. Technical Choices, Privacy & Trade-offs
* **Architecture & Model Choices:** We designed a lightweight client-side simulation utilizing Natural Language Processing (NLP) keyword/intent classification and real-time audio transcript analysis trained to recognize Gulf/Emirati dialects alongside standard Arabic and English.
* **Privacy-First Design (Edge AI):** To comply with UAE data protection standards and ensure user trust, all processing is designed to run locally on the device (Edge AI) without storing or transmitting personal calls or messages to external servers.
* **Trade-offs & Future Improvements:** Due to the hackathon's timeframe, our current MVP simulates live telecom API interception and deepfake audio streaming via an interactive web interface. With additional time, we plan to integrate native Android/iOS call-screening APIs and deploy a fine-tuned Whisper + LLM quantized model for on-device execution.

## 3. How to Build and Run the Project
No complex installation or external servers are required to test the MVP:
1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Safari, Edge).
3. Test the live simulation modules for **SMS/URL Phishing Detection** and **Live Vishing Call Protection**.