# **CFP-AUTEXTIFICATION**



**Link:** https://sites.google.com/view/autextification

**Team Number:** Team 30 \
**Team Members:**
1. Harshit Gupta
2. Manav Chaudary 
3. Aneesh Chavan

---

## **Overview**

This repo contains the source code for our work on the Autextification shared task for our term project for SMAI. More information can be found at <a href="https://sites.google.com/view/autextification">https://sites.google.com/view/autextification</a>

## **Description**

The shared task itself has two subtasks
1. **Task A:** Distinguishing between Human and AI generated text.
2. **Task B:** Distinguishing between text generated by a variety of text generation models.

Both subtasks have English and Spanish versions, with and we suitably split them into train, validation and test sets. 

Each Jupyter notebook in this repo contains code for each of our attempts. Running each method involves running each cell of code as instructed in each dataset.

## **Environment and Model Details**

Conda env details can be found in `conda_requirements.txt`

Pip env details can be found in `pip_requirements.txt`

Model weights and checkpoints for models for each method can be found <a href="https://drive.google.com/drive/folders/1A2ts44xq1kJl5ReJJvJEYEXSzdftf6PB">here</a>.

----

## **Attempts Made**

We have tried the following methods:

### **Task A**
- BERT embeddings + PCA on varying embedding sizes
- BERT embeddings + linear layer
- BERT embeddings and sentiment embeddings + linear layer (spanish only)
- BERT embeddings and sentiment and POS embeddings + linear layer (spanish only)
- HuggingFaces pretrained sentence classification BERT

### **Task B**
- BERT embeddings and sentiment embeddings + linear layer
- BERT embeddings and sentiment and POS embeddings + linear layer
- HuggingFaces pretrained sentence classification BERT
- Random forest with xgboost + BERT embeddings
- Ensemble of BERTs treating each classification as binary classification
- Hierachical training of BERTs 


### **Current Progress and Status:**

✓ Datasets Uploaded. \
✓ Models Run. \
✓ Results Compiled. \
✓ Results Analyzed. \
✓ Report Created.

----
