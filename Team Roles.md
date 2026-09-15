🦠 Project 6: Malaria Cell Detection & Explainable Computer Vision

👥 Team Task Distribution – 6 Members

👤 Member 1 — Data Preparation & EDA

Responsibilities:

- Download and organize the Malaria Cell Images Dataset.
- Analyze dataset size and class distribution.
- Check image quality, corrupted images, duplicates, and near-duplicates.
- Create reproducible Train / Validation / Test splits.
- Perform image preprocessing: resizing, normalization, and basic transformations.
- Perform EDA:
  - Class distribution
  - Image dimensions
  - Pixel intensity
  - Brightness and contrast
  - Sample infected/uninfected images
- Prepare the final cleaned dataset pipeline.
- Create the data dictionary.

Deliverables:

- Data preparation notebook/script.
- EDA notebook/report.
- Clean dataset structure.
- Data dictionary.
- Reproducible train/validation/test split.
- Data validation script.

---

👤 Member 2 — SQL & Classical Machine Learning

Responsibilities:

- Design the SQL database for image metadata and experiment results.
- Create tables for images, classes, splits, models, and predictions.
- Write at least 10 meaningful analytical SQL queries.
- Use JOIN, CTE, GROUP BY, and Window Functions where applicable.
- Extract handcrafted image features:
  - HOG
  - Color features
  - Texture features
- Build the Classical ML baseline.
- Train and compare:
  - SVM
  - Random Forest
- Perform preprocessing and feature scaling where needed.
- Evaluate the Classical ML models.
- Generate confusion matrix and per-class metrics.

Deliverables:

- SQL schema.
- 10+ analytical SQL queries.
- HOG/Color/Texture feature extraction code.
- SVM model.
- Random Forest model.
- Classical ML comparison table.
- Confusion matrices and evaluation results.

---

👤 Member 3 (Me) — Custom CNN & Deep Learning

Responsibilities:

- Design and implement the Custom CNN architecture.
- Prepare image input pipeline for Deep Learning.
- Apply data augmentation on training data.
- Train the CNN model.
- Use:
  - Early Stopping
  - Learning Rate Scheduling
  - Dropout / Regularization
  - Model Checkpointing
- Analyze training and validation curves.
- Evaluate the CNN on the test set.
- Perform error analysis on CNN predictions.
- Save the final trained CNN model.

Deliverables:

- Custom CNN notebook/script.
- CNN architecture.
- Training/validation curves.
- Saved CNN model.
- Confusion matrix.
- Precision, Recall, F1, ROC-AUC and PR-AUC.
- CNN error analysis.

---

👤 Member 4 — Transfer Learning & Grad-CAM

Responsibilities:

- Select and implement a pretrained CNN such as:
  - EfficientNet
  - ResNet
  - MobileNet
- Prepare the transfer-learning pipeline.
- Train the classifier using the pretrained model.
- Perform fine-tuning.
- Apply data augmentation.
- Use Early Stopping and Learning Rate Scheduling.
- Compare Transfer Learning with the Custom CNN.
- Implement Grad-CAM or a similar visual explanation technique.
- Generate Grad-CAM visualizations for correct and incorrect predictions.
- Analyze which image regions influence model predictions.

Deliverables:

- Transfer Learning notebook/script.
- Fine-tuned pretrained model.
- Model performance results.
- Custom CNN vs Transfer Learning comparison.
- Grad-CAM implementation.
- Grad-CAM visualizations.
- Explainability analysis.

---

👤 Member 5 — Model Evaluation, Robustness & MLOps

Responsibilities:

- Collect and organize results from all ML and DL models.
- Create the final model comparison table:
  - SVM
  - Random Forest
  - Custom CNN
  - Transfer Learning
- Evaluate:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
  - PR-AUC
  - Confusion Matrix
- Focus on Recall/Sensitivity for the Infected class.
- Perform detailed error analysis.
- Perform robustness testing using:
  - Blur
  - Brightness changes
  - Rotation
  - Other image perturbations
- Compare model performance under normal and perturbed images.
- Implement model/version metadata.
- Implement prediction logging.
- Prepare model evaluation reports.

Deliverables:

- Final model comparison table.
- Error analysis report.
- Robustness testing pipeline.
- Robustness results.
- Model versioning/metadata.
- Prediction logging.
- Final evaluation report.

---

👤 Member 6 — Streamlit, Testing, Docker & Integration

Responsibilities:

- Build the Streamlit application.
- Create image upload functionality.
- Connect the application with the final trained model.
- Display:
  - Uploaded image
  - Predicted class
  - Confidence/probability
  - Grad-CAM heatmap
  - Model version
- Add a clear disclaimer that the system is an educational/research prototype and not a clinical diagnostic tool.
- Integrate prediction logging.
- Create basic UI/model/data tests.
- Prepare Dockerfile and Docker configuration.
- Test the complete application locally through Docker.
- Organize the final GitHub repository.
- Prepare README and setup instructions.
- Integrate all team members' components into the final system.

Deliverables:

- Complete Streamlit application.
- Image upload and prediction interface.
- Grad-CAM integration.
- Prediction history/logging.
- Test folder with basic tests.
- Dockerfile.
- requirements.txt.
- README.md.
- Final integrated GitHub repository.
- Dockerized working application.

---

🔗 Final Integration

The project workflow will be:

Dataset
↓
Data Preparation & EDA
↓
SQL / Metadata
↓
Classical ML Baseline
↓
Custom CNN
↓
Transfer Learning
↓
Grad-CAM / Explainability
↓
Model Evaluation & Robustness
↓
MLOps / Prediction Logging
↓
Streamlit Application
↓
Docker
↓
GitHub + Final Demo

📊 Shared Final Deliverables

All team members will collaborate on:

- Final Architecture Diagram
- Final Model Comparison
- Final Technical Report
- Responsible AI / Limitations Section
- Final Presentation
- Live Demo
- Technical Defense
- GitHub Documentation

⚖️ Workload Distribution

Member| Main Area| Major Work
1| Data + EDA| Dataset + Preprocessing + EDA
2| SQL + Classical ML| SQL + HOG/Color/Texture + SVM/RF
3| Custom CNN| CNN + Augmentation + Training
4| Transfer Learning + Explainability| Pretrained CNN + Fine-tuning + Grad-CAM
5| Evaluation + MLOps| Comparison + Robustness + Logging
6| Deployment + Integration| Streamlit + Testing + Docker + GitHub

Important: Each member is responsible for both implementation and documentation of their assigned part. All members should understand the complete project for the final technical defense.