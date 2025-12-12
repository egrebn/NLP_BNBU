# NLP Analysis of Tang Dynasty Imperial Edicts

This repository contains Jupyter notebooks for analyzing Tang Dynasty imperial edicts using Natural Language Processing techniques, specifically focusing on SIKU-BERT embeddings for semantic analysis of classical Chinese texts.

## 📚 Notebooks

### 1. Formulaic Sentence Detection (`formulaic_sentence_detection.ipynb`)
Identifies formulaic (standardized) versus unique sentences in Tang Dynasty imperial edicts using SIKU-BERT embeddings and cosine similarity. This analysis helps distinguish between conventional template language and edict-specific content.

**Key Features:**
- Sentence segmentation based on Chinese punctuation
- SIKU-BERT embedding generation
- Similarity analysis with configurable thresholds
- Visual highlighting of formulaic patterns
- Interactive edict comparison

### 2. Semantic Clustering (`semantic_cluster.ipynb`)
Performs semantic clustering of edict passages to identify thematic groups and structural patterns within different types of imperial documents.

**Key Features:**
- DBSCAN clustering with SIKU-BERT embeddings
- Thematic pattern detection
- Cluster visualization and analysis
- Outlier detection for unique passages

### 3. Edicts Similarity Analysis (`edicts_similarity_analysis.ipynb`)
Analyzes content similarity across edicts of specified types using SIKU-BERT embeddings to identify documents with similar semantic content.

**Key Features:**
- Document-level similarity computation
- Comparative analysis across edict types
- Similarity threshold configuration
- Visual similarity matrices

## 📁 Data

- `extracted_edicts_punc.csv` - Processed Tang Dynasty edict corpus with punctuation

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Git

### Installation

1. Clone this repository:
```bash
git clone <repository-url>
cd NLP_BNBU
```

2. Install dependencies:
Each notebook includes its own setup cell with required packages. Run the setup cell in each notebook to install dependencies:
```python
pip install pandas numpy torch transformers scikit-learn matplotlib seaborn tqdm umap-learn
```

3. Launch Jupyter:
```bash
jupyter notebook
```

## 📖 Usage

1. Open any notebook in Jupyter
2. Run the setup/installation cells first
3. Configure parameters (edict type, similarity thresholds, etc.)
4. Execute cells sequentially to perform the analysis
5. Review generated outputs and visualizations

## 🛠️ Key Technologies

- **SIKU-BERT**: Pre-trained language model for classical Chinese texts
- **PyTorch**: Deep learning framework
- **Transformers**: Hugging Face library for pre-trained models
- **scikit-learn**: Machine learning and clustering algorithms
- **pandas**: Data manipulation and analysis
- **matplotlib/seaborn**: Data visualization

## 📝 Notes

- Notebooks are designed to work with Tang Dynasty imperial edict data
- Each notebook includes detailed methodology and configuration options
- SIKU-BERT embeddings are specifically trained for classical Chinese
- Processing large corpora may require GPU acceleration

## 🎓 Academic Context

This work is part of NLP research on classical Chinese imperial documents, focusing on identifying formulaic language patterns and semantic structures in Tang Dynasty administrative texts.

---

For questions or issues, please open an issue in this repository.
