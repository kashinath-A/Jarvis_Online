# JARVIS 3.0 AI Assistant 🤖

## 📖 Overview
**JARVIS 3.0** is an advanced, fully interactive personal AI assistant designed to bridge the gap between large language models and local machine control. Powered by the free Google Gemini API, this system runs locally on your machine using Python and acts as a two-way conversational agent. 

Unlike standard text-based AI, JARVIS 3.0 continuously listens for its wake word, remembers previous context, and has the authority to execute system-level commands on your operating system—giving you a true "Iron Man" style desktop assistant.

---

## ✨ Core Capabilities

* **Wake Word Activation:** The system runs dynamically in the background, continuously listening for the exact phrase *"Hey Jarvis."* Once detected, it instantly wakes up and awaits your command without needing manual keyboard input.
* **Recallable Memory:** JARVIS features long-term contextual awareness. It remembers important details, facts, and preferences from previous conversations and can recall them accurately during future sessions.
* **Real-Time Voice Processing:** Enjoy seamless, natural, two-way voice conversations. The assistant processes your speech instantly and replies back with natural vocal generation.
* **System Control & Automation:** Beyond just answering questions, JARVIS can control your PC using natural language commands. You can ask it to open applications, fetch live news, check system status, and manage tasks directly on your OS.
* **Cross-Platform Compatibility:** The codebase is designed to run natively on Windows, macOS, and Linux environments.

---

## 🛠️ Prerequisites & Tech Stack

Before diving into the setup, ensure your development environment is ready:
1. **[Visual Studio Code (VS Code)](https://code.visualstudio.com/):** The recommended IDE for managing the project files and running the local terminal.
2. **[Python 3.11+](https://www.python.org/downloads/):** The core runtime environment. *(Tested perfectly on Python 3.13).*
   > **⚠️ CRUCIAL PATH WARNING:** When running the Python installer, look at the very bottom of the first installation window and **check the box that says "Add python.exe to PATH"**. If you skip this, your terminal will not recognize Python commands and the setup will fail.

---

## 🚀 Step-by-Step Installation Guide

### Step 1: Generate Your Brain (Free Gemini API Key)
JARVIS relies on Google's Gemini AI Studio to process language and generate intelligent responses.
1. Navigate to [Google AI Studio](https://aistudio.google.com/) in your browser.
2. Ensure you are logged into your Google Account.
3. On the dashboard, click on **Create API Key**.
4. Name the key something recognizable (e.g., `Jarvis version 3.0`) so you know what it is being used for.
5. Wait for the key to generate, then **copy the API string**. 
6. Paste it into a secure Notepad file for later. *(Security Note: Never upload this key to a public GitHub repo or share it with anyone).*

### Step 2: Download the Core Architecture
1. Download the `Mark L2` (or latest available) version of this project's repository. Click the green **Code** button and select **Download ZIP**.
2. Locate the `.zip` file in your system, right-click it, and select **Extract All**. Choose a dedicated folder for your Jarvis project.

### Step 3: Initialize the Codebase
1. Open **Visual Studio Code**.
2. Navigate to `File` > `Open Folder...` and select the extracted project folder. You should now see all the project files in the left-hand explorer pane.

### Step 4: Install Dependencies & Libraries
JARVIS relies on several Python libraries to handle speech recognition, text-to-speech, and system controls.
1. Open a terminal directly inside VS Code by clicking `Terminal` > `New Terminal` in the top menu bar.
2. Run the initialization script by typing the following command and hitting Enter:
   ```bash
   py setup.py
