Web Application to help with Dyslexia
Theme:- The Inclusive Classroom Assistant
Team-Tech Phantoms

Table of Contents
Introduction
Project Structure
HTML Structure
CSS Styles
JavaScript Code
Functionality Overview
Media Queries
1. Introduction    
The "Speech Synthesis" web application is designed to showcase the integration of the Web Speech API for speech synthesis. Users can select different voices, adjust speech parameters such as rate and pitch, input custom text, and control speech synthesis with the provided buttons.
2. Project Structure            
HTML File: index.html
CSS Stylesheet: style.css
JavaScript File: script.js
3. HTML Structure        
The HTML file (index.html) consists of the following main elements:
Head section with metadata, title, and external dependencies.
Body section containing the user interface components:
Heading (h1) with the application title.
Voice selection dropdown.
Rate and pitch input sliders.
Textarea for inputting custom text.
Speak and Stop buttons.
Social links and developer information.
4. CSS Styles
The CSS stylesheet (style.css) defines the visual appearance of the web application. Key styles include:
Background gradient for an appealing look.
Styling for the main container (voiceinator).
Styling for the heading, input elements, buttons, and social links.
Responsive design with media queries for different screen sizes.
5. JavaScript Code
The JavaScript file (script.js) contains the logic for interacting with the Web Speech API and managing the user interface. Key functionalities include:
Initialization of a SpeechSynthesisUtterance object (msg).
Handling voice selection and populating the voice dropdown.
Functions for setting voice, updating speech parameters, and controlling speech synthesis.
Event listeners for changes in voices, options, and button clicks.
6. Functionality Overview
Voice Selection:
Users can select a voice from the dropdown.
The application filters voices to include only those supporting the English language.
Speech Parameters:
Users can adjust the rate and pitch of the speech.
Text Input:
Users can input custom text into the textarea.
Speech Control Buttons:
"Speak" button initiates speech synthesis.
"Stop" button stops ongoing speech synthesis.
Developer Information:
Links to the developer's GitHub profile and personal website.
7. Media Queries
The application employs media queries to ensure a responsive design for various screen sizes. Notable adjustments include modifying the width of the main container and reducing the font size of the heading for smaller screens.
