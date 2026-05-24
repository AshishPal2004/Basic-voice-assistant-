# Basic Voice Assistant - Hero

A Python-based voice assistant with advanced features including voice recognition, text-to-speech, computer vision, and system control capabilities.

## 🌟 Features

- **Voice Recognition**: Listen and respond to voice commands using speech recognition
- **Text-to-Speech**: Natural voice responses using advanced TTS technology
- **Computer Vision**: Object detection and visual analysis using YOLOv8
- **Memory System**: Persistent memory to remember user preferences and conversation history
- **System Control**: Control your computer with voice commands
- **Interactive UI**: User-friendly interface for seamless interaction
- **Batch Launcher**: Easy one-click startup with `hero_launcher.bat`

## 📋 Prerequisites

- Python 3.7 or higher
- Microphone for voice input
- Webcam (optional, for vision features)
- Windows OS (for batch launcher and some system controls)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AshishPal2004/Basic-voice-assistant-.git
   cd Basic-voice-assistant-
   ```

2. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the assistant**
   
   **Option 1**: Using the batch launcher (Windows)
   ```bash
   hero_launcher.bat
   ```
   
   **Option 2**: Using Python directly
   ```bash
   python hero.py
   ```

## 📦 Project Structure

```
Basic-voice-assistant-/
├── hero.py                 # Main application entry point
├── brain.py               # Core AI logic and command processing
├── listener.py            # Speech recognition module
├── voice.py               # Text-to-speech module
├── vision.py              # Computer vision capabilities
├── ui.py                  # User interface components
├── memory.py              # Memory management system
├── system_control.py      # System control functions
├── test_voice.py          # Voice testing utilities
├── hero_launcher.bat      # Windows batch launcher
├── requirements.txt       # Python dependencies
├── app_memory.json        # Application memory storage
├── hero_memory.json       # Hero-specific memory storage
├── yolov8n.pt            # YOLOv8 model weights
├── __pycache__/          # Python cache files
├── recordings/           # Audio recordings storage
└── vision_output/        # Computer vision output files
```

## 🎯 Usage

### Basic Commands

Once the assistant is running, you can interact with it using voice commands:

- **General Conversation**: Just speak naturally to the assistant
- **System Control**: Commands to control your computer
- **Vision Tasks**: Request object detection or image analysis
- **Information Queries**: Ask questions and get intelligent responses

### Testing Voice Output

Run the test script to verify text-to-speech functionality:
```bash
python test_voice.py
```

## 🛠️ Key Modules

### Brain (`brain.py`)
The core intelligence module that processes commands and generates appropriate responses.

### Listener (`listener.py`)
Handles speech recognition, converting spoken words into text commands.

### Voice (`voice.py`)
Manages text-to-speech conversion for natural voice responses.

### Vision (`vision.py`)
Implements computer vision capabilities using YOLOv8 for object detection and analysis.

### Memory (`memory.py`)
Maintains conversation history and user preferences across sessions.

### System Control (`system_control.py`)
Provides system-level controls and automation capabilities.

### UI (`ui.py`)
Creates an interactive user interface for better user experience.

## 🔧 Configuration

The assistant uses JSON files for storing configuration and memory:

- `app_memory.json`: General application settings and data
- `hero_memory.json`: User-specific preferences and conversation history

## 🎨 Features in Detail

### Voice Recognition
- Real-time speech-to-text conversion
- Multiple language support
- Noise filtering and accuracy optimization

### Text-to-Speech
- Natural-sounding voice output
- Customizable voice parameters
- Cached audio files for frequently used responses

### Computer Vision
- Object detection using YOLOv8
- Real-time image analysis
- Visual feedback and results storage

### Memory System
- Persistent storage of user preferences
- Conversation history tracking
- Context-aware responses

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📝 License

This project is open source and available for educational and personal use.

## 🐛 Troubleshooting

### Common Issues

**Issue**: Microphone not working
- **Solution**: Check your microphone permissions and default input device

**Issue**: Import errors
- **Solution**: Ensure all dependencies are installed: `pip install -r requirements.txt`

**Issue**: YOLOv8 model not found
- **Solution**: Verify that `yolov8n.pt` is present in the project directory

**Issue**: Voice output not working
- **Solution**: Check your audio output device and speaker settings

## 🔮 Future Enhancements

- [ ] Multi-language support
- [ ] Cloud integration for advanced features
- [ ] Mobile app companion
- [ ] Plugin system for extensibility
- [ ] Enhanced natural language understanding
- [ ] Smart home device integration

## 👨‍💻 Author

**Ashish Pal**
- GitHub: [@AshishPal2004](https://github.com/AshishPal2004)

## 🙏 Acknowledgments

- YOLOv8 for computer vision capabilities
- Python speech recognition and TTS libraries
- The open-source community for various tools and libraries

## 📞 Support

For issues, questions, or suggestions, please open an issue on the [GitHub repository](https://github.com/AshishPal2004/Basic-voice-assistant-/issues).

---

**Note**: This is a basic voice assistant project designed for learning and experimentation. For production use, additional security and error handling should be implemented.
