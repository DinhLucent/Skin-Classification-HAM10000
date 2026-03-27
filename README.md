# Skin-Classification-HAM10000

Deep learning project for classifying skin lesions into 7 diagnostic categories using the HAM10000 dataset and PyTorch.

## Features
- **Multi-class Classification**: Targeted at identifying Melanocytic nevi, Melanoma, Benign keratosis, and more.
- **Data Augmentation**: Standardized pipeline for balancing the dataset.
- **Model Evaluation**: Detailed reporting on accuracy, precision, and confusion matrices.

## Tech Stack
- **Language**: Python 3.8+
- **Framework**: PyTorch, torchvision
- **Dataset**: [HAM10000](https://www.nature.com/articles/sdata2018161)
- **Domain**: Biomedical Engineering (Dermatology)

## Project Structure
```
├── README.md
├── LICENSE
├── .gitignore
├── src/                # Core Python scripts and model definitions
├── notebooks/          # Exploration results and analysis
├── models/             # Saved model weights
├── results/            # Performance metrics and plots
└── data/               # HAM10000 dataset storage (local)
```

## Getting Started

### Prerequisites
- Python 3.8+
- PyTorch and Torchvision
- Pandas, Scikit-learn, Matplotlib

### Installation
```bash
git clone https://github.com/DinhLucent/Project2B-Skin-Classification-HAM10000.git
cd Project2B-Skin-Classification-HAM10000
pip install -r requirements.txt
```

### Usage
```bash
# To run exploratory data analysis
# (Check notebooks folder)

# To train the model
python src/train.py
```

## Demo
Detailed evaluation reports and confusion matrices can be found in the `results/` directory after local execution.

## License
MIT License — see [LICENSE](LICENSE)

---
Built by [DinhLucent](https://github.com/DinhLucent)
