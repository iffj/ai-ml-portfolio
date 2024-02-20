### Project Title
Detecting Brain Tumors in MRI Images Using the VGG-16 Model

**Author**
Jaehyeong Lee

#### Executive summary
The model demonstrated a significant improvement over the baseline performance of 61.54%. The final test confusion matrix showed a high level of precision in tumor detection, with an accuracy of 85.71%, precision of 77.78%. Training and validation loss and accuracy metrics indicated a stable convergence, with the model achieving a validation accuracy of up to 85.42%, highlighting its robustness and potential for clinical application.

The VGG-16 model has proven to be a valuable tool for detecting brain tumors in MRI images, offering improvements in accuracy and efficiency. The project's success opens avenues for further research and development, including the potential for real-world clinical deployment and the exploration of other advanced models to further enhance diagnostic capabilities.

#### Rationale
The project leverages advanced deep learning to improve the accuracy and efficiency of diagnosing brain tumors. By automating detection with the VGG-16 model, it aims to support medical professions by providing more consistent and objective assessments.

#### Research Question
How does the application of the VGG-16 deep learning model improve the accuracy and efficiency of brain tumor detection in MRI images?

#### Data Sources
[Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

#### Methodology
1. Data Preparation: Collect and preprocess a dataset of MRI images, including tumor and non-tumor cases.

2. Model Implementation: Use the VGG-16 deep learning model, adjusting it for brain tumor detection.

3. Training and Testing: Train the model on the dataset and evaluate its performance using accuracy, precision, and recall metrics.

4. Analysis: Compare the model's detection capabilities against baseline methods to assess improvements in accuracy and efficiency.

#### Results
The application of the VGG-16 deep learning model for detecting brain tumors in MRI images yielded significant findings, as summarized below:

**Model Performance**

The model achieved a test accuracy of 85.71%, demonstrating a high capability in distinguishing between tumor and non-tumor MRI images. This represents a notable improvement over the baseline performance of 61.54%.
Precision was calculated at 77.78%, indicating that when the model predicted a tumor, it was correct approximately 77.78% of the time.

**Training and Validation Metrics**

During training, the model's loss decreased from an initial 4.99 to 1.77, indicating successful learning and adaptation to the dataset. Similarly, accuracy improved from 55.84% to 75.63%.
In the validation phase, loss reduced from 2.85 to 0.53, and accuracy increased from 52.08% to 85.42%. These trends reflect the model's ability to generalize well to unseen data, a critical factor for real-world applications.


#### Next steps
1. Model Optimization: Fine-tune the VGG-16 model parameters and architecture to enhance its accuracy and efficiency.

2. Dataset Expansion: Increase the diversity and size of the MRI image dataset to include a wider variety of tumor types, sizes, and locations. This can help in generalizing the model’s detection capabilities.

3. Clinical Validation: Collaborate with medical professionals to validate the model's predictions against clinical outcomes, ensuring its practical applicability and reliability in a real-world setting.

#### Outline of project

- [Jupyter Notebook](https://github.com/iffj/ai-ml-portfolio/blob/main/capstone/capstone.ipynb)

##### Contact and Further Information
jhlee127@gmail.com
