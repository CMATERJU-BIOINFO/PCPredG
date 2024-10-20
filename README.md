# _PCPredG_: Protein Complex Prediction Using Graphlet Features
![COmplexPred](https://github.com/CMATERJU-BIOINFO/ComplexPredGraphlet/assets/56863228/9d7d707d-c903-43cc-acf7-58c811985433)

Proteins interact with other biomolecules to form complexes, playing crucial roles in biological functions and responding to environmental signals. Predicting these protein complexes is a challenging yet vital task with limited exploration in existing research.

**PCPredG** is a novel method designed for predicting 3-node protein complexes from protein-protein interaction (PPI) networks using 5-node graphlet features. The **CORUM protein complex repository** was used to curate positive and negative samples, with **MCODE** and **MCL clustering algorithms** supporting the dataset preparation.

## Key Features

- Utilizes **Random Forest (RF)**  classifier trained with **CORUM** complexes in a **10-fold cross-validation** setup.
- Experiments run in both **balanced and imbalanced: (1:1 to 1:10)** setups.
- Introduces a **10-fold quality consensus** on hold-out datasets for performance validation.
- Achieved best performance with the **Random Forest (RF) classifier** in both balanced and imbalanced experiments.
  
### Performance comparison

PCPredG's performance was compared against several advanced models, including:

- **Support Vector Machine (SVM)**
- **GCN (Graph Convolutional Networks)**
- **GAT (Graph Attention Networks)**
- **Ensemble of GCN and GAT**
- **Polarized Message Passing Graph Neural Network (PMP-GNN)**

## Datasets

- The dataset was sourced from the **CORUM protein complex repository**, with data curation handled by **MCODE** and **MCL clustering algorithms** to ensure accurate positive and negative samples.
- Interaction data: **DIP**, **HIPPIE**



## Performance

- **Best performance** was achieved using the **Random Forest (RF)** classifier.
- A detailed comparison was made across both balanced and imbalanced setups.
- A **10-fold quality consensus** was introduced on the hold-out set to ensure the robustness of the results.


