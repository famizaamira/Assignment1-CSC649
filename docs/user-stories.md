# User Stories

1. As a Silat Cekak practitioner, I want to upload an image of my pose, so that I can check whether it meets the     defined correctness criteria. (FR1, FR2, FR3, FR4)
    Acceptence criteria:
    - Only JPG and PNG file image can be uploaded to allow system to accept the image
    - Rejected image like unsupported file or large size of image more than 10MB will make the system display an         appropriate error message.

2. As a Silat Cekak practitioner, I want the system to classify my uploaded pose as correct or incorrect, so that I can identify whether it meets the expected pose criteria. (FR4, FR5)
    Acceptence criteria:
    - Valid upload image will make the system analyze and display the classification.
    - If practitioner pose is correct then the system will display result as correct.

3. As a Silat Cekak practitioner, I want to view the classification result and confidence score, so that I can understand the system's assessment of my pose (FR5).
   Acceptance criteria:
   - If the classification success, then system will display the predicted class and confidence score.
   - If fails, then system will display error message. 

