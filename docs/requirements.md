# Requirements

## Functional requirements (what the system must DO)
1. The system shall allow users to upload an image in JPG or PNG format.
2. The system shall reject uploaded images that exceed 10 MB or use an unsupported file format.
3. The system shall allow users to select one of the five supported Silat Cekak poses before classification.
4. The system shall use the trained CNN model to classify an uploaded image as either “Correct” or “Incorrect”.
5. The system shall display the predicted class and its associated confidence score after successful classification.

## Non-functional requirements (how the system must PERFORM)
1. The system shall return a classification result within 5 seconds for at least 95% of valid uploads.
2. The trained model shall achieve at least 80% accuracy on a held-out test dataset that is not used for training or model selection.
3. The system shall display an appropriate error message for invalid-file test cases in the defined test suite.
