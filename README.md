# Voice Recorder with Live Waveform Canvas
Record audio from the browser microphone with real-time oscilloscope waveform or frequency bar visualization.
## Features
- MediaRecorder API recording with graceful microphone permission handling
- Live oscilloscope waveform visualization using Web Audio AnalyserNode during recording
- Toggleable frequency bar visualizer mode showing spectral content
- VU meter showing real-time loudness level with color coding (green/yellow/red)
- Recordings list with play, download (.webm), and delete buttons; up to 5 recordings stored in localStorage
## Usage
Click "Request Microphone" to grant permission, then press Record to start. The waveform animates in real time. Stop recording to save it to the list below, where you can play, download, or delete each recording.
