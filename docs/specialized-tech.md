# Specialized Technology

## Concept
The project uses computer vision and a CNN model with MobileNetV2 transfer learning to classify uploaded Silat Cekak pose images as correct or incorrect. The system displays predictions with confidence scores and evaluates performance using accuracy, precision, recall, and F1-score.

For example, if the model predicts 87% confidence for “Correct,” the system will display “Correct with 87% confidence” if the predefined confidence threshold is met.

## Framework, Model, Methods and Tools
1. Convolutional Neural Network (CNN) – Used as the main algorithm to classify Silat Cekak poses by identifying patterns in images.
2. MobileNetV2 – A lightweight CNN architecture that provides efficient image classification with lower computational requirements.
3. Transfer Learning – Uses a pretrained CNN model to reduce training requirements, especially when the dataset is small.
4. TensorFlow and Keras – Used to prepare image datasets, load the pretrained model, configure the classification layer, train the model, and make predictions.
5. Scikit-learn – Used to evaluate model performance through accuracy, precision, recall, F1-score, and a confusion matrix.

## Fit to problem
This project helps Silat Cekak practitioners check their poses when an instructor is unavailable. A CNN model will classify uploaded images as correct or incorrect and provide confidence scores. A certified instructor will define the correctness criteria to ensure reliable classification.

## Benifit
- Feature learning
- Simple Input method
- Potential for web deployment

## Limitation
- Limited dataset
- Image bias
- Single image limitation

## sources
IBM. (2021, July 27). What is computer vision? Ibm.Com. https://www.ibm.com/think/topics/computer-vision
IBM. (2024, June 17). Deep learning. Ibm.Com. http://ibm.com/think/topics/deep-learning
Watanabe, S., Liao, C.-C., Wu, E., & Koike, H. (2026). Seeing and saying movement: Combining skeleton visualization and LLM feedback for motor skill coaching. Proceedings of the Augmented Humans International Conference 2026, 691–697. https://doi.org/10.1145/3795011.3795054