Through this project, I learned how margin-based models (SVM) handle overlapping classes, and why feature scaling and kernel choice directly affect decision boundaries and false negatives.

| Model | Feature Scaling | Kernel | Accuracy | False Negatives (FN) |
|------|----------------|--------|----------|---------------------|
| SVM  | No           | Linear | 0.956    | 4 |
| SVM  | Yes          | Linear | 0.973 ↑  | 2 ↓ |
| SVM  | Yes          | RBF    | 0.982 ↑  | 1 ↓ |



