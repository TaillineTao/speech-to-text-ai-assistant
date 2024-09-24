# speech-to-text-ai-assistant
This project is a real-time speech-to-text assistant built using AssemblyAI and OpenAI. It captures live audio input through a microphone, sends it to AssemblyAI's WebSocket API for transcription, and uses OpenAI to generate intelligent responses based on the transcription. 

## 1. Features
- Real-time audio capture and transcription using AssemblyAI's API
- Integration with OpenAI to generate responses from transcribed text
- Asynchronous processing to ensure smooth audio streaming and transcription

## 2. Tech Stack
- Python
- PyAudio (for capturing audio)
- WebSockets (for real-time communication with AssemblyAI)
- AssemblyAI (speech-to-text API)
- OpenAI (language generation API)
- Asyncio (for asynchronous concurrency)

## 3. Installation & Setup
  1.Clone this repository
  
  2.Create a virtual environment and install dependencies:
  
    python3 -m venv venv
    source venv/bin/activate  # For Linux/macOS
    venv\Scripts\activate     # For Windows
    pip install -r requirements.txt
    
  3.Configure API Keys:
    Add your AssemblyAI and OpenAI API keys to the api_secrets.py file.
    
  4.Run the application:
  
    python main.py


