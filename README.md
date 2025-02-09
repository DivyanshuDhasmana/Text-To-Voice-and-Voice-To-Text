<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Voice to Text / Text to Voice Converter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
        }
        code {
            background: #e8e8e8;
            padding: 2px 5px;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Voice to Text / Text to Voice Converter</h1>
        <p>This Python project provides a simple GUI to convert voice to text and text to speech using <code>tkinter</code>, <code>speech_recognition</code>, and <code>gtts</code>.</p>
        
        <h2>Features:</h2>
        <ul>
            <li>Convert speech to text using Google Speech Recognition API.</li>
            <li>Convert text to speech using Google Text-to-Speech (gTTS).</li>
            <li>Simple and user-friendly graphical interface.</li>
        </ul>
        
        <h2>Requirements:</h2>
        <p>Ensure you have the following dependencies installed:</p>
        <pre>
        pip install tkinter gtts speechrecognition
        </pre>
        
        <h2>How to Run:</h2>
        <ol>
            <li>Save the provided Python script as <code>voice_text_converter.py</code>.</li>
            <li>Run the script using Python:</li>
            <pre>
            python voice_text_converter.py
            </pre>
            <li>Choose either "Voice to Text" or "Text to Voice" mode.</li>
            <li>For voice input, speak into your microphone.</li>
            <li>For text-to-speech, enter text and listen to the audio output.</li>
        </ol>
        
        <h2>Author:</h2>
        <p>Made by <strong>Divyanshu</strong></p>
    </div>
</body>
</html>
