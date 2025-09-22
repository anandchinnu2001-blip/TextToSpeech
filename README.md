# TextToSpeech
This project is a simple web-based application that converts written text into spoken audio using the browser’s built-in speech synthesis API. The interface allows users to type or paste text into a text area and then listen to it in real time.

Key Features:

User-friendly Interface: A clean and responsive design where users can enter text easily.
Language/Voice Selection: A dropdown menu (select element) intended for choosing different voices or languages.
Instant Playback: A “Listen” button triggers the text-to-speech functionality, playing the entered text aloud.
Lightweight & Fast: Built using plain HTML, CSS, and JavaScript without heavy frameworks.

How it Works:
Users type or paste text into the text area.
They select a desired voice (if multiple voices are available).
Clicking the Listen button calls a JavaScript function (in script.js) that uses the Web Speech API to synthesize and play the speech.

Technologies Used:
HTML5 for structure.
CSS3 for styling (via style.css).
JavaScript for functionality (via script.js).
Web Speech API (SpeechSynthesis) for converting text to speech.
