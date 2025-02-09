<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Voice to Text / Text to Voice Converter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f9f9f9;
        }
        .container {
            max-width: 800px;
            background: white;
            padding: 20px;
            margin: auto;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
        }
        code, pre {
            background: #e8e8e8;
            padding: 5px;
            border-radius: 4px;
            display: block;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Voice to Text / Text to Voice Converter</h1>
        <p>This project is a simple GUI application that allows users to convert voice to text and text to speech using Python libraries like <code>tkinter</code>, <code>speech_recognition</code>, and <code>gtts</code>.</p>
        
        <h2>Features</h2>
        <ul>
            <li>Convert speech to text using Google Speech Recognition API.</li>
            <li>Convert text to speech using Google Text-to-Speech (gTTS).</li>
            <li>Easy-to-use graphical interface.</li>
        </ul>
        
        <h2>Requirements</h2>
        <p>Ensure you have the following dependencies installed:</p>
        <pre>
        pip install tkinter gtts speechrecognition pyaudio
        </pre>
        
        <h2>How to Run</h2>
        <ol>
            <li>Save the Python script as <code>voice_text_converter.py</code>.</li>
            <li>Run the script using:</li>
            <pre>python voice_text_converter.py</pre>
            <li>Select either "Voice to Text" or "Text to Voice" mode.</li>
            <li>For voice input, speak into the microphone.</li>
            <li>For text-to-speech, enter text and listen to the audio output.</li>
        </ol>
        
        <h2>Author</h2>
        <p>Created by <strong>Divyanshu</strong></p>
    </div>
</body>
</html>
