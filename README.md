# Visual Intelligence for Personalized Travel & Finance Optimization

A multimodal AI framework using Vision-Language Models (VLMs) for personalized travel planning and financial optimization.

## 🎯 Project Overview

This system analyzes travel images to:
1. Extract visual preferences and themes
2. Identify geo-locations (landmarks and regions)
3. Generate personalized itineraries
4. Recommend optimal credit card offers

## 📚 Repository Structure
```
├── notebooks/          # Google Colab notebooks (step-by-step)
├── src/               # Source code modules
├── data/              # Datasets (landmarks, test images)
├── outputs/           # Analysis results
└── docs/              # Documentation
```

## 🚀 Quick Start

### Option 1: Google Colab (Recommended)

**Step 1: Image Analysis**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashwin-yedte/visual-intelligence-travel-finance/blob/main/notebooks/Step_1_Image_Analysis.ipynb)

**Step 2: Theme Extraction**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashwin-yedte/visual-intelligence-travel-finance/blob/main/notebooks/Step_2_Theme_Extraction.ipynb)

**Step 3: Geo-Location Identification**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashwin-yedte/visual-intelligence-travel-finance/blob/main/notebooks/Step_3_Geo_Location_Identification.ipynb)

### Option 2: Local Installation
```bash
# Clone repository
git clone https://github.com/ashwin-yedte/visual-intelligence-travel-finance.git
cd visual-intelligence-travel-finance

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 📖 Documentation

- [System Architecture](docs/ARCHITECTURE.md)
- [API Reference](docs/API_REFERENCE.md)
- [User Guide](docs/USER_GUIDE.md)

## 🎓 Academic Information

**Project**: Visual Intelligence for Personalized Travel & Finance Optimization Using Multimodal AI Framework  
**Course**: AIMLCZG628T  
**Institution**: BITS Pilani  
**Student**: Ashwin Kumar Y (2023AC05628)  
**Program**: M.Tech (AIML)  
**Duration**: November 2025 - February 2026

## 🏗️ System Architecture
```
User Upload → Image Analysis (CLIP) → Theme Extraction → Geo-Location ID → 
Itinerary Generation → Financial Optimization → Recommendations
```

## 🛠️ Technology Stack

- **Vision-Language Model**: CLIP (OpenAI)
- **Deep Learning**: PyTorch, Transformers
- **Image Processing**: Pillow, OpenCV
- **Vector Search**: FAISS / ChromaDB
- **Backend**: FastAPI (planned)
- **Frontend**: React (planned)

## 📊 Key Features

✅ Multi-image analysis (1-5 images)  
✅ Indian seashore specialization (Goa, Kerala, Andaman, etc.)  
✅ Theme-based recommendations  
✅ Landmark recognition  
✅ Visual preference learning  

## 🔄 Version History

| Version | Date | Description |
|---------|------|-------------|
| v1.0 | Jan 2026 | Initial release - Step 1 complete |
| v1.1 | Jan 2026 | Step 2 - Theme extraction added |
| v1.2 | Jan 2026 | Step 3 - Geo-location identification |

## 📝 License

This project is part of academic research at BITS Pilani.

## 👨‍💻 Author

**Ashwin Kumar Y**  
M.Tech (AIML), BITS Pilani  
Email: ashwin.yedte@gmail.com

## 🙏 Acknowledgments

- BITS Pilani Work Integrated Learning Programme
- Bank of America Continuum India
- Supervisor: Sridhar Viswanathan
