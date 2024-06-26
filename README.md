<!DOCTYPE html>
<html lang="en">
<body>
    <h1>Real-Time Speech Translation</h1>
    <h2>Overview</h2>
    <p>This project demonstrates a real-time speech translation application using Python and various libraries.</p>
    <h2>Dependencies</h2>
    <ul>
        <li><code>speech_recognition</code>: Python library for speech recognition</li>
        <li><code>googletrans</code>: Python wrapper for Google Translate API</li>
        <li><code>nltk</code>: Natural Language Toolkit for NLP tasks</li>
        <li><code>numpy</code>: Library for numerical computations</li>
        <li><code>pandas</code>: Library for data manipulation and analysis</li>
        <li>Other standard Python libraries</li>
    </ul>
    <h2>Key Features</h2>
    <ul>
        <li><strong>Speech Recognition:</strong> Utilizes the Google Web Speech API through <code>speech_recognition</code> library to transcribe spoken words into text.</li>
        <li><strong>Language Translation:</strong> Integrates <code>googletrans</code> library to translate recognized text into multiple target languages.</li>
        <li><strong>Dynamic Language Selection:</strong> Supports a wide range of languages for both source and target translations.</li>
        <li><strong>Ambient Noise Adjustment:</strong> Enhances accuracy by adjusting for ambient noise levels during speech recognition.</li>
    </ul>
    <h2>Technologies Used</h2>
    <ul>
        <li><strong>Python:</strong> Used for application development.</li>
        <li><strong>Libraries:</strong> <code>speech_recognition</code>, <code>googletrans</code>, <code>numpy</code>, <code>pandas</code>, <code>re</code>, <code>nltk</code>, <code>sklearn</code>.</li>
        <li><strong>Integrated Development Environment (IDE):</strong> Used Visual Studio Code</li>
    </ul>
    <hr>
    <h2>Setup</h2>
    <ol>
        <li>Clone the repository:</li>
        <code>git clone https://github.com/your-username/real-time-speech-translation.git</code>
        <li>Install dependencies:</li>
        <code>pip install -r requirements.txt</code>
        <li>Run the application:</li>
        <code>python transcribe_translate.py</code>
    </ol>
    <h2>Usage</h2>
    <p>Upon running the application, follow the prompts to select the source language and begin speaking for real-time translation.</p>
    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <code>LICENSE</code> file for details.</p>
    <hr>
    <p align="center">Generated by README generator v1.0</p>
</body>
</html>
