# K-Nearest Neighbors Classifier

This project implements a **distance-weighted K-Nearest Neighbor (KNN)** classifier on a 2-dimensional dataset. The analysis explores how different distance measures influence classification accuracy.

## Project Structure

- **AssignmentKNN1.ipynb**: Jupyter notebook with the KNN implementation, experiments, and evaluation.  
- **AssignmentKNN1.pdf**: PDF version of the assignment with problem statement and instructions.  
- **knnData.csv**: Dataset containing training and test points with class labels.  

## Dataset Description

The dataset (`knnData.csv`) includes:  
- **Training Points**: 2D coordinates with class labels.  
- **Test Points**: 2D coordinates with true labels for evaluation.  

The dataset contains **two classes** (as shown in the assignment figure).  

## Research Questions and Hypotheses

1. **Effect of Distance Measures**  
   - *Hypothesis*: Different norms (L1, L2, L∞) will produce varying accuracy rates.  
2. **Choice of k = 3**  
   - *Hypothesis*: Using 3 nearest neighbors balances sensitivity to noise and generalization.  
3. **Weighted vs. Unweighted KNN**  
   - *Hypothesis*: Distance-weighted voting will improve classification compared to simple majority voting.  

## Requirements

To run the notebook, install these packages:  

```bash
pip install numpy pandas
```

## Instructions

1. **Open the Notebook**: Use Jupyter Notebook or JupyterLab to open `AssignmentKNN1.ipynb`.  
2. **Run Experiments**:  
   - Implement 3-NN from scratch (no scikit-learn KNN).  
   - Test with distance measures:  
     - **L2 norm (Euclidean distance)**  
     - **L1 norm (Manhattan distance)**  
     - **L∞ norm (Chebyshev distance)**  
3. **Evaluate Accuracy**:  
   - Compare predicted labels with ground truth for test points.  
   - Record accuracy for each distance measure.  

## Questions Answered

- What is the classification accuracy of 3-NN under different distance metrics?  
- How does the choice of distance metric affect decision boundaries?  
- Does distance-weighted voting yield improvements over unweighted voting?  

## License

This project is provided for educational purposes.  
