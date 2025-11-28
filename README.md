# Face-Mask-Detection-
FACE MASK DETECTION PROJECT
This project detects whether a person is wearing a face mask using deep learning.

### Requirements
Ensure you have Python installed. Install dependencies using:
pip install -r requirements.txt

### Training the Model
Run the following Jupyter Notebook to train the face mask detection model:
File1_FaceMask_Model.ipynb
This notebook trains a model using MobileNetV2 and saves it for later use.

### Running the Detector
Once the model is trained, use the following notebook to test mask detection:
File2_Mask_Detector.ipynb
It will load the trained model and process input images to detect whether a mask is worn.

### Dataset
Dataset with images labeled as `with_mask` and `without_mask`. The dataset directory structure look like:
dataset/
│── with_mask/
│── without_mask/

