# LexCoder: ASD Utterances Annotation Tool
## 🧠 Overview

**LexCoder** is a professional-grade, web-based annotation tool specifically designed for coding and analyzing utterances in Autism Spectrum Disorder (ASD) research. This tool enables researchers to efficiently annotate video recordings of interactions between children with ASD and adults, providing comprehensive data collection for behavioral and linguistic analysis.

### 🎯 Key Features

- **🎥 Video Integration**: Load and synchronize video files with annotation timeline
- **👥 Dual-Speaker Coding**: Separate annotation tracks for Kid and Adult utterances
- **🏷️ 5-Category Classification System**:
  - Unintelligible
  - Imitative  
  - Verbal Prompt
  - Non-Verbal Prompt
  - Spontaneous
- **📝 Notes Support**: Add contextual notes to any utterance
- **⌨️ Keyboard Shortcuts**: Efficient coding with customizable hotkeys
- **📊 Real-time Statistics**: Live counts and summaries
- **💾 CSV Export/Import**: Professional data exchange format
- **🎨 Visual Subtitles**: Color-coded utterance display with notes
- **⏯️ Video Controls**: Frame-accurate navigation and playback

## 🚀 Quick Start

### Online Version
1. Open `lexcoder.html` in any modern web browser
2. Click "Load Video" to select your research video file
3. Use keyboard shortcuts or mouse clicks to code utterances
4. Export your coded data as CSV for analysis

### Keyboard Shortcuts

#### Kid Utterances
- `A` - Unintelligible
- `S` - Imitative  
- `D` - Verbal Prompt
- `F` - Non-Verbal Prompt
- `V` - Spontaneous

#### Adult Utterances
- `N` - Unintelligible
- `J` - Imitative
- `K` - Verbal Prompt  
- `L` - Non-Verbal Prompt
- `;` - Spontaneous

#### Video Navigation
- `Space` - Play/Pause
- `←` - Skip back 1 second
- `→` - Skip forward 1 second

## 📋 Supported File Formats

### Video Files
- **MP4** (H.264 recommended)
- **WebM** 
- **MOV**
- **AVI** (browser dependent)

### Data Files
- **CSV Import/Export** (8, 10, or 11 column formats)
- **Legacy format support** for existing datasets

## 🔬 Research Applications

LexCoder is designed for:

- **Autism Spectrum Disorder Research**: Behavioral interaction analysis
- **Language Development Studies**: Utterance classification and timing
- **Therapeutic Intervention Assessment**: Pre/post treatment comparisons  
- **Parent-Child Interaction Research**: Communication pattern analysis
- **Educational Research**: Learning environment observations
- **Clinical Assessment**: Diagnostic and progress monitoring

## 📊 Data Export Format

### 11-Column CSV Structure
```csv
Utterance_Type_Kid,Start_Time_Kid,End_Time_Kid,Duration_Kid,Note_Kid,
Utterance_Type_Adult,Start_Time_Adult,End_Time_Adult,Duration_Adult,Note_Adult,Coder_Name

# Automatic totals section included:
TOTALS_Kid,,,,,TOTALS_Adult,,,,,
Unintelligible_Kid,[count],,,,Unintelligible_Adult,[count],,,,
# ... (detailed breakdowns for all categories)
```

## 🛠️ Technical Specifications

### Requirements
- **Browser**: Chrome 88+, Firefox 85+, Safari 14+, Edge 88+
- **Memory**: 4GB RAM minimum (8GB recommended for large videos)
- **Storage**: Video file size dependent
- **Network**: None required (fully offline capable)

### Architecture
- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Video Engine**: Native HTML5 video API
- **File Handling**: File API with drag-and-drop support
- **Data Processing**: Client-side CSV parsing and generation
- **UI Framework**: Custom responsive design

## 📈 Performance Metrics

- **Video Load Time**: < 3 seconds for typical research videos
- **Annotation Precision**: Frame-accurate timing (±0.001s)
- **Export Speed**: 1000+ annotations processed in < 1 second
- **Memory Usage**: ~50MB base + video file size
- **Compatibility**: 99%+ modern browser support

## 🔧 Advanced Features

### Professional Workflow
- **Coder Attribution**: Automatic coder name integration
- **Version Control**: Compatible with research data management
- **Batch Processing**: Multiple session support
- **Quality Assurance**: Built-in validation and error checking

### Customization Options
- **Subtitle Display**: Toggle and customize overlay appearance  
- **Color Coding**: Visual distinction between speaker types
- **Timing Precision**: Millisecond-level accuracy
- **Note Categories**: Flexible annotation system

## 📚 Documentation

### User Guides
- [Getting Started Guide](docs/getting-started.md)
- [Keyboard Shortcuts Reference](docs/shortcuts.md)
- [Data Export Guide](docs/data-export.md)
- [Troubleshooting](docs/troubleshooting.md)

### For Researchers
- [Research Methodology Integration](docs/research-methods.md)
- [Statistical Analysis Preparation](docs/statistical-analysis.md)
- [Multi-Coder Reliability](docs/inter-rater-reliability.md)

## 🏆 Citation

If you use LexCoder in your research, please cite:

```bibtex
@software{lexcoder2025,
  title={LexCoder: ASD Utterances Annotation Tool},
  author={Komaki, Hamidreza},
  year={2025},
  institution={Stanford University},
  url={https://github.com/Hamidreza-Komaki/LexCoder}
}
```

## 🤝 Contributing

### Research Collaborations
We welcome collaborations with research institutions and clinical practitioners. For partnership inquiries:

**Contact**: HKomaki@Stanford.edu

### Feature Requests
- Autism research community feedback
- Clinical workflow improvements  
- Educational use case adaptations

## 📄 License

**Proprietary Software** - Copyright © 2025 Hamidreza Komaki

This software is proprietary and confidential. Unauthorized copying, distribution, modification, or use is strictly prohibited. For licensing inquiries, contact: HKomaki@Stanford.edu

## 🏥 Institutional Use

### Stanford University
Developed at Stanford University for autism research applications.

### Research Partnerships
Available for collaborative research projects. Contact for institutional licensing.

## 🔗 Links

- **Developer**: [Hamidreza Komaki](https://github.com/Hamidreza-Komaki)
- **Institution**: Stanford University
- **Email**: HKomaki@Stanford.edu
- **Research Area**: Autism Spectrum Disorder, Behavioral Analysis

## 🆕 Version History

### v1.0.0 (2025)
- Initial release
- Full utterance coding system
- CSV import/export functionality
- Video synchronization
- Keyboard shortcut system
- Notes and coder attribution
- Professional statistical summaries

---

**Developed with ❤️ for the autism research community**

*LexCoder: Empowering researchers with precision tools for understanding communication in autism.*
