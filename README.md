# Handwritten-Signature-Verification-using-ResNet18

### Topic Information
This project involves developing a machine learning model to verify the authenticity of handwritten signatures using CNN architecture.

### Dataset Description
The project utilizes three benchmark datasets containing offline handwritten genuine and forged signatures:
- **CEDAR**: Contains English signatures.
- **BHSig260-Hindi**: Contains Hindi signatures.
- **BHSig260-Bengali**: Contains Bengali signatures.

### Steps in Data Preprocessing
- Renamed files in the CEDAR dataset for consistency.
- Collected data and labels from CEDAR, BHSig260-Hindi, and BHSig260-Bengali datasets.
- Created a unified dataset and split it into training, validation, and test sets.
- Applied image transformations (resizing and converting to tensor).

### Model Used: ResNet18
ResNet18 is chosen due to its:
- Ability to handle complex image recognition tasks.
- Efficient training with residual connections to prevent vanishing gradients.
- Pre-trained on large datasets, providing strong feature extraction capabilities.

### Results and Conclusion
The model achieved:
- **Validation Accuracy:** 95.02%
- **Validation Precision:** 94.51%
- **Validation Recall:** 94.38%
- **Validation F1-Score:** 94.44%

The confusion matrix showed the model's robust performance in distinguishing between genuine and forged signatures, indicating high accuracy and reliability in signature verification tasks.


#### Code comments are added to each and every code for more clarity.
