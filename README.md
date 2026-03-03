This project focused on classifying mental workload using EEG data through three different models:
🔹 Logistic Regression (baseline)
 🔹 Convolutional Neural Network (CNN)
 🔹 Transformer-based Model (self-attention mechanism)
🧪 Key Results:
CNN achieved the best performance: 93.6% average accuracy across 5-fold cross-validation.
Transformer performed well but was less suited to the small dataset (avg. 88% accuracy).
Logistic Regression served as a basic reference with lower performance (~68%).
🧠 EEG Insights:
We analyzed EEG data across five frequency bands (Delta to Gamma), extracted 310 features per trial, and applied deep learning techniques to classify mental workload states. The CNN’s layered architecture (with ReLU, dropout, and batch learning) was especially effective in capturing meaningful patterns.
