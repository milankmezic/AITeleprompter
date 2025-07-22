# 📺 AI Teleprompter

[![Watch on YouTube](https://img.youtube.com/vi/fi8pnLPxwi0/0.jpg)](https://www.youtube.com/watch?v=fi8pnLPxwi0)



A modern, intelligent teleprompter application that uses AI-powered speech recognition to follow your speech in real-time. Built with vanilla HTML, CSS, and JavaScript for maximum compatibility and performance.

## ✨ Features

### 🎤 **Smart Speech Recognition**
- Real-time speech-to-text with Web Speech API
- Intelligent word matching with backward and forward search
- Automatic highlighting of current word position
- Smart error recovery and phrase recognition

### 🎨 **Visual Feedback System**
- **Green highlighting** for current word
- **Red highlighting** for missed words
- **No highlighting** for mismatched words (counts as correct)
- Toggleable highlight system in settings

### 🛠️ **Advanced Customizable Settings**
- **Theme Selection**: Light and dark mode with system preference detection
- **Scroll Positioning**: Top, center, or bottom word positioning
- **Word Highlights**: Toggle visual feedback on/off
- **Font Size Control**: Adjustable text size (Small, Medium, Large, Extra Large)
- **Mirror Mode**: Horizontal flip for special teleprompter setups
- **Local Storage**: All settings and scripts are saved automatically

### 📊 **Enhanced Performance Analytics**
- Comprehensive speech analysis when session completes
- Accuracy percentage calculation with visual progress bar
- Reading speed (words per minute)
- Total reading time with precise timing
- Detailed statistics on correct vs missed words
- **Script Statistics**: Real-time word count and estimated reading time
- **Analysis History**: View previous session results with "Speech Analysis" button
- **Persistent Data**: Analysis results saved between sessions

### 🎯 **Professional Features**
- **Continuous Smooth Scrolling**: Keeps text flowing naturally
- **Line Break Preservation**: Maintains original script formatting
- **Pause/Resume**: Full control over speech recognition
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Manual Scroll Override**: Take control when needed
- **Modern UI**: Clean interface with Tailwind CSS styling
- **Toggle Switches**: Professional toggle controls for settings
- **Streamlined Layout**: Optimized settings organization

## 🚀 Getting Started

### Prerequisites
- Modern web browser with Web Speech API support (Chrome, Edge, Safari)
- Microphone access for speech recognition

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/milankmezic/AITeleprompter.git
   cd AITeleprompter
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your web browser
   open index.html
   # or
   python -m http.server 8000  # For local server
   ```

3. **Start using**
   - No build process required!
   - No dependencies to install!
   - Works offline after initial load!

## 📖 Usage

### Quick Start
1. **Launch** the application by opening `index.html`
2. **Configure** your settings (theme, scroll position, highlights)
3. **Enter** your script in the large text area
4. **Start** the teleprompter and begin speaking
5. **View** your performance analysis when complete

### Advanced Features

#### Script Formatting
- Supports line breaks and paragraph structure
- Maintains original text formatting
- Works with poetry, speeches, and structured content

#### Speech Recognition Tips
- Speak clearly and at a natural pace
- The system adapts to your speaking speed
- Pause/resume functionality for breaks
- Smart recovery from speech recognition errors

#### Performance Optimization
- Uses intelligent word matching algorithms
- Backward search up to entire script history
- Forward search up to 6 words ahead
- Real-time statistics tracking

## 🛠️ Technical Details

### Built With
- **HTML5** - Semantic structure and Web Speech API
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript** - No frameworks or dependencies
- **Web Speech API** - Real-time speech recognition
- **Local Storage** - Persistent settings and scripts

### Browser Compatibility
- ✅ Chrome (Recommended)
- ✅ Edge
- ✅ Safari
- ⚠️ Firefox (Limited Web Speech API support)

### Performance Features
- **Lazy Loading** - Optimized resource usage
- **Local Storage** - Fast settings persistence
- **Real-time Processing** - Minimal latency speech recognition
- **Responsive Design** - Adapts to any screen size

## 📁 Project Structure

```
AITeleprompter/
├── index.html          # Main application file
├── README.md           # Project documentation
└── LICENSE            # MIT license file
```

## 📋 Version History

### v2.0.0 - Enhanced UI & Analytics (Current)
**Release Date**: July 2025

#### ✨ New Features
- **Modern UI Migration**: Upgraded to Tailwind CSS for cleaner, more professional styling
- **Advanced Settings Page**: Moved all settings to a dedicated advanced settings screen
- **Font Size Control**: Added adjustable text size options (Small, Medium, Large, Extra Large)
- **Mirror Mode**: Added horizontal flip functionality for special teleprompter setups
- **Script Statistics**: Real-time word count and estimated reading time display
- **Speech Analysis Button**: Quick access to previous session results
- **Analysis Persistence**: Analysis data saved between sessions
- **Professional Toggle Switches**: Replaced checkboxes with modern toggle controls
- **Streamlined Layout**: Optimized main settings screen with full-width script input

#### 🔧 Improvements
- **Enhanced Reading Time**: Fixed precise timing calculation and display
- **Better Settings Organization**: Separated basic and advanced settings
- **Improved User Experience**: Cleaner interface with better visual hierarchy
- **Robust Error Handling**: Better handling of speech recognition edge cases
- **Performance Optimizations**: Improved real-time statistics updates

#### 🐛 Bug Fixes
- Fixed reading time calculation showing "0:00" in analysis modal
- Resolved duplicate HTML ID conflicts
- Fixed toggle switch styling and functionality
- Improved speech recognition end time tracking

### v1.0.0 - Initial Release
**Release Date**: July 2025

#### ✨ Core Features
- Real-time speech recognition with Web Speech API
- Word-by-word highlighting system
- Comprehensive performance analytics
- Light/dark theme support
- Local storage for settings persistence
- Responsive design for all devices
- Continuous smooth scrolling
- Pause/resume functionality

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Guidelines
1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Feature Requests
- 🎵 Audio cue support
- 📱 Mobile app version
- 🌐 Multi-language support
- 📤 Export functionality
- 🎥 Video recording integration

## 📝 License

This project is licensed under the GNU AFFERO GENERAL  - see the [LICENSE](LICENSE) file for details.


## 👨‍💻 Author

**Milan Kmezic**
- GitHub: [@milankmezic](https://github.com/milankmezic)
- LinkedIn: [Milan Kmezic](https://www.linkedin.com/in/milankmezic/)

## 🙏 Acknowledgments

- Built with the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)
- Inspired by professional teleprompter applications
- Thanks to the open source community for inspiration and feedback

## 📈 Roadmap

- [x] **Font Size Control** - Adjustable text size for better readability ✅
- [x] **Enhanced Analytics** - Improved performance metrics and timing precision ✅
- [x] **Modern UI** - Professional styling with Tailwind CSS ✅
- [x] **Advanced Settings** - Organized settings management ✅
- [ ] **External Script Loading** - Load scripts from URLs or external sources
- [ ] **Multi-language Support** - Support for different speech recognition languages
- [ ] **Export Functionality** - Export analysis results and scripts
- [ ] **Audio Cue Support** - Audio feedback for performance milestones

## 🐛 Bug Reports

If you find a bug, please create an issue with:
- **Browser** version and type
- **Steps** to reproduce
- **Expected** vs actual behavior
- **Screenshots** if applicable

## ⭐ Support

If you find this project helpful, please consider:
- ⭐ **Starring** the repository
- 🐛 **Reporting** bugs and issues
- 💡 **Suggesting** new features
- 🤝 **Contributing** to development

---

**Built with ❤️ for speakers, presenters, and content creators everywhere.**

