# LexCoder: ASD Utterances Annotation Tool

Made with ♥ for the Autism Community

A web-based video annotation tool designed specifically for coding and analyzing utterances in autism spectrum disorder (ASD) research. LexCoder provides researchers with an intuitive interface to annotate video recordings and generate detailed CSV reports for further analysis.

## Features

### 🎯 Dual Coding Modes
- **Simple Mode** (Default): Basic utterance coding with Kid/Adult categories
- **Advanced Mode**: Detailed categorization with 5 kid types and 6 adult interaction types

### 📹 Video Integration
- Support for MP4, WebM, and other HTML5 video formats
- Real-time subtitle overlays during video playback
- Keyboard controls for precise navigation (Space, Arrow keys)
- Video timeline integration with annotations

### 📝 Annotation Features
- **Real-time coding**: Hold buttons/keys while utterance occurs
- **Precise timing**: 100ms adjustment controls for fine-tuning
- **Note-taking**: Add contextual notes to any utterance
- **Edit functionality**: Modify timing, type, speaker, and notes
- **Visual feedback**: Color-coded buttons and subtitle overlays

### 🎹 Keyboard Shortcuts
#### Simple Mode
- `Q` - Kid Utterance
- `W` - Adult Utterance

#### Advanced Mode - Kid Utterances
- `A` - Unintelligible
- `S` - Imitative
- `D` - Verbal Prompt
- `F` - Non-Verbal Prompt
- `V` - Spontaneous

#### Advanced Mode - Adult Utterances
- `N` - Initiate-Offer
- `J` - Prompt
- `K` - Model
- `L` - Encourage
- `;` - Instruct
- `M` - Reinforce-Reward

### 📊 Data Management
- **CSV Import/Export**: Standard 11-column format with coder attribution
- **Auto-save detection**: Smart button states prevent data loss
- **Change tracking**: Visual indicators for unsaved modifications
- **Mode detection**: Automatically switches interface based on loaded data
- **Statistics summary**: Real-time counts and totals

### 🔄 File Handling
- **Load existing work**: Continue coding from previous sessions
- **Smart filename generation**: `videoname_mode_coder.csv` format
- **Reset functionality**: Clean slate for new sessions
- **Mode-aware exports**: Appropriate totals for simple vs advanced data

## Installation

1. Download the `LexCoder.html` file from this repository
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. No additional installation or server setup required

## Usage

### Getting Started
1. **Load Video**: Click "Load Video" and select your video file
2. **Choose Mode**: Toggle "Advanced Mode" checkbox if needed (Simple mode is default)
3. **Start Coding**: Hold annotation buttons during utterances
4. **Save Work**: Click "Save CSV" and enter coder name

### Basic Workflow
1. Load your video file into the application
2. Position video at the start of an utterance
3. Hold the appropriate button (or keyboard key) while the utterance occurs
4. Release when the utterance ends
5. Add notes if needed using the edit function
6. Repeat for all utterances in the video
7. Save your work as a CSV file

### Advanced Features
- **Edit Annotations**: Click any annotation in the sidebar to modify
- **Time Adjustment**: Use ▲▼ buttons for 100ms precision adjustments
- **Load Previous Work**: Import CSV files to continue coding sessions
- **Mode Switching**: Change between simple and advanced coding anytime
- **Reset Session**: Clear all data for a fresh start

## File Formats

### Video Support
- MP4 (H.264 recommended)
- WebM
- Other HTML5-compatible formats

### CSV Structure
The tool generates CSV files with the following columns:
- Utterance_Type_Kid, Start_Time_Kid, End_Time_Kid, Duration_Kid, Note_Kid
- Utterance_Type_Adult, Start_Time_Adult, End_Time_Adult, Duration_Adult, Note_Adult
- Coder_Name

Files include summary statistics and totals appropriate for the coding mode used.

## Research Applications

LexCoder is designed for researchers studying:
- Parent-child interactions in autism
- Communication patterns and development
- Intervention effectiveness
- Behavioral analysis and coding
- Speech-language pathology research

## Browser Compatibility

- ✅ Chrome/Chromium (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Microsoft Edge
- ⚠️ Internet Explorer (Not supported)

## Technical Requirements

- Modern web browser with HTML5 video support
- JavaScript enabled
- Sufficient RAM for video playback
- No internet connection required (runs offline)

## Data Privacy

- All processing happens locally in your browser
- No data is sent to external servers
- Videos and annotations remain on your device
- Suitable for sensitive research data

## Contributing

We welcome contributions from the autism research community! Please feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests
- Share feedback from your research experience

## License

```
Copyright 2025 Hamidreza Komaki

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## Contact

**Developer**: Hamidreza Komaki  
**Email**: HKomaki@Stanford.edu  
**GitHub**: https://github.com/Hamidreza-Komaki

## Acknowledgments

This tool was developed with love for the autism research community, including researchers, clinicians, families, and individuals with autism who contribute to our understanding of communication and development.

## Citation

If you use LexCoder in your research, please consider citing:

```
Komaki, H. (2025). LexCoder: ASD Utterances Annotation Tool. 
GitHub. https://github.com/Hamidreza-Komaki/LexCoder
```

---

**Made with ♥ for the Autism Community**
