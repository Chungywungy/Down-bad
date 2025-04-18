# Down-bad
Project Design Document  Offline AI Assistant

1.	Project Title
I am down bad :D

3.	Project Overview

Goal:
Create an offline AI assistant that:
-	Accepts text input from the user
-	Replies via text and optionally via speech
-	Manages a local schedule/reminders
-	Can interact with your PC (e.g. open files/apps)
-	Displays output through a reactive animated PNG avatar

3.	Core Features (v1)
Feature                  | Description                                               | Status
------------------------|-----------------------------------------------------------|--------
Text Input              | User types messages to the assistant                      | To Do
Voice Output            | Assistant speaks its replies aloud                        | To Do
Scheduling System       | Local calendar/reminder tool                              | To Do
PC Interaction          | System automation: open files, control volume, etc.       | To Do
AI Brain (NLP)          | Understands and responds to commands via LLM              | To Do
Animated PNG Avatar     | Visual feedback that reacts to interaction                | To Do

4.	Optional/Future Features
-	GUI Input Box
-	Emotion-based voice tone
-	Toggle for silent vs speaking mode
-	System tray integration

5.	Technology Stack
Component                | Tool/Library/Option                | Notes
------------------------|------------------------------------|------------------------------
Programming Language     | Python                             | Primary backend
Text Input UI            | Tkinter, Electron, or Terminal     | Simple user input
Text-to-Speech           | Coqui TTS, Piper, eSpeak NG        | Offline voice synthesis
Local LLM                | llama.cpp, Mistral, GPT4All        | Handles assistant responses
PC Control               | pyautogui, subprocess, keyboard    | For automation & control
Animated Avatar          | PNG sequence, Live2D, Godot        | Basic animation on events

6.	Architecture Diagram
User (Text Input)  AI (LLM) 
      Text Reply Display
      Voice Output (TTS)
      System Action Trigger
      Avatar Reaction Trigger
  	
8.	Timeline 
Week | Goal                           | Deliverables
-----|--------------------------------|-----------------------------
1	| Set up LLM + text interface    | Simple input  response
x| Add voice output via TTS       | Assistant can speak
x| Implement scheduling/reminder  | Local calendar w/ reminders
x| Add system command execution   | Run apps, control volume
x| Avatar animation integration   | APNG reacts to replies
x| Final integration + polish     | Fully working assistant
