# Drug Substitute Identification and Risk Analysis  
### MSc Business Data Analytics – Final Project Repository
Author: Fatemeh Mashayekhiahangarani

This repository contains the full implementation of the MSc project titled:

**“Drug Substitute Identification and Risk Analysis in the Pharmaceutical Supply Chain Using Data-Driven Similarity and Exploratory Analytics.”**

The project identifies substitute medicines by combining text embeddings, structured pharmaceutical attributes, cosine similarity, clustering, and network analysis. It also introduces two managerial indicators: Substitutability Index (SI) and Shortage Risk Index (SRI).

---

## 1. Repository Structure

![Repository Structure](https://github.com/user-attachments/assets/804d1321-5523-43cc-bc1d-68e7c7dd9099)

## 2. Contents of the Repository

### **Notebook**
`notebooks/FINAL_IBS_PROJECT_FATEMEH.ipynb`  
Contains the full workflow from loading data to generating embeddings, similarity matrices, clustering results, SI/SRI metrics, and final figures.

### **Figures**
Plots used in the dissertation, grouped by chapter.

### **Processed Outputs**
`data/processed/dashboard_summary.csv`  
Summary table used for managerial analysis and dashboard use.

### **Documentation**
`docs/Drug_Substitute_Analysis_Rev0.pdf`  
Project documentation file.

## 3. Run all cells

## How to Run the Results

To reproduce the results of this project, first open the main notebook located at `notebooks/FINAL_IBS_PROJECT_FATEMEH.ipynb`. The required datasets are loaded from Google Drive, and all necessary libraries are installed according to the `requirements.txt` file. By running the notebook from start to finish, all steps—including data processing, similarity computation, clustering, network construction, and the generation of SI and SRI indices—will execute automatically.

All generated visualizations are saved in the `figures/` folder, and the managerial summary file is available at `data/processed/dashboard_summary.csv`. This structure ensures that the entire workflow is fully reproducible, and identical results can be obtained with each rerun.

## 4. Dependencies

This project relies on several Python libraries for data processing, text embedding, similarity analysis, clustering, and visualization. All core dependencies are listed in the `requirements.txt` file. The main libraries used include:

- **pandas** – for data cleaning, manipulation, and analysis  
- **numpy** – for numerical operations and matrix handling  
- **scikit-learn** – for one-hot encoding, clustering, cosine similarity, and evaluation utilities  
- **sentence-transformers** – for generating Sentence-BERT text embeddings  
- **torch** – required backend for running the embedding model  
- **matplotlib** and **seaborn** – for visual exploratory data analysis and plotting  
- **networkx** – for constructing and analysing the substitution network  
- **tqdm** – for progress tracking during long-running operations  











